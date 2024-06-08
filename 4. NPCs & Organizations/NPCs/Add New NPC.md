---
database-plugin: basic
---

```yaml:dbfolder
name: NPC-Db
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
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Name:
    input: text
    accessorKey: Name
    key: Name
    id: Name
    label: Full-Name
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Race:
    input: select
    accessorKey: Race
    key: Race
    id: Race
    label: Race
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 109
    options:
      - { label: "Human", value: "Human", color: "hsl(17, 95%, 90%)"}
      - { label: "Gnome", value: "Gnome", color: "hsl(101, 95%, 90%)"}
      - { label: "Monster", value: "Monster", color: "hsl(306, 95%, 90%)"}
      - { label: "Drow", value: "Drow", color: "hsl(64, 95%, 90%)"}
      - { label: "Vampire", value: "Vampire", color: "hsl(2, 95%, 90%)"}
      - { label: "Dragon", value: "Dragon", color: "hsl(264, 95%, 90%)"}
      - { label: "Fey", value: "Fey", color: "hsl(136, 95%, 90%)"}
      - { label: "Dwarf", value: "Dwarf", color: "hsl(72, 95%, 90%)"}
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
  Gender:
    input: select
    accessorKey: Gender
    key: Gender
    id: Gender
    label: Gender
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 59
    options:
      - { label: "Male", value: "Male", color: "hsl(113, 95%, 90%)"}
      - { label: "Female", value: "Female", color: "hsl(319, 95%, 90%)"}
      - { label: "Other", value: "Other", color: "hsl(337, 95%, 90%)"}
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
  status:
    input: select
    accessorKey: status
    key: status
    id: newColumn4
    label: Status
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Alive", value: "Alive", color: "hsl(285, 95%, 90%)"}
      - { label: "Dead", value: "Dead", color: "hsl(101, 95%, 90%)"}
      - { label: "Unknown", value: "Unknown", color: "hsl(332, 95%, 90%)"}
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
  AssociatedGroup:
    input: relation
    accessorKey: AssociatedGroup
    key: AssociatedGroup
    id: AssociatedGroup
    label: AssociatedGroup
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 200
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      related_note_path: 4. NPCs & Organizations/Organizations/Add New Organization.md
      bidirectional_relation: true
      relation_color: hsl(296,92%,20%)
config:
  remove_field_when_delete_column: false
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
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 200
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: true
  implementation: default
filters:
  enabled: false
  conditions:
```