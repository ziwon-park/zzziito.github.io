---
title: 'BumpyPatch: Heightmap-based Outdoor Point Cloud Segmentation to Find Less Bumpy Road'

authors:
  - admin
  - Hyoseok Hwang

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-12-01T00:00:00Z'
doi: '10.1109/IRC59093.2023.00050'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Robotic Computing 2023
publication_short: IEEE IRC 2023

abstract: |-
 Autonomous mobile robots operate in a range of environments, from controlled indoor settings to unpredictable outdoor terrains. These varied conditions present challenges that require advanced navigation systems for their safe and efficient operation. A key component of this navigation is accurately assessing the ground texture. Any misjudgments can jeopardize both the robot's sensitive equipment and its carried cargo. In this research, we propose a novel method that uses heightmaps created by mapping the z -coordinates of 3D LiDAR-derived point cloud data to grayscale pixel values for evaluating outdoor ground textures. This approach effectively converts point cloud data, providing information to assist mobile robots in navigating less bumpy roads in outdoor settings. We present classification techniques for terrains based on the environment's nature: static, which pertains to individual point cloud files representing completed scenes, and dynamic, related to the real-time point cloud data captured by moving robots. For both static and dynamic environments, we introduce tailored heightmap classifiers, incorporating Inertial Measurement Unit (IMU) insights to consider the robot motion influenced by terrain texture. Our proposed method demonstrates superior performance compared to existing methods that analyze the point cloud directly and perform texture analysis with high accuracy in both static and dynamic environments. The code can be downloaded from https://github.com/zzziito/BumpyPatch.
 
# Summary. An optional shortened abstract.
summary: This research introduces an innovative approach to enhancing autonomous mobile robot navigation in diverse outdoor environments. We developed a method that transforms 3D LiDAR point cloud data into grayscale heightmaps, enabling more accurate assessment of ground textures. Our system classifies terrains in both static and dynamic environments, incorporating IMU data to account for robot motion influenced by terrain. The method demonstrates superior performance in texture analysis compared to direct point cloud analysis techniques, significantly improving the ability of mobile robots to navigate safely and efficiently across various outdoor terrains. This advancement is crucial for protecting sensitive equipment and cargo while expanding the operational capabilities of autonomous robots in complex, real-world settings.

tags: 
- Artificial Intelligence
- Heightmap
- Point Cloud
- Outdoor Mobile Robot
# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: arXiv
#   url: https://arxiv.org/abs/2311.10339

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10473575'
url_code: 'https://github.com/zzziito/BumpyPatch'

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
