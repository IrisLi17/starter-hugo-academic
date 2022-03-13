---
title: "Learning to Design and Construct Bridge without Blueprint"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Tao Kong
- Lei Li
- Yifeng Li
- Yi Wu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-07"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Intelligent Robots and Systems*
publication_short: In *IROS*

abstract: "Autonomous assembly has been a desired functionality of many intelligent robot systems. We study a new challenging assembly task, designing and constructing a bridge without a blueprint. In this task, the robot needs to first design a feasible bridge architecture for arbitrarily wide cliffs and then manipulate the blocks reliably to construct a stable bridge according to the proposed design. In this paper, we propose a bi-level approach to tackle this task. At the high level, the system learns a bridge blueprint policy in a physical simulator using deep reinforcement learning and curriculum learning. A policy is represented as an attention-based neural network with object-centric input, which enables generalization to different numbers of blocks and cliff widths. For low-level control, we implement a motion-planning-based policy for real-robot motion control, which can be directly combined with a trained blueprint policy for real-world bridge construction without tuning. In our field study, our bi-level robot system demonstrates the capability of manipulating blocks to construct a diverse set of bridges with different architectures."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/iros21/paper.pdf'
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
