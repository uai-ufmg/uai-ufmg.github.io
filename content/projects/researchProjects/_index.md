---
title: "Research Projects"
show_breadcrumb: true
type: landing

tags: ["projects"]

sections:
  - block: portfolio3
    id: projects
    content:
      title: Research Projects
      filters:
        folders:
        tags: ["RP"]
        exclude_tags: []
        kinds:
          - page
          - section
          - term
          - taxonomy
          - home
      sort_by: 'Name'
      sort_ascending: true
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Sensor Data Processing
          tag: SDP
        - name: Visual Surveillance
          tag: VS
        - name: Biometrics
          tag: Bio
        - name: Computer Vision
          tag: CV
        - name: GIS
          tag:
        - name: Music Machine Learning
          tag:
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---