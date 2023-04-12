---

database-plugin: basic

---

```yaml:dbfolder
name: Habit tracking database
description: To track my daily habits
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
    width: 163
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Reading:
    input: checkbox
    accessorKey: Reading
    key: Reading
    id: Reading
    label: Reading
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 30
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Spent:
    input: number
    accessorKey: Spent
    key: Spent
    id: $_Spent
    label: $ Spent
    position: 7
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
  Screen:
    input: number
    accessorKey: Screen
    key: Screen
    id: Screen_Time_(mins)
    label: Screen Time (mins)
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 114
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Water:
    input: number
    accessorKey: Water
    key: Water
    id: Glass_of_Water
    label: Glass of Water
    position: 100
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
  Workout:
    input: checkbox
    accessorKey: Workout
    key: Workout
    id: Workout_Routine
    label: Full Body Workout
    position: 3
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
  Entertainment:
    input: select
    accessorKey: Entertainment
    key: Entertainment
    id: Youtube/Show/Anime/TV
    label: Main Entertainment
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "TV", value: "TV", color: "hsl(47, 95%, 90%)"}
      - { label: "Youtube", value: "Youtube", color: "hsl(124, 95%, 90%)"}
      - { label: "Anime", value: "Anime", color: "hsl(75, 95%, 90%)"}
      - { label: "Music", value: "Music", color: "hsl(309, 95%, 90%)"}
      - { label: "GoingOut", value: "GoingOut", color: "hsl(217, 95%, 90%)"}
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
  Cardio:
    input: checkbox
    accessorKey: Cardio
    key: Cardio
    id: Cardio_(Walk_or_run_outside)
    label: Cardio
    position: 5
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
  Journal:
    input: checkbox
    accessorKey: Journal
    key: Journal
    id: Journal_throughout_the_day
    label: Journal
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
config:
  remove_field_when_delete_column: false
  cell_size: compact
  sticky_first_column: true
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
  row_templates_folder: assets/templates
  current_row_template: 
  pagination_size: 10
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