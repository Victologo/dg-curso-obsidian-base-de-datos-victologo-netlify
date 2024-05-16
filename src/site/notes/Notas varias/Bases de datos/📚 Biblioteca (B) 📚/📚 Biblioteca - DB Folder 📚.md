---
{"dg-publish":true,"permalink":"/notas-varias/bases-de-datos/biblioteca-b/biblioteca-db-folder/"}
---


```yaml:dbfolder
name: new database
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
    isHidden: false
    sortIndex: -1
    position: 2
    width: 351
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      content_alignment: text-align-center
      wrap_content: false
  coverUrl:
    input: text
    accessorKey: coverUrl
    key: coverUrl
    label: coverUrl
    position: 1
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 176
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      content_vertical_alignment: align-middle
      content_alignment: text-align-center
  Asignatura:
    input: text
    accessorKey: Asignatura
    key: Asignatura
    label: Asignatura
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 261
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      content_alignment: text-align-center
  PDF:
    input: text
    accessorKey: PDF
    key: PDF
    label: PDF
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: 1
    width: 175
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
      persist_formula: false
      content_alignment: text-align-center
config:
  remove_field_when_delete_column: true
  cell_size: compact
  sticky_first_column: false
  group_folder_column: 
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  source_data: current_folder
  source_form_result: root
  source_destination_path: /
  frontmatter_quote_wrap: false
  row_templates_folder: /
  current_row_template: 
  pagination_size: 10
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: top
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  enable_js_formulas: false
  enable_footer: false
  font_size: 16
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  implementation: default
  show_metadata_tags: false
filters:
  enabled: false
  conditions:
      - field: annotation-target
        operator: CONTAINS
        value: ""
        type: text
      - field: Etiquetas
        operator: CONTAINS
        value: ""
        type: text
      - field: annotation-target
        operator: CONTAINS
        value: ""
        type: text
      - field: annotation-target
        operator: CONTAINS
        value: ""
        type: text
```