---
title: "Training projects"
show_breadcrumb: true
type: landing

tags: ["projects-en"]

sections:
  - block: portfolio
    id: projects
    content:
      title: Training projects
      #subtitle:
      #text:
      filters:
        # Folders to display content from
        folders:
        # Only show content with these tags
        tags: ["training-en"]
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
          - section
          - term
          - taxonomy
          - home
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: true
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view:
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
---