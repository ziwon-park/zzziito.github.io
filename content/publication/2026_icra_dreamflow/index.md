---
title: 'DreamFlow: Local Navigation Beyond Observation via Conditional Flow Matching in the Latent Space'

authors:
  - admin
  - Dongkyu Lee
  - I Made Aswin Nahrendra
  - Jaeyoung Lim
  - Hyun Myung

date: '2026-03-03T00:00:00Z'
doi: '10.48550/arXiv.2603.02976'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Robotics and Automation 2026
publication_short: ICRA 2026

abstract: |-
  We present DreamFlow, a deep reinforcement learning framework for robot navigation in obstacle-dense environments. Conventional planners and perception systems are constrained by the robot's immediate sensor range, leading to navigation failures in cluttered environments. DreamFlow addresses this limitation by employing conditional flow matching to extend the robot's perceptual range through probabilistic mapping between local height map representations and broader spatial features. This enables robots to anticipate obstacles beyond their immediate field of view and proactively circumvent potential navigation failures. We validate our approach in both simulated maze and hallway scenarios and real-world environments using a Unitree Go2 quadrupedal robot equipped with dual LiDAR sensors, demonstrating superior performance in latent space prediction accuracy and navigation tasks compared to existing methods.

# Summary. An optional shortened abstract.
summary: DreamFlow is a deep RL framework that uses conditional flow matching to extend a robot's perceptual range beyond its sensor FOV, enabling proactive navigation around unseen obstacles in cluttered environments.

tags:
  - Robot Navigation
  - Deep Reinforcement Learning
  - Flow Matching
  - Heightmap
  - Legged Robot

# Display this page in the Featured widget?
featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2603.02976
- name: Project Page
  url: https://dreamflow-icra.github.io/

url_pdf: 'https://arxiv.org/pdf/2603.02976'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  focal_point: ''
  preview_only: false
---
