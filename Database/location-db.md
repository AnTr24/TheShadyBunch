---

database-plugin: basic

---

```yaml:dbfolder
name: location-db
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
      footer_formula: 
  Designation:
    input: select
    accessorKey: Designation
    key: Designation
    id: Designation
    label: Designation
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Continent", value: "Continent", color: "hsl(3, 95%, 90%)"}
      - { label: "City", value: "City", color: "hsl(118, 95%, 90%)"}
      - { label: "Region", value: "Region", color: "hsl(307, 95%, 90%)"}
      - { label: "Dwelling", value: "Dwelling", color: "hsl(227, 95%, 90%)"}
      - { label: "Cave", value: "Cave", color: "hsl(207, 95%, 90%)"}
      - { label: "Castle", value: "Castle", color: "hsl(11, 95%, 90%)"}
      - { label: "Village", value: "Village", color: "hsl(219, 95%, 90%)"}
      - { label: "Town", value: "Town", color: "hsl(328, 95%, 90%)"}
      - { label: "World", value: "World", color: "hsl(187, 95%, 90%)"}
      - { label: "Island", value: "Island", color: "hsl(169, 95%, 90%)"}
      - { label: "Unknown", value: "Unknown", color: "hsl(347, 95%, 90%)"}
      - { label: "Underworld", value: "Underworld", color: "hsl(234, 95%, 90%)"}
      - { label: "Empire", value: "Empire", color: "hsl(221, 95%, 90%)"}
      - { label: "Hideout", value: "Hideout", color: "hsl(306, 95%, 90%)"}
      - { label: "Outpost", value: "Outpost", color: "hsl(298, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      footer_formula: 
  PartOf:
    input: relation
    accessorKey: PartOf
    key: PartOf
    id: PartOf
    label: PartOf
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 164
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
      relation_color: hsl(0,0%,37%)
  Name:
    input: text
    accessorKey: Name
    key: Name
    id: newColumn3
    label: Name
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: 0
    width: 195
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
      footer_formula: 
  Govt:
    input: select
    accessorKey: Govt
    key: Govt
    id: Govt.
    label: Govt.
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "N/A", value: "N/A", color: "hsl(113, 95%, 90%)"}
      - { label: "Mayor-Council", value: "Mayor-Council", color: "hsl(6, 95%, 90%)"}
      - { label: "Kingdom", value: "Kingdom", color: "hsl(20, 95%, 90%)"}
      - { label: "Contested", value: "Contested", color: "hsl(51, 95%, 90%)"}
      - { label: "Garrison", value: "Garrison", color: "hsl(88, 95%, 90%)"}
      - { label: "Tribal", value: "Tribal", color: "hsl(224, 95%, 90%)"}
      - { label: "Vassal-Kingdom", value: "Vassal-Kingdom", color: "hsl(179, 95%, 90%)"}
      - { label: "Unknown", value: "Unknown", color: "hsl(330, 95%, 90%)"}
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
  Summary:
    input: text
    accessorKey: Summary
    key: Summary
    id: newColumn5
    label: Summary
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 100
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
  source_data: query
  source_form_result: "FROM \"3. Locations\""
  source_destination_path: 3. Locations
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
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```