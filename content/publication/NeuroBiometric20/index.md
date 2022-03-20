---
title: "NeuroBiometric: An eye blink based biometric authentication system using an event-based neuromorphic vision sensor"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Guang Chen
- Fa Wang
- admin
- Zhijun Li
- Zichen Liang
- Alois Knoll

# Author notes (optional)
author_notes: []


date: "2020"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/CAA Journal of Automatica Sinica*
<!-- publication_short: In *IEEE/CAA JAS* -->

abstract: The rise of the Internet and identity authentication systems has brought convenience to people’s lives but has also introduced the potential risk of privacy leaks. Existing biometric authentication systems based on explicit and static features bear the risk of being attacked by mimicked data. This work proposes a highly efficient biometric authentication system based on transient eye blink signals that are precisely captured by a neuromorphic vision sensor with microsecond-level temporal resolution. The neuromorphic vision sensor only transmits the local pixel-level changes induced by the eye blinks when they occur, which leads to advantageous characteristics such as an ultra-low latency response. We first propose a set of effective biometric features describing the motion, speed, energy and frequency signal of eye blinks based on the microsecond temporal resolution of event densities. We then train the ensemble model and non-ensemble model with our NeuroBiometric dataset for biometrics authentication. The experiments show that our system is able to identify and verify the subjects with the ensemble model at an accuracy of 0.948 and with the non-ensemble model at an accuracy of 0.925. The low false positive rates (about 0.002) and the highly dynamic features are not only hard to reproduce but also avoid recording visible characteristics of a user’s appearance. The proposed system sheds light on a new path towards safer authentication using neuromorphic vision sensors.

# Summary. An optional shortened abstract.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9272708'
url_code: 'https://github.com/XD7479/NeuroBiometric'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: True

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
