---
title: 'SENECA: Building a fully digital neuromorphic processor, design trade-offs and challenges'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Kanishkan Vadivel
  - Yingfu Xu
  - Refik Bilgic
  - Kevin Shidqi
  - Paul Detterer
  - Stefano Traferro
  - Mario Konijnenburg
  - Manolis Sifalakis
  - Gert-Jan van Schaik
  - Amirreza Yousefzadeh

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-06-23T00:00:00Z'
doi: 'https://doi.org/10.3389%2Ffnins.2023.1187252'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Frontiers in Neuroscience*
publication_short: In *Front. Neurosci.*

abstract: Neuromorphic processors aim to emulate the biological principles of the brain to achieve high efficiency with low power consumption. However, the lack of flexibility in most neuromorphic architecture designs results in significant performance loss and inefficient memory usage when mapping various neural network algorithms. This paper proposes SENECA, a digital neuromorphic architecture that balances the trade-offs between flexibility and efficiency using a hierarchical-controlling system. A SENECA core contains two controllers, a flexible controller (RISC-V) and an optimized controller (Loop Buffer). This flexible computational pipeline allows for deploying efficient mapping for various neural networks, on-device learning, and pre-post processing algorithms. The hierarchical-controlling system introduced in SENECA makes it one of the most efficient neuromorphic processors, along with a higher level of programmability. This paper discusses the trade-offs in digital neuromorphic processor design, explains the SENECA architecture, and provides detailed experimental results when deploying various algorithms on the SENECA platform. The experimental results show that the proposed architecture improves energy and area efficiency and illustrates the effect of various trade-offs in algorithm design. A SENECA core consumes 0.47 mm2 when synthesized in the GF-22 nm technology node and consumes around 2.8 pJ per synaptic operation. SENECA architecture scales up by connecting many cores with a network-on-chip. The SENECA platform and the tools used in this project are freely available for academic research upon request.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.frontiersin.org/articles/10.3389/fnins.2023.1187252/full'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
