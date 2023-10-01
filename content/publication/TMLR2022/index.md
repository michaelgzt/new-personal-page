---
title: 'Decoding EEG With Spiking Neural Networks on Neuromorphic Hardware'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Neelesh Kumar
  - admin
  - Raymond Yoo
  - Konstantinos Michmizos

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-06-25T00:00:00Z'
doi: 'https://openreview.net/forum?id=ZPBJPGX3Bz'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Transactions on Machine Learning Research*
publication_short: In *TMLR*

abstract: Decoding motor activity accurately and reliably from electroencephalography (EEG) signals is essential for several portable brain-computer interface (BCI) applications ranging from neural prosthetics to the control of industrial and mobile robots. Spiking neural networks (SNNs) is an emerging brain-inspired architecture that is well-suited for decoding EEG signals due to their built-in ability to integrate information at multiple timescales, leading to energy-efficient solutions for portable BCI. In practice, however, current SNN solutions suffer from i) an inefficient spike encoding of the EEG signals; ii) non-specialized network architectures that cannot capture EEG priors of spatiotemporal dependencies; and iii) the limited generalizability of the local learning rules commonly used to train the networks. These untapped challenges result in a performance gap between the current SNN approaches and the state-of-the-art deep neural network (DNN) methods. Moreover, the black-box nature of most current SNN solutions masks their correspondence with the underlying neurophysiology, further hindering their reliability for real-world applications. Here, we propose an SNN architecture with an input encoding and network design that exploits the priors of spatial and temporal dependencies in the EEG signal. To extract spatiotemporal features, the network comprised of spatial convolutional, temporal convolutional, and recurrent layers. The network weights and the neuron membrane parameters were trained jointly using gradient descent and our method was validated in classifying movement on two datasets i) an in-house dataset comprising of complex components of movement, namely reaction time and directions, and ii) the publicly available eegmmidb dataset for motor imagery and movement. We deployed our SNN on Intel's Loihi neuromorphic processor, and show that our method consumed 95\% less energy per inference than the state-of-the-art DNN methods on NVIDIA Jeston TX2, while achieving similar levels of classification performance. Finally, we interpreted the SNN using a network perturbation study to identify the spectral bands and brain activity that correlated with the SNN outputs. The results were in agreement with the current neurophysiological knowledge implicating the activation patterns in the low-frequency oscillations over the motor cortex for hand movement and imagery tasks. Overall, our approach demonstrates the effectiveness of SNNs in accurately and reliably decoding EEG while availing the computational advantages offered by neuromorphic computing, and paves the way for employing neuromorphic methods in portable BCI systems.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=ZPBJPGX3Bz'
url_code: 'https://github.com/combra-lab/snn-eeg'
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
