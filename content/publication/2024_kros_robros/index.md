---
title: 'Transformer based Collision Detection Approach by Torque Estimation using Joint Information'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Daegyu Lim
  - Sumin Park
  - Hyeonjun Park

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-08-31T00:00:00Z'
doi: '10.7746/jkros.2024.19.3.266'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-31T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "The Journal of Korea Robotics Society, Vol.19, No.3, pp. 266 - 273 (8 pages)"
publication_short: The Journal of Korea Robotics Society, Vol.19, No.3

abstract: |-
 With the rising interaction between robots and humans, detecting collisions has become increasingly vital for ensuring safety. In this paper, we propose a novel approach for detecting collisions without using force torque sensors or tactile sensors, utilizing a Transformer-based neural network architecture. The proposed collision detection approach comprises a torque estimator network that predicts the joint torque in a free-motion state using Synchronous time-step encoding, and a collision discriminator network that predicts collisions by leveraging the difference between estimated and actual torques. The collision discriminator finally creates a binary tensor that predicts collisions frame by frame. In simulations, the proposed network exhibited enhanced collision detection performance relative to the other kinds of networks both in terms of prediction speed and accuracy. This underscores the benefits of using Transformer networks for collision detection tasks, where rapid decision-making is essential.
 
# Summary. An optional shortened abstract.
summary: The paper introduces A2XP, a novel approach for domain generalization, which optimizes prompts for each source domain and combines them for robust performance across domains, while also preserving privacy and integrity of the network architecture. Experimental results demonstrate its state-of-the-art performance in computer vision tasks and its potential for broader applications.

tags: 
- Artificial Intelligence
- Deep Learning
- Transformer
- Collision Detection
- Torque Controller

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)

url_pdf: 'https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11909393'
url_code: 'https://github.com/zzziito/Mujoco_RobotArm'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: 'https://airlabkhu.github.io/A2XP/static/pdfs/A2XP_poster.pdf#view=fit'
# url_project: 'https://airlabkhu.github.io/A2XP/'
# url_slides: 'https://airlabkhu.github.io/A2XP/static/pdfs/A2XP_slides.pdf#view=fit'
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)' 
  focal_point: ''
  preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
#   - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

