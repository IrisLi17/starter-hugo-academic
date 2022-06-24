---
title: "Phasic Self-Imitative Reduction for Sparse-Reward Goal-Conditioned Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Tian Gao
- Jiaqi Yang
- Huazhe Xu
- Yi Wu

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2022-05"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning*
publication_short: In *ICML*

abstract: "It has been a recent trend to leverage the power of supervised learning (SL) towards more effective reinforcement learning (RL) methods. We propose a novel phasic approach by alternating online RL and offline SL for tackling sparse-reward goal-conditioned problems. In the online phase, we perform RL training and collect rollout data while in the offline phase, we perform SL on those successful trajectories from the dataset. To further improve sample efficiency, we adopt additional techniques in the online phase including task reduction to generate more feasible trajectories and a value- difference-based intrinsic reward to alleviate the sparse-reward issue. We call this overall algorithm, PhA sic self-Imitative R eduction (PAIR). PAIR substantially outperforms both non-phasic RL and phasic SL baselines on sparse-reward goal-conditioned robotic control problems, including a challenging stacking task. PAIR is the first RL method that learns to stack 6 cubes with only 0/1 success rewards from scratch."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/icml22_pair/pair.pdf'
url_code: 'https://github.com/IrisLi17/onpolicy_algorithm'
url_dataset: ''
url_poster: ''
url_project: 'https://sites.google.com/view/pair-gcrl'
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

