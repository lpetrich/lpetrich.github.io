---
title: "Robot eye-hand coordination learning by watching human demonstrations: a task function approximation approach."
collection: publications
permalink: /publication/2019-05-20-task-func-approx
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2019-05-20
venue: '2019 IEEE International Conference on Robotics and Automation (ICRA)'
paperurl: 'http://lpetrich.github.io/files/ICRA19-task-func-approx.pdf'
citation: 'Jin, J., <b>Petrich, L.</b>, Dehghan, M., Zhang, Z., and Jägersand, M. (2019). &quot;Robot eye-hand coordination learning by watching human demonstrations: a task function approximation approach.&quot; In <i>2019 IEEE International Conference on Robotics and Automation (ICRA)</i>, pp. 6624-6630.'
---
<!-- This paper is about the number 1. The number 2 is left for future workssssss -->

<!-- [Download paper here](http://lpetrich.github.io/files/ICRA19-online-learning-hri.pdf)

Dehghan, M., Zhang, Z., Siam, M., Jin, J., **Petrich, L.**, and Jägersand, M. (2019) "Online Object and Task Learning via Human Robot Interaction." <i>In 2019 IEEE International Conference on Robotics and Automation (ICRA)</i>, pp. 2132-2138. -->

**Abstract**

We present a robot eye-hand coordination learning method that can directly learn visual task specification by watching human demonstrations. Task specification is represented as a task function, which is learned using inverse reinforcement learning(IRL[1]) by inferring a reward model from state transitions. The learned reward model is then used as continuous feedbacks in an uncalibrated visual servoing(UVS[2]) controller designed for the execution phase. Our proposed method can directly learn from raw videos, which removes the need for hand-engineered task specification. Benefiting from the use of a traditional UVS controller, the training on real robot only happens at initial Jacobian estimation which takes an average of 4-7 seconds for a new task. Besides, the learned policy is independent from a particular robot, thus has the potential of fast adapting to other robot platforms. Various experiments were designed to show that, for a task with certain DOFs, our method can adapt to task/environment changes in target positions, backgrounds, illuminations, and occlusions.