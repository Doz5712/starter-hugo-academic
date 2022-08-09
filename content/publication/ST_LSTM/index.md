---
title: "Spatial-Temporal Deep Learning for Hosting Capacity Analysis in Distribution Grids"

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

date: "2022-08-08"
doi: "10.1109/TSG.2022.3196943"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In IEEE Transactions on Smart Grid
# publication_short: In *ICW*

abstract: The widespread use of distributed energy sources (DERs) raises significant challenges for power system design, planning, and operation, leading to wide adaptation of tools on hosting capacity analysis (HCA). Traditional HCA methods conduct extensive power flow analysis. Due to the computation burden, these time-consuming methods fail to provide online hosting capacity (HC) in large distribution systems. To solve the problem, we first propose a deep learning-based problem formulation for HCA, which conducts offline training and determines HC in real time. The used learning model, long short-term memory (LSTM), implements historical time-series data to capture periodical patterns in distribution systems. However, directly applying LSTMs suffers from low accuracy due to the lack of consideration on spatial information, where location information like feeder topology is critical in nodal HCA. Therefore, we modify the forget gate function to dual forget gates, to capture the spatial correlation within the grid. Such a design turns the LSTM into the Spatial-Temporal LSTM (ST-LSTM). Moreover, as voltage violations are the most vital constraints in HCA, we design a voltage sensitivity gate to increase accuracy further. The results of LSTMs and ST-LSTMs on feeders, such as IEEE 34-, 123-bus feeders, and utility feeders, validate our designs.

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

