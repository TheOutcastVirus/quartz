---
Created: 2025-04-22
Type: Zettel
aliases: 
References:
  - https://www.flippingphysics.com/uploads/2/1/1/0/21103672/0200_lecture_notes_-_ap_physics_c-_rotational_dynamics_review_-_1_of_2__mechanics_.pdf
  - https://www.flippingphysics.com/apc-rotational-dynamics-1-review.html
Links:
---
The rotational kinetic [[energy]] for an object can be expressed as the sum of all the translational kinetic energies for all particles in a solid object. We can iterate through all the points on the object using sum notation. Note that we used the equation for [[Tangential Velocity and Acceleration|tangential velocity]] to convert between the two forms. 
$$
KE_{t} = \sum_{i}KE_{i} = \sum_{i} \frac{1}{2} m_{i} (v_{1})^2 = \sum_{i} \frac{1}{2} m_{i} (r_{i}\omega_{i})^2
$$
Which simplifies to 

$$
\sum_{i} \frac{1}{2} m_{i}r_{i}^2 \omega_{i}^2
$$
The rotational velocity, $\omega_{i}$ is the same for all points on the object, so the expression becomes 
$$
\frac{1}{2}(\sum_{i}m_{i}r_{i}^2)\omega_{i}^2
$$
Which is equivalent to 
$$
\frac{1}{2}I\omega^2
$$
Where  $I$, the [[Moment of Inertia|moment of inertia]], is defined as $\sum_{i}m_{i}r_{i}^2$ . Notice the similarities between this and the equation for [[work|kinetic energy]].