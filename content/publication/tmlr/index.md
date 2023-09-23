---
title: "Beyond Information Gain: An Empirical Benchmark for Low-Switching-Cost Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Shusheng Xu
- Yancheng Liang
- admin
- Simon S. Du
- Yi Wu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Transactions on Machine Learning Research*
publication_short: In *TMLR*

abstract: "A ubiquitous requirement in many practical reinforcement learning (RL) applications is that the deployed policy that actually interacts with the environment cannot change frequently. Such an RL setting is called low-switching-cost RL, i.e., achieving the highest reward while reducing the number of policy switches during training. It has been a recent trend in theoretical RL research to develop provably efficient RL algorithms with low switching cost. The core idea in these theoretical works is to measure the information gain and switch the policy when the information gain is doubled. Despite of the theoretical advances, none of existing approaches have been validated empirically. We conduct the first empirical evaluation of different policy switching criteria on popular RL testbeds, including a medical treatment environment, the Atari games, and robotic control tasks. Surprisingly, although information-gain-based methods do recover the optimal rewards, they often lead to a substantially higher switching cost. By contrast, we find that a feature-based criterion, which has been largely ignored in the theoretical research, consistently produces the best performances over all the domains. We hope our benchmark could bring insights to the community and inspire future research. Our code and complete results can be found at https://sites.google.com/view/low-switching-cost-rl."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/tmlr/beyond_information_gain.pdf'
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
