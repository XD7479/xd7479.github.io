---
title: "CamFreeDiff: Camera-free Image to Panorama Generation with Diffusion Model"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Shitao Tang
- Kejie Li
- Peng Wang

# Author notes (optional)
author_notes: []


date: "2025"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *CVPR* 2025
publication_short: In *CVPR* 2025

abstract: "This paper introduces Camera-free Diffusion (CamFreeDiff) model for 360∘ image outpainting from a single camera-free image and text description. 
This method distinguishes itself from existing strategies, such as MVDiffusion, by eliminating the requirement for predefined camera poses. 
CamFreeDiff seamlessly incorporates a mechanism for predicting homography within the multi-view diffusion framework. 
The key component of our approach is to formulate camera estimation by directly predicting the homography transformation from the input view to the predefined canonical view. 
In contrast to the direct two-stage approach of image transformation and outpainting, CamFreeDiff utilizes predicted homography to establish point-level correspondences between the input view and the target panoramic view. 
This enables consistency through correspondence-aware attention, which is learned in a fully differentiable manner. 
Qualitative and quantitative experimental results demonstrate the strong robustness and performance of CamFreeDiff for 360∘ image outpainting in the challenging context of camera-free inputs."

# Summary. An optional shortened abstract.
Summary: "Xiaoding Yuan, Shitao Tang, Kejie Li, Peng Wang"

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
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
  preview_only: False

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
