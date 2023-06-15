---
title: "Learning State Conditioned Linear Mappings for Low-Dimensional Control of Robotic Manipulators."
collection: publications
permalink: /publication/2023-05-29-linear-map-robot-manip
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2023-05-29
venue: '2023 IEEE International Conference on Robotics and Automation (ICRA)'
paperurl: 'http://lpetrich.github.io/files/ICRA23-linear-map-robot-manip.pdf'
citation: 'Przystupa, M., Johnstonbaugh, K., Zhang, Z., <b>Petrich, L.</b>, Dehghan, M., Haghverd, F., and Jägersand, M. (2023). &quot;Learning State Conditioned Linear Mappings for Low-Dimensional Control of Robotic Manipulators.&quot; In <i>2023 IEEE International Conference on Robotics and Automation (ICRA)</i>.'
---
<!-- Need comment here for some reason otherwise Abstract word shows on main publications page -->

**Abstract**

Identifying an appropriate task space can simplify solving robotic manipulation problems. One solution is deploying control algorithms in a learned low-dimensional action space. Linear and nonlinear action mapping methods have trade-offs between simplicity and the ability to express motor commands outside of a single low-dimensional subspace. We propose that learning local linear action representations can achieve both of these benefits. Our state-conditioned linear maps ensure that for any given state, the high-dimensional robotic actuation is linear in the low-dimensional actions. As the robot state evolves, so do the action mappings, so that necessary motions can be performed during a task. These local linear representations guarantee desirable theoretical properties by design. We validate these findings empirically through two user studies. Results suggest state-conditioned linear maps outperform conditional autoencoder and PCA baselines on a pick-and-place task and perform comparably to mode switching in a more complex pouring task.
