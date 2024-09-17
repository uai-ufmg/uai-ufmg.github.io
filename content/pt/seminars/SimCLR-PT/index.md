---
title: 'Desvendando o SimCLR: Aprendizado Autosupervisionado e Representações Visuais Contrastivas'

show_breadcrumb: true


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - henriqueMagalhaesPT

date: '2024-06-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

abstract: SimCLR (Simple Framework for Contrastive Learning of Visual Representations) é um algoritmo de rede neural que treina um modelo para identificar imagens similares sem utilizar rótulos pré-definidos de similaridade. Por isso, é chamado de autosupervisionado. O SimCLR cria uma representação latente para cada imagem e utiliza um aprendizado baseado no contraste entre uma imagem âncora e suas versões aumentadas. Nesta apresentação, vamos explorar os algoritmos autosupervisionados, com ênfase no método SimCLR. Discutiremos os componentes chave do SimCLR, incluindo a etapa de aumento de dados, o papel do codificador, e a cabeça de projeção. Além disso, explicaremos a teoria por trás do aprendizado contrastivo e como ele contribui para a criação de modelos de representação eficientes.

# Summary. An optional shortened abstract.
summary: Seminário apresentado por Henrique Magalhães sobre SimCLR (22/06/2024 às 14 horas).

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<p>SimCLR (Simple Framework for Contrastive Learning of Visual Representations) é um algoritmo de rede neural que treina um modelo para identificar imagens similares sem utilizar rótulos pré-definidos de similaridade. Por isso, é chamado de autosupervisionado. O SimCLR cria uma representação latente para cada imagem e utiliza um aprendizado baseado no contraste entre uma imagem âncora e suas versões aumentadas. Nesta apresentação, vamos explorar os algoritmos autosupervisionados, com ênfase no método SimCLR. Discutiremos os componentes chave do SimCLR, incluindo a etapa de aumento de dados, o papel do codificador, e a cabeça de projeção. Além disso, explicaremos a teoria por trás do aprendizado contrastivo e como ele contribui para a criação de modelos de representação eficientes.</p>