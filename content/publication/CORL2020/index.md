---
title: 'Deep Reinforcement Learning with Population-Coded Spiking Neural Network for Continuous Control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Neelesh Kumar
  - Raymond Yoo
  - Konstantinos Michmizos

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-12-03T00:00:00Z'
doi: 'https://proceedings.mlr.press/v155/tang21a.html'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2020 Conference on Robot Learning (CoRL)*
publication_short: In *CoRL 2020*

abstract: The energy-efficient control of mobile robots has become crucial as the complexity of their real-world applications increasingly involves high-dimensional observation and action spaces, which cannot be offset by their limited on-board resources. An emerging non-Von Neumann model of intelligence, where spiking neural networks (SNNs) are executed on neuromorphic processors, is now considered as an energy-efficient and robust alternative to the state-of-the-art real-time robotic controllers for low dimensional control tasks. The challenge now for this new computing paradigm is to scale so that it can keep up with real-world applications. To do so, SNNs need to overcome the inherent limitations of their training, namely the limited ability of their spiking neurons to represent information and the lack of effective learning algorithms. Here, we propose a population-coded spiking actor network (PopSAN) that was trained in conjunction with a deep critic network using deep reinforcement learning (DRL). The population coding scheme, which is prevalent across brain networks, dramatically increased the representation capacity of the network and the hybrid learning combined the training advantages of deep networks with the energy-efficient inference of spiking networks. To show that our approach can be used for general-purpose spike-based reinforcement learning, we demonstrated its integration with a wide spectrum of policy-gradient based DRL methods covering both on-policy and off-policy DRL algorithms. We deployed the trained PopSAN on Intel’s Loihi neuromorphic chip and benchmarked our method against the mainstream DRL algorithms for continuous control. To allow for a fair comparison among all methods, we validated them on OpenAI gym tasks. Our Loihi-run PopSAN consumed 140 times less energy per inference when compared against the deep actor network on Jetson TX2, and achieved the same level of performance. Our results demonstrate the overall efficiency of neuromorphic controllers and suggest the hybrid reinforcement learning approach as an alternative to deep learning, when both energy-efficiency and robustness are important.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://proceedings.mlr.press/v155/tang21a/tang21a.pdf'
url_code: 'https://github.com/combra-lab/pop-spiking-deep-rl'
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
