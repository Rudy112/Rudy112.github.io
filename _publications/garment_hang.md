---
title: "Learning to Grasp Clothing Structural Regions for Garment Manipulation Tasks"
collection: publications
permalink: /publication/garment_hang
excerpt: '**Wei Chen**, Dongmyoung Lee, Digby Chappell, and Nicolas Rojas'
date: 2023-12-10
venue: 'The 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2023)'
paperurl: 'https://arxiv.org/pdf/2306.14553.pdf'
---



![garment_hang](https://github.com/Rudy112/weichen.github.io/assets/55579633/1cc7af47-327b-4423-96dc-3b5bcb081dac)



When performing cloth-related tasks, such as garment hanging, it is often important to identify and grasp certain structural regions -- a shirt's collar as opposed to its sleeve, for instance. However, due to cloth deformability, these manipulation activities, which are essential in domestic, health care, and industrial contexts, remain challenging for robots. In this paper, we focus on how to segment and grasp structural regions of clothes to enable manipulation tasks, using hanging tasks as case study. To this end, a neural network-based perception system is proposed to segment a shirt's collar from areas that represent the rest of the scene in a depth image. With a 10-minute video of a human manipulating shirts to train it, our perception system is capable of generalizing to other shirts regardless of texture as well as to other types of collared garments. A novel grasping strategy is then proposed based on the segmentation to determine the grasping pose. 

Experiments demonstrate that our proposed grasping strategy achieves 92%, 80%, and 50% grasping success rates with one folded garment, one crumpled garment and three crumpled garments, respectively. Our grasping strategy performs considerably better than tested baselines that do not take into account the structural nature of the garments. With the proposed region segmentation and grasping strategy, challenging garment hanging tasks are successfully implemented using an open-loop control policy.


[Download paper here](https://arxiv.org/pdf/2306.14553.pdf) | [website](https://sites.google.com/view/garment-hanging) | [presentation](https://www.youtube.com/watch?v=fEmlbfU8yss)

