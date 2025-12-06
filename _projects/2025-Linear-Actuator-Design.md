---
layout: project
title: Linear Actuator Design
description: Linear Actuator Design
technologies: ibisPaint X
image: /assets/images/Linear-Actuator-Design.jpg
---

The design task was to create a lifting mechanism that fits entirely within a two-dimensional design envelope measuring 150 cm in width and 50 cm in height. The primary goal of the design was to lift the maximum possible weight to the greatest achievable height within this limited space. The mechanism was required to use a single rigid bar, whose length was selected to maximize lift performance, three pin supports (two fixed to the ground and one movable connection), and one linear actuator chosen from an online catalog based on its maximum rated thrust. For this initial step of the analysis, all components—including the actuator, supports, and bar—were assumed to be perfectly rigid, meaning that no deformation was considered. 

Several constraints governed the design. The entire mechanism had to remain within the 150 cm × 50 cm envelope at all times, and the bar length could not exceed the diagonal clearance available within this space. Exactly three pin supports were permitted: two mounted to the ground to provide stability and one used to connect the bar to the actuator. Only a single linear actuator could be used, and its force capacity was limited to the catalog-specified maximum thrust. Within these constraints, the design objectives were to maximize the lifting height at the tip of the bar, maximize the lifted weight as limited by actuator force, maintain structural stability through appropriate support placement, and optimize the bar geometry to achieve both forward reach and vertical travel. 

The design offered several degrees of freedom that could be adjusted to improve performance. These included the length of the bar, which directly affected the achievable vertical displacement; the angle of the bar, which had to be chosen to fit within the 50 cm height constraint; the horizontal spacing between the two ground-mounted pin supports; the actuator’s mounting position and stroke direction; and the placement of the upper pin support that guided the bar’s rotation. Each of these parameters influenced the kinematic and force behavior of the mechanism. 

A static analysis was conducted under the assumption that the bar behaved as a rigid body. To satisfy the 50 cm height constraint within a 150 cm bar length, the bar angle was determined using simple trigonometry. The required relationship, sin θ = 50/150, yields a bar angle of approximately 19.47°. With this angle, the horizontal projection of the 150 cm bar is √(150² − 50²), which equals 141.42 cm. This horizontal distance dictates the required spacing between the two ground-mounted pin supports to ensure proper geometry and stability. 

Finally, the load capacity of the mechanism was evaluated using the selected IMA55 linear actuator, which has a maximum rated thrust of 35,810 N. Because the mechanism is assumed to be perfectly rigid, all of the actuator force is transmitted directly through the bar without loss. Therefore, under ideal alignment conditions, the maximum lifted weight is equal to the maximum actuator force, resulting in a maximum load capacity of 35,810 N.

![Photo of my linear acutuator design]({{ "/assets/images/Linear-Actuator-Design.jpg" | relative_url }}){: .inline-image-l}