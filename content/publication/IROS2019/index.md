---
title: 'Spiking neural network on neuromorphic hardware for energy-efficient unidimensional SLAM'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Arpit Shah
  - Konstantinos Michmizos

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-11-03T00:00:00Z'
doi: 'https://doi.org/10.1109/IROS40897.2019.8967864'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*
publication_short: In *IROS 2019*

abstract: Energy-efficient simultaneous localization and mapping (SLAM) is crucial for mobile robots exploring unknown environments. The mammalian brain solves SLAM via a network of specialized neurons, exhibiting asynchronous computations and event-based communications, with very low energy consumption. We propose a brain-inspired spiking neural network (SNN) architecture that solves the unidimensional SLAM by introducing spike-based reference frame transformation, visual likelihood computation, and Bayesian inference. We integrated our neuromorphic algorithm to Intel's Loihi neuromorphic processor, a non-Von Neumann hardware that mimics the brain's computing paradigms. We performed comparative analyses for accuracy and energy-efficiency between our neuromorphic approach and the GMapping algorithm, which is widely used in small environments. Our Loihi-based SNN architecture consumes 100 times less energy than GMapping run on a CPU while having comparable accuracy in head direction localization and map-generation. These results pave the way for scaling our approach towards active-SLAM alternative solutions for Loihi-controlled autonomous robots.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1903.02504.pdf'
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
# ---

# {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
