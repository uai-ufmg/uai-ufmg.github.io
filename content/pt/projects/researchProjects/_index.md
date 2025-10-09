---
title: "Projetos de pesquisa"
show_breadcrumb: true
type: landing

tags: ["projects-pt"]

sections:
  - block: portfolio3
    id: projects
    content:
      title: Projetos de pesquisa
      filters:
        folders:
        tags: ["RP-pt"]
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
        - name: Processamento de dados de sensores
          tag: SDP
        - name: Vigilância Visual
          tag: VS
        - name: Biometria
          tag: Bio
        - name: Visão Computacional
          tag: CV
        - name: GIS
          tag:
        - name: Aprendizado de máquina musical
          tag:
        - name: Artigos
          tag: artigos
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

---
