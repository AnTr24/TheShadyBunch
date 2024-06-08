---

database-plugin: basic

---

```yaml:dbfolder
name: Orgs-DB
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
    sortIndex: 1
    width: -164
    isSorted: true
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
  Name:
    input: text
    accessorKey: Name
    key: Name
    id: Name
    label: Name
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 204
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  parent:
    input: relation
    accessorKey: parent
    key: parent
    id: newColumn5
    label: Part Of
    position: 3
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
      related_note_path: 4. NPCs & Organizations/Organizations/Add New Organization.md
      relation_color: hsl(0,43%,51%)
      content_alignment: text-align-left
      wrap_content: true
  AssociatedGroup:
    input: relation
    accessorKey: AssociatedGroup
    key: AssociatedGroup
    id: AssociatedGroup
    label: Members
    position: 4
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
      related_note_path: 4. NPCs & Organizations/NPCs/Add New NPC.md
      bidirectional_relation: true
      relation_color: hsl(209,96%,18%)
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
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
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