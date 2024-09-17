---
title: 'Outdoor visual SLAM and Path Planning for Mobile-Robot'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Seongil Heo
  - Jueun Mun
  - Jiwoong Choi
  - admin
  - Eric T Matson

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-12-01T00:00:00Z'
doi: '10.1109'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In IEEE International Conference on Robotic Computing 2022
publication_short: In IEEE IRC 2022 CHARMS workshop

abstract: |-
 This paper proposes a robust visual SLAM and a path planning algorithm for autonomous vehicles in the outdoor environment. The consideration of the outdoor characteristics was essential in both SLAM and path planning processes. This study can be used when it is necessary to know the exact appearance of the environment due to the impossibility of observing the environment through a satellite map, e.g., inside a forest. The visual SLAM system was developed using GPS data in consideration of the deterioration of camera recognition performance outdoors. The GPS data was inserted into every multi-thread of visual SLAM, which are Camera Tracking, Local Mapping, and Loop Closing. It enhanced the accuracy of the map and saved computational power by preventing useless calculations. In the path planning part, our method divided the path based on the stability of the roads. When determining the optimal path, the stability of the road and the driving time were considered, and the weight was assigned based on the GPS data.
 
# Summary. An optional shortened abstract.
summary: The paper introduces A2XP, a novel approach for domain generalization, which optimizes prompts for each source domain and combines them for robust performance across domains, while also preserving privacy and integrity of the network architecture. Experimental results demonstrate its state-of-the-art performance in computer vision tasks and its potential for broader applications.

tags: 
- Visual SLAM
- GPS
- Outdoor Mobile Robot

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: arXiv
#   url: https://arxiv.org/abs/2311.10339

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10023601'
# url_code: 'https://github.com/AIRLABkhu/A2XP'
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


<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
