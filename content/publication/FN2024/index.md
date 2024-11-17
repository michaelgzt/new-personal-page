---
title: 'Optimizing event-based neural networks on digital neuromorphic architecture: a comprehensive design space exploration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yingfu Xu
  - Kevin Shidqi
  - Gert-Jan van Schaik
  - Refik Bilgic
  - Alexandra Dobrita
  - Shenqi Wang
  - Roy Meijer
  - Prithvish Nembhani
  - Cina Arjmand
  - Pietro Martinello
  - Anteneh Gebregiorgis
  - Said Hamdioui
  - Paul Detterer
  - Stefano Traferro
  - Mario Konijnenburg
  - Kanishkan Vadivel
  - Manolis Sifalakis
  - admin
  - Amirreza Yousefzadeh

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-03-28T00:00:00Z'
doi: 'https://doi.org/10.3389/fnins.2024.1335422'

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

abstract: Neuromorphic processors promise low-latency and energy-efficient processing by adopting novel brain-inspired design methodologies. Yet, current neuromorphic solutions still struggle to rival conventional deep learning accelerators' performance and area efficiency in practical applications. Event-driven data-flow processing and near/in-memory computing are the two dominant design trends of neuromorphic processors. However, there remain challenges in reducing the overhead of event-driven processing and increasing the mapping efficiency of near/in-memory computing, which directly impacts the performance and area efficiency. In this work, we discuss these challenges and present our exploration of optimizing event-based neural network inference on SENECA, a scalable and flexible neuromorphic architecture. To address the overhead of event-driven processing, we perform comprehensive design space exploration and propose spike-grouping to reduce the total energy and latency. Furthermore, we introduce the event-driven depth-first convolution to increase area efficiency and latency in convolutional neural networks (CNNs) on the neuromorphic processor. We benchmarked our optimized solution on keyword spotting, sensor fusion, digit recognition and high resolution object detection tasks. Compared with other state-of-the-art large-scale neuromorphic processors, our proposed optimizations result in a 6× to 300× improvement in energy efficiency, a 3× to 15× improvement in latency, and a 3× to 100× improvement in area efficiency. Our optimizations for event-based neural networks can be potentially generalized to a wide range of event-based neuromorphic processors.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2024.1335422/full'
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
