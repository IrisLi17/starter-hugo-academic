---
title: "Efficient Bimanual Handover and Rearrangement via Symmetry-Aware Actor-Critic Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Chaoyi Pan
- Huazhe Xu
- Xiaolong Wang
- Yi Wu

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2023-05"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Robotics and Automation*
publication_short: In *ICRA*

abstract: "Bimanual manipulation is important for building intelligent robots that unlock richer skills than single arms. We consider a multi-object bimanual rearrangement task, where a reinforcement learning (RL) agent aims to jointly control two arms to rearrange these objects as fast as possible. Solving this task efficiently is challenging for an RL agent due to the requirement of discovering precise intra-arm coordination in exponentially large control space. We develop a symmetry-aware actor-critic framework that leverages the interchangeable roles of the two manipulators in the bimanual control setting to reduce the policy search space. To handle the compositionality over multiple objects, we augment training data with an object-centric relabeling technique. The overall approach produces an RL policy that can rearrange up to 8 objects with a success rate of over 70% in simulation. We deploy the policy to two Franka Panda arms and further show a successful demo on human-robot collaboration. Videos can be found at https://sites.google.com/view/bimanual."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/icra23_bimanual/bimanual_handover.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://sites.google.com/view/bimanual'
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
