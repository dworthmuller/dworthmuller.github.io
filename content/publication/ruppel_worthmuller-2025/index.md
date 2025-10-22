---
title: napariTFM- An Open-Source Tool for Traction Force Microscopy and Monolayer Stress Microscopy

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Artur Ruppel
- Dennis Wörthmüller
- Martial Balland
- Francois Fagotto


# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-10-20'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-10-22T14:23:54.333698Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- manuscript

# Publication name and optional abbreviated publication name.
publication: '*bioRxiv*'
publication_short: ''

doi: 10.1101/2025.10.14.682385

abstract: Cellular force generation and transmission are fundamental processes driving cell migration, division, tissue morphogenesis, and disease progression. Traction Force Microscopy (TFM) and Monolayer Stress Microscopy (MSM) have emerged as essential techniques for quantifying these mechanical processes, but current software solutions are fragmented across multiple platforms with varying degrees of usability and accessibility. Here, we present napariTFM, a comprehensive open-source plugin for the napari image viewer that integrates state-of-the-art algorithms for both TFM and MSM analysis within an intuitive graphical user interface. The software implements TV-L1 optical flow for displacement analysis, Fourier Transform Traction Cytometry (FTTC) for force reconstruction, and finite element methods for stress calculation, supporting both single-frame and time-series analysis of 2D microscopy data. Systematic validation using synthetic datasets with known ground truth values demonstrated excellent accuracy, with correlation coefficients above 0.9 for most situations. Real-time parameter adjustment and immediate visualization capabilities enable interactive optimization of analysis parameters and quality assessment during processing. Finally, we demonstrate the software's capabilities through analysis of optogenetic contractility experiments in cell doublets. napariTFM addresses critical gaps in the cellular mechanics software ecosystem by combining algorithmic rigor with practical usability, providing the research community with an accessible platform for quantitative studies of cellular force generation and transmission.


# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://www.biorxiv.org/content/10.1101/2025.10.14.682385v2.abstract
---

