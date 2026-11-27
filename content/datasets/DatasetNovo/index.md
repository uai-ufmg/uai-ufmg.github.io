---
title: 'Parihaka Channels'
show_breadcrumb: true

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2026-11-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
#publication: In *Wowchemy Conference*
#publication_short: In *ICW*

abstract: 'Parihaka-Channels is the first publicly available dataset of manual paleochannel annotations on real seismic data. It is built on the open-access Parihaka-3D survey (590 inlines × 782 crosslines × 1006 time samples) from the offshore Taranaki Basin, New Zealand, which is rich in channel systems but until now had only facies labels.'

# Summary. An optional shortened abstract.
summary: 'Parihaka-Channels is the first publicly available dataset of manual paleochannel annotations on real seismic data. It is built on the open-access Parihaka-3D survey (590 inlines × 782 crosslines × 1006 time samples) from the offshore Taranaki Basin, New Zealand, which is rich in channel systems but until now had only facies labels.'

tags: []

# Display this page in the Featured widget?
featured: true

url_pdf: ''
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://drive.google.com/drive/folders/1Wws9HiHtA6YjuuckJIRZ86uEnq9paCvc'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
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

Parihaka-Channels is the first publicly available dataset of manual paleochannel annotations on real seismic data. It is built on the open-access Parihaka-3D survey (590 inlines × 782 crosslines × 1006 time samples) from the offshore Taranaki Basin, New Zealand, which is rich in channel systems but until now had only facies labels. The annotations were made on 601 horizon slices taken from a Relative Geological Time (RGT) volume, so channels keep their lateral continuity along depositional surfaces instead of being cut apart by inlines, crosslines or timeslices. While labeling, the annotator could overlay the seismic amplitude with an STFT-based spectral decomposition, split into low, mid and high frequency bands, which made thin channel boundaries easier to outline. For evaluation, the volume is split in half along the crosslines into two independent 590 × 391 × 1006 subvolumes for training and testing. Slice sets are provided for all four orientations, in both amplitude and spectral form.
