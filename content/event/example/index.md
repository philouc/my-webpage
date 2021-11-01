---
title: "Accelerated brain MR Imaging: From shorter data acquisition to faster image reconstruction"

event: 2nd annual meeting of the French Ultra-high field Network (FUN)
event_url: https://www.francelifeimaging.fr/reseaux-connexes/fun/

location: CHU La Timone
address:
  street: 264 Rue Saint-Pierre
  city: Marseille Cedex 5
  region: 
  postcode: '13385'
  country: France

summary: I presented in this talk the recent progresses of my team related to SPARKLING for shorter scan times in MRI and XPDNet for improved image reconstruction using our deep neural nets.
abstract: "Magnetic Resonance Imaging is a widely used neuroimaging technique as it can probe brain tissues, their structure and provide insights on the functional organization as well as the layout of brain vessels. However, MRI relies on an inherently slow imaging process. 
Reducing acquisition time has been a major challenge in high-resolution MRI and has been successfully addressed by Compressed Sensing (CS) theory. Nevertheless, most of the Fourier encoding schemes under-sample existing k-space trajectories which does not adequately encode all the information necessary. Recently, my team has addressed this issue by proposing the Spreading Projection Algorithm for Rapid K-space sampLING (SPARKLING) for 2D/3D non-Cartesian T2* and susceptibility weighted imaging at 3 and 7Tesla (T). In the first half of my presentation, I will present these advancements, interesting clinical applications and how we have adapted this approach to address high-resolution functional MRI at 7T.
However, CS approaches suffer from a slow image reconstruction process. To counteract this delay and improve image quality, deep learning has been used since 2016. In the second half of this talk, I will expose our own deep-learning architecture, called XPDNet (Primal Dual Network where X plays the role of a magic card), that has been ranked second in the 2020 brain fastMRI challenge (1.5 and 3T data).  I will illustrate XPDNet’s transfer learning capacity on 7T NeuroSpin T2 images. Lastly, I will share how we have further improved this approach to handle 3D non-Cartesian imaging settings associated with the SPARKLING encoding scheme."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-10-21T08:40:00Z"
date_end: "2021-10-21T17:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2021-11-01T08:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Philippe Ciuciu
  url: https://twitter.com/Philippe_Ciuciu
url_code: ""
url_pdf: "static/upload/21.10_ciuciu_marseille.pdf"
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}
