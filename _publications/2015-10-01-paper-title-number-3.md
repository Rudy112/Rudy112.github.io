---
title: "TraKDis: A Transformer-based Knowledge Distillation Approach for Visual Reinforcement Learning with Application to Cloth Manipulation"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: '**Wei Chen** and Nicolas Rojas'
date: 2024-1-25
venue: ' IEEE Robotics and Automation Letters '
paperurl: 'https://arxiv.org/abs/2401.13362'

---
Approaching robotic cloth manipulation using reinforcement learning based on visual feedback is appealing as robot perception and control can be learned simultaneously. However, major challenges result due to the intricate dynamics of cloth and the high dimensionality of the corresponding states, what shadows the practicality of the idea. To tackle these issues, we propose TraKDis, a novel Transformer-based Knowledge Distillation approach that decomposes the visual reinforcement learning problem into two distinct stages. 

In the first stage, a privileged agent is trained, which possesses complete knowledge of the cloth state information. This privileged agent acts as a teacher, providing valuable guidance and training signals for subsequent stages. The second stage involves a knowledge distillation procedure, where the knowledge acquired by the privileged agent is transferred to a vision-based agent by leveraging pre-trained state estimation and weight initialization. TraKDis demonstrates better performance when compared to state-of-the-art RL techniques, showing a higher performance of 21.9%, 13.8%, and 8.3% in cloth folding tasks in simulation. Furthermore, to validate robustness, we evaluate the agent in a noisy environment; the results indicate its ability to handle and adapt to environmental uncertainties effectively. Real robot experiments are also conducted to showcase the efficiency of our method in real-world scenarios.

[Download paper here](https://arxiv.org/abs/2401.13362)

