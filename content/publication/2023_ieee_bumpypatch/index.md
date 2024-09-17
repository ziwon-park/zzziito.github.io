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
doi: '10.1109'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In IEEE International Conference on Robotic Computing 2023
publication_short: In IEEE IRC 2023

abstract: |-
 Autonomous mobile robots operate in a range of environments, from controlled indoor settings to unpredictable outdoor terrains. These varied conditions present challenges that require advanced navigation systems for their safe and efficient operation. A key component of this navigation is accurately assessing the ground texture. Any misjudgments can jeopardize both the robot's sensitive equipment and its carried cargo. In this research, we propose a novel method that uses heightmaps created by mapping the z -coordinates of 3D LiDAR-derived point cloud data to grayscale pixel values for evaluating outdoor ground textures. This approach effectively converts point cloud data, providing information to assist mobile robots in navigating less bumpy roads in outdoor settings. We present classification techniques for terrains based on the environment's nature: static, which pertains to individual point cloud files representing completed scenes, and dynamic, related to the real-time point cloud data captured by moving robots. For both static and dynamic environments, we introduce tailored heightmap classifiers, incorporating Inertial Measurement Unit (IMU) insights to consider the robot motion influenced by terrain texture. Our proposed method demonstrates superior performance compared to existing methods that analyze the point cloud directly and perform texture analysis with high accuracy in both static and dynamic environments. The code can be downloaded from https://github.com/zzziito/BumpyPatch.
 
# Summary. An optional shortened abstract.
summary: The paper introduces A2XP, a novel approach for domain generalization, which optimizes prompts for each source domain and combines them for robust performance across domains, while also preserving privacy and integrity of the network architecture. Experimental results demonstrate its state-of-the-art performance in computer vision tasks and its potential for broader applications.

tags: 
- Artificial Intelligence
- Deep Learning
- Domain Generalization
- Privacy-preservation
- Adversarial Reprogramming
- Visual Prompt Tuning
- Representation Learning
- CLIP
- Conference
- IEEE
- CVF
- CVPR

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2311.10339

url_pdf: 'https://openaccess.thecvf.com/content/CVPR2024/papers/Yu_A2XP_Towards_Private_Domain_Generalization_CVPR_2024_paper.pdf'
url_code: 'https://github.com/AIRLABkhu/A2XP'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: 'https://airlabkhu.github.io/A2XP/static/pdfs/A2XP_poster.pdf#view=fit'
url_project: 'https://airlabkhu.github.io/A2XP/'
url_slides: 'https://airlabkhu.github.io/A2XP/static/pdfs/A2XP_slides.pdf#view=fit'
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

<iframe src="https://airlabkhu.github.io/A2XP/static/pdfs/A2XP_poster.pdf#view=fit" width="100%" height="400">
</iframe>

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
