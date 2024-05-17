---
title: Projects
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title: Projects
      text: >
        <p>Explore the innovative projects that are contributing to future of technology. From practical solutions to visionary concepts, each project reflects our laboratory's commitment to technical excellence and the relentless pursuit of significant advances. In our laboratory, excellence is measured by projects that challenge the boundaries of what is possible. Each initiative reflects not only the advanced application of artificial intelligence and other contemporary technology topics, but also an unwavering commitment to solving complex problems.

  - block: portfolio
    id: projects
    content:
      title:
      #subtitle:
      #text:
      filters:
        # Folders to display content from
        folders:
        # Only show content with these tags
        tags: ["projects"]
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
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---