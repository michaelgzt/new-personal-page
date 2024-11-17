---
title: Talk at ICONS2024

event: International Conference on Neuromorphic Systems 2024 (ICONS2024)
event_url: https://iconsneuromorphic.cc/

location: George Mason University
address:
 # street: 
  city: Arlington, Virginia
 # postcode: 
  country: United States

summary: I gave a talk on our neuromorphic hard attention framework TRIP for efficient event-based vision at ICONS 2024.
abstract: 'Neuromorphic processors are well-suited for efficiently handling sparse events from event-based cameras. However, they face significant challenges in the growth of computing demand and hardware costs as the input resolution increases. This paper proposes the Trainable Region-of-Interest Prediction (TRIP), the first hardware-efficient hard attention framework for event-based vision processing on a neuromorphic processor. Our TRIP framework actively produces low-resolution Region-of-Interest (ROIs) for efficient and accurate classification. The framework exploits sparse events' inherent low information density to reduce the overhead of ROI prediction. We introduced extensive hardware-aware optimizations for TRIP and implemented the hardware-optimized algorithm on the SENECA neuromorphic processor. We utilized multiple event-based classification datasets for evaluation. Our approach achieves state-of-the-art accuracies in all datasets and produces reasonable ROIs with varying locations and sizes. On the DvsGesture dataset, our solution requires 46x less computation than the state-of-the-art while achieving higher accuracy. Furthermore, TRIP enables more than 2x latency and energy improvements on the SENECA neuromorphic processor compared to the conventional solution.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-07-30T8:00:00Z'
date_end: '2024-08-0200T17:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: 'uploads/icons2024.pdf'
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
