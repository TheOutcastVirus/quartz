---
Created: 2025-04-14
Type: Zettel
aliases: 
References:
  - https://www.flippingphysics.com/uploads/2/1/1/0/21103672/0200_lecture_notes_-_ap_physics_c-_rotational_dynamics_review_-_1_of_2__mechanics_.pdf
  - https://www.flippingphysics.com/apc-rotational-dynamics-1-review.html
Links:
---
We apply the limit to the definition of moment of inertia to calculate it for a continuous mass object. 
$$
I = \lim_{ \Delta m \to 0 } \sum_{i}r^2\Delta m_{i}
$$
$$
I = \int r^2dm
$$
## Examples 
### Moment of Inertia for a uniform thin hoop

$$
I = \int r^2 dm \to r \text{ is constant}
$$
$$
I = R^{2} \int dm = R^{2}m
$$
### Moment of Inertia of a uniform rod

$$
\lambda = \frac{m}{a} = \frac{dm}{dx}
$$
$$
dm = \lambda dx = \frac{m}{L}dx
$$
$$
I = \int r^{2}dm = \int r^2 \frac{m}{L}dx = \frac{m}{L} \int_{-\frac{L}{2}}^{\frac{L}{2}} x^{2}dx
$$
Which evaluates to $\frac{1}{12}mL^{2}$
