---
title: Pesquisa e Desenvolvimento
date: 2022-10-24
show_breadcrumb: true

tags: ["projects-pt"]

type: landing

sections:
  - block: markdown
    content:
      title: Pesquisa e Desenvolvimento
      text: <p>A divisão de Pesquisa e Desenvolvimento (P&D) colabora com grandes empresas e organizações para pesquisar e desenvolver ideias. Fundado em 2013, o Smart Sense Lab fez contribuições significativas para análise de vídeo, computação forense e biometria, explorando diversas técnicas de inteligência artificial. Com mais de 8 milhões de reais em financiamento de projetos de P&D em parceria com empresas e agências de pesquisa no Brasil, o laboratório já publicou inúmeros projetos e artigos científicos. Estes projetos melhoram a integração entre a investigação acadêmica e as exigências industriais, traduzindo os resultados da investigação em soluções inovadoras de Inteligência Artificial. Desenvolvemos soluções que abrangem captura de dados, treinamento e validação de modelos preditivos, incluindo identificação e verificação facial, detecção de pessoas e objetos, reconhecimento de atividades, reconhecimento de placas de veículos e controle ativo de câmeras. Aproveitando técnicas estabelecidas e pesquisas científicas, também oferecemos soluções personalizadas e adaptadas a requisitos específicos.

  - block: portfolio
    id: projects
    content:
      #subtitle:
      #text:
      filters:
        # Folders to display content from
        folders:
        # Only show content with these tags
        tags: ["R&D-pt"]
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