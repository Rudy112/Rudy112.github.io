---
title: "Synthetic data enables faster annotation and robust segmentation for multi-object grasping in clutter"
collection: publications
permalink: /publication/fruit
excerpt:  Dongmyoung Lee, **Wei Chen** and Nicolas Rojas
date: 2024-01-24
venue: ' 2024 10th International Conference on Mechatronics and Robotics Engineering (ICMRE)'
paperurl: 'https://arxiv.org/pdf/2401.13405.pdf'
---



Object recognition and object pose estimation in robotic grasping continue to be significant challenges, since building a labelled dataset can be time consuming and financially costly in terms of data collection and annotation. In this work, we propose a synthetic data generation method that minimizes human intervention and makes downstream image segmentation algorithms more robust by combining a generated synthetic dataset with a smaller real-world dataset (hybrid dataset). Annotation experiments show that the proposed synthetic scene generation can diminish labelling time dramatically. RGB image segmentation is trained with hybrid dataset and combined with depth information to produce pixel-to-point correspondence of individual segmented objects. The object to grasp is then determined by the confidence score of the segmentation algorithm. Pick-and-place experiments demonstrate that segmentation trained on our hybrid dataset (98.9%, 70%) outperforms the real dataset and a publicly available dataset by (6.7%, 18.8%) and (2.8%, 10%) in terms of labelling and grasping success rate, respectively.
[Download paper here](https://arxiv.org/pdf/2401.13405.pdf)

