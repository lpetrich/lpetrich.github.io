---
title: "Visual Geometric Skill Inference by Watching Human Demonstration."
collection: publications
permalink: /publication/2020-05-31-visual-geom-skill-inf
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2020-05-31
venue: '2020 IEEE International Conference on Robotics and Automation (ICRA)'
paperurl: 'http://lpetrich.github.io/files/ICRA2-visual-geom-skill-inf.pdf'
citation: 'Jin, J., <b>Petrich, L.</b>, Zhang, Z., Dehghan, M., and Jägersand, M. (2019). &quot;Robot eye-hand coordination learning by watching human demonstrations: a task function approximation approach.&quot; In <i>2019 IEEE International Conference on Robotics and Automation (ICRA)</i>, pp. 6624-6630.'
---
**Abstract**

We study the problem of learning manipulation skills from human demonstration video by inferring the association relationships between geometric features. Motivation for this work stems from the observation that humans perform eye-hand coordination tasks by using geometric primitives to define a task while a geometric control error drives the task through execution. We propose a graph based kernel regression method to directly infer the underlying association constraints from human demonstration video using Incremental Maximum Entropy Inverse Reinforcement Learning (InMaxEnt IRL). The learned skill inference provides human readable task definition and outputs control errors that can be directly plugged into traditional controllers. Our method removes the need for tedious feature selection and robust feature trackers required in traditional approaches (e.g. feature-based visual servoing). Experiments show our method infers correct geometric associations even with only one human demonstration video and can generalize well under variance.
