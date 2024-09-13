---
title: Research and Development
date: 2022-10-24
show_breadcrumb: true

tags: ["projects-en"]

type: landing

sections:
  - block: markdown
    content:
      title: Research and Development
      text: <p>The Research and Development (R&D) division collaborates with large companies and organizations to research and develop ideas. Established in 2013, the Smart Sense Lab has made significant contributions to video analysis, computer forensics, and biometrics, exploring various artificial intelligence techniques. With over 8 million reais in funding from R&D projects in partnership with companies and research agencies in Brazil, the lab has published numerous projects and scientific articles. These projects enhance the integration between academic research and industrial demands, translating research findings into innovative Artificial Intelligence solutions. We develop solutions covering data capture, predictive model training and validation, including facial identification and verification, people and object detection, activity recognition, license plate recognition, and active camera control. Leveraging established techniques and scientific research, we also offer customized solutions tailored to specific requirements.

  - block: portfolio
    id: projects
    content:
      #subtitle:
      #text:
      filters:
        # Folders to display content from
        folders:
        # Only show content with these tags
        tags: ["R&D-en"]
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
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view:
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---