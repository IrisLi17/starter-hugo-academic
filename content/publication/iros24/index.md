---
title: "Robot Generating Data for Learning Generalizable Visual Robotic Manipulation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin 
- Ying Yuan
- Jingzhi Cui
- Haoran Huan
- Wei Fu
- Jiaxuan Gao
- Zekai Xu
- Yi Wu

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2024-10"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE/RSJ International Conference on Intelligent Robots and Systems*
publication_short: In *IROS*

abstract: "It has been a popular trend in AI to pretrain foundation models on massive data. However, collecting sufficient offline training trajectories for robot learning is particularly expensive since valid control actions are required. Therefore, most existing robotic datasets are collected from human experts. We tackle such a data collection issue with a new framework called “robot self-teaching”, which asks the robot to self-generate effective training data instead of relying on human demonstrators. Our key idea is to train a separate data-generation policy operating on the state space to automatically generate meaningful actions and trajectories with ever-growing complexities. Then, these generated data can be further used to train a visual policy with strong compositional generalization capabilities. We validate our framework in two visual manipulation testbeds, including a multi-object stacking domain and a popular RL benchmark “Franka kitchen”. Experiments show that the final visual policy trained on self-generated data can accomplish novel testing goals that require long-horizon robot executions. Project website https://sites.google.com/view/robot-self-teaching."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/iros24/rst.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://sites.google.com/view/robot-self-teaching'
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
