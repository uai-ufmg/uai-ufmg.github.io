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
      sort_by: 'Date'
      sort_ascending: false
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Geographic and Geological Data Science
          tag: Deep Learning
        - name: Computer Vision
          tag: Computer Vision
        - name: Medical Imaging
          tag: Medical Imaging
        - name: Music Machine Learning
          tag: Music
        - name: Sports Analytics
          tag: Sports
        - name: Uncertainty in AI
          tag: AI
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view:
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---