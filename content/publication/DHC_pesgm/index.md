---
title: "Learn Dynamic Hosting Capacity Based on Voltage Sensitivity Analysis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jingyi Yuan
- Yang Weng
- Raja Ayyanar

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-09-25"
doi: "10.1109/PESGM52003.2023.10252543"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In 2023 IEEE Power & Energy Society General Meeting (PESGM)
# publication_short: In *ICW*

abstract: The extensive use of distributed energy sources (DERs) presents the substantial design, planning, and operational issues for distribution systems, thus prompting the broad adaption of methodologies for photovoltaics (PV) hosting capacity analysis (HCA). Traditional HCA methods require running power flow analysis iteratively, typically in the time-series scenario, to consider the dynamic pattern. However, the time-consuming HCA techniques fail to offer online prediction in large distribution networks because of the computational burden. To tackle the computation challenge, we first provide a deep learning-based problem formulation for HCA, which performs offline training and calculates hosting capacity in real time. The applicable learning model, long short-term memory (LSTM), uses historical time-series data to identify the underlying periodic patterns in distribution systems. However, the accuracy of HC estimation is low in the LSTM without considering system spatial information correlated with HC. To capture such spatial correlation from system measurements, we design dual forget gates in the LSTM and propose a novel Spatial-Temporal LSTM. Moreover, as voltage violations are observed to be one of the most critical constraints of HCA, we construct a voltage sensitivity gate to increase the weight on voltage variation and reduce the mismatch in HC determination. The simulation results on different feeders, such as IEEE 123-bus and utility feeders, validate our designs.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
# featured: true

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
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
