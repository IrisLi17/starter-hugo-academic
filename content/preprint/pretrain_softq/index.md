---
title: "Pretrain soft q-learning with imperfect demonstrations"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xiaoqin Zhang
- admin
- Huimin Ma
- Xiong Luo

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-05"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *International Conference on Intelligent Robots and Systems*
# publication_short: In *IROS*

abstract: "Pretraining reinforcement learning methods with demonstrations has been an important concept in the study of reinforcement learning since a large amount of computing power is spent on online simulations with existing reinforcement learning algorithms. Pretraining reinforcement learning remains a significant challenge in exploiting expert demonstrations whilst keeping exploration potentials, especially for value based methods. In this paper, we propose a pretraining method for soft Q-learning. Our work is inspired by pretraining methods for actor-critic algorithms since soft Q-learning is a value based algorithm that is equivalent to policy gradient. The proposed method is based on γ-discounted biased policy evaluation with entropy regularization, which is also the updating target of soft Q-learning. Our method is evaluated on various tasks from Atari 2600. Experiments show that our method effectively learns from imperfect demonstrations, and outperforms other state-of-the-art methods that learn from expert demonstrations."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'preprint/pretrain_softq/paper.pdf'
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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
