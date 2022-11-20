---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Efficient Storage and Importance Sampling for Fluorescent Reflectance
subtitle: ''
summary: 'Computer Graphics Forum'
authors:
- Qingqin Hua
- Vojtěch Tázlar
- Alban Fichet
- Alexander Wilkie
doi: 10.1111/cgf.14716
publication: "*Computer Graphics Forum*"
tags: []
categories: []
date: '2022-11-10'
lastmod: 2022-11-20T22:13:59+01:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-11-20T21:13:52.494590Z'
publication_types:
- '2'
abstract: 'We propose a technique for efficient storage and importance sampling of fluorescent spectral data. Fluorescence is fully described by a re-radiation matrix, which for a given input wavelength indicates how much energy is re-emitted at other wavelengths.However, such representation has a considerable memory footprint. To significantly reduce memory requirements, we proposethe use of Gaussian mixture models for the representation of re-radiation matrices. Instead of the full-resolution matrix, wework with a set of Gaussian parameters that also allow direct importance sampling. Furthermore, if accuracy is of concern,a re-radiation matrix can be used jointly with efficient importance sampling provided by the Gaussian mixture. In this paper,we present our pipeline for efficient storage of bispectral data and provide its extensive evaluation on a large set of bispectralmeasurements. We show that our method is robust and colour accurate even with its comparably minor memory requirementsand that it can be seamlessly integrated into a standard Monte Carlo path tracer.'
publication: '*Computer Graphics Forum*'

---
