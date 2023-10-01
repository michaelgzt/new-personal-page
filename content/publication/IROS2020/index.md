---
title: 'Reinforcement co-Learning of Deep and Spiking Neural Networks for Energy-Efficient Mapless Navigation with Neuromorphic Hardware'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Neelesh Kumar
  - Konstantinos Michmizos

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-10-24T00:00:00Z'
doi: 'https://doi.org/10.1109/IROS45743.2020.9340948'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*
publication_short: In *IROS 2020*

abstract: Energy-efficient mapless navigation is crucial for mobile robots as they explore unknown environments with limited on-board resources. Although the recent deep rein-forcement learning (DRL) approaches have been successfully applied to navigation, their high energy consumption limits their use in several robotic applications. Here, we propose a neuromorphic approach that combines the energy-efficiency of spiking neural networks with the optimality of DRL and benchmark it in learning control policies for mapless navigation. Our hybrid framework, spiking deep deterministic policy gradient (SDDPG), consists of a spiking actor network (SAN) and a deep critic network, where the two networks were trained jointly using gradient descent. The co-learning enabled synergistic information exchange between the two networks, allowing them to overcome each other's limitations through a shared representation learning. To evaluate our approach, we deployed the trained SAN on Intel's Loihi neuromorphic processor. When validated on simulated and real-world complex environments, our method on Loihi consumed 75 times less energy per inference as compared to DDPG on Jetson TX2, and also exhibited a higher rate of successful navigation to the goal, which ranged from 1% to 4.2% and depended on the forward-propagation timestep size. These results reinforce our ongoing efforts to design brain-inspired algorithms for controlling autonomous robots with neuromorphic hardware.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2003.01157.pdf'
url_code: 'https://github.com/combra-lab/spiking-ddpg-mapless-navigation'
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
