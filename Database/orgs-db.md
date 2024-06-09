---

database-plugin: basic

---

```yaml:dbfolder
name: orgs-db
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isHidden: false
    sortIndex: -1
    width: -22
    isSorted: false
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      wrap_content: false
      content_vertical_alignment: align-top
      content_alignment: text-align-left
  Name:
    input: text
    accessorKey: Name
    key: Name
    id: Name
    label: Name
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: 0
    width: 204
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      content_alignment: text-align-left
      content_vertical_alignment: align-top
  parent:
    input: relation
    accessorKey: parent
    key: parent
    id: newColumn5
    label: Part Of
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 179
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      related_note_path: Database/orgs-db.md
      relation_color: hsl(236,47%,35%)
      content_alignment: text-align-left
      wrap_content: true
      content_vertical_alignment: align-top
  Subsidiary:
    input: relation
    accessorKey: Subsidiary
    key: Subsidiary
    id: Subsidiary
    label: Subsidiary
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 128
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      related_note_path: Database/orgs-db.md
      relation_color: hsl(209,59%,44%)
      content_alignment: text-align-left
      content_vertical_alignment: align-top
  Partnership:
    input: relation
    accessorKey: Partnership
    key: Partnership
    id: Partnership
    label: Partnership
    position: 10
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 113
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      related_note_path: Database/orgs-db.md
      bidirectional_relation: true
      relation_color: hsl(119,88%,29%)
      content_alignment: text-align-left
      content_vertical_alignment: align-top
  Designation:
    input: select
    accessorKey: Designation
    key: Designation
    id: Designation
    label: Designation
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 146
    options:
      - { label: "Company", value: "Company", color: "hsl(156, 95%, 90%)"}
      - { label: "Clan", value: "Clan", color: "hsl(28, 95%, 90%)"}
      - { label: "Faction", value: "Faction", color: "hsl(151, 95%, 90%)"}
      - { label: "Party", value: "Party", color: "hsl(312, 95%, 90%)"}
      - { label: "Noble House", value: "Noble House", color: "hsl(240, 95%, 90%)"}
      - { label: "Kingdom", value: "Kingdom", color: "hsl(107, 95%, 90%)"}
      - { label: "Institute", value: "Institute", color: "hsl(173, 95%, 90%)"}
      - { label: "Guild", value: "Guild", color: "hsl(61, 95%, 90%)"}
      - { label: "Cult", value: "Cult", color: "hsl(76, 95%, 90%)"}
      - { label: "Empire", value: "Empire", color: "hsl(100, 95%, 90%)"}
      - { label: "Continent", value: "Continent", color: "hsl(150, 95%, 90%)"}
      - { label: "Criminal", value: "Criminal", color: "hsl(182, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
      content_alignment: text-align-left
      content_vertical_alignment: align-top
  Homebase:
    input: relation
    accessorKey: Homebase
    key: Homebase
    id: newColumn7
    label: Homebase
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 162
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      related_note_path: Database/location-db.md
      relation_color: hsl(138,32%,27%)
      content_alignment: text-align-left
      content_vertical_alignment: align-top
  Enemies:
    input: relation
    accessorKey: Enemies
    key: Enemies
    id: Enemies
    label: Enemies
    position: 11
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 166
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      related_note_path: Database/orgs-db.md
      bidirectional_relation: true
      relation_color: hsl(0,71%,33%)
      content_alignment: text-align-left
      content_vertical_alignment: align-top
  Leader:
    input: relation
    accessorKey: Leader
    key: Leader
    id: newColumn9
    label: Leader
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 135
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      related_note_path: Database/char-db.md
      relation_color: hsl(276,51%,40%)
      content_alignment: text-align-left
      content_vertical_alignment: align-top
      wrap_content: true
  Status:
    input: select
    accessorKey: Status
    key: Status
    id: newColumn10
    label: Status
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Active", value: "Active", color: "hsl(87,59%,58%)"}
      - { label: "Inactive", value: "Inactive", color: "hsl(217,20%,35%)"}
      - { label: "Unknown", value: "Unknown", color: "hsl(175, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
      content_alignment: text-align-left
      content_vertical_alignment: align-top
  Member:
    input: relation
    accessorKey: Member
    key: Member
    id: Member
    label: Member
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 226
    isSorted: false
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      bidirectional_relation: true
      related_note_path: Database/char-db.md
      relation_color: hsl(179,58%,32%)
      content_alignment: text-align-left
      wrap_content: true
      content_vertical_alignment: align-top
config:
  remove_field_when_delete_column: true
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: query
  source_form_result: "FROM \"4. NPCs & Organizations/Organizations\""
  source_destination_path: 4. NPCs & Organizations/Organizations
  row_templates_folder: /
  current_row_template: 
  pagination_size: 105
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```