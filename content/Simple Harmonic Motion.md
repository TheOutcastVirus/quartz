---
Created: 2025-05-03
Type: Zettel
aliases:
  - SHM
References:
  - https://www.flippingphysics.com/uploads/2/1/1/0/21103672/0204_lecture_notes_-_ap_physics_c-_simple_harmonic_motion_review__mechanics_.pdf
Links: 
tags:
---

- Simple harmonic motion is motion that oscillates with a given period
	- The acceleration of an object must be proportional to the position from equilibrium, and the acceleration must be in the direction of equilibrium
- The condition for simple harmonic motion is:
	- $$
	\frac{d^{2}x}{dt^{2}} = - \omega^{2}x
	$$
	- $\omega$, the angular frequency varies for different objects, such as springs and pendulums.
- One equation that satisfies the condition for simple harmonic motion is:
	- $$
	x(t) = A \cos(\omega t + \phi)
	$$
	- Where $\phi$ is the phase shift, translates the equation
- The derivatives of this follow as:
	- $$
	v(t) = \frac{dx}{dt} = \frac{d}{dt}(A\cos(\omega t + \phi)) = -A\omega \sin(\omega t + \phi)
	$$
	- $$
	a(t) = \frac{dv}{dt} = \frac{d}{dt}(-A\omega \sin(\omega t+\phi)) = -A\omega^{2}\cos(\omega t+\phi)
	$$
	- Note how $a(t)$ fulfills the condition for SHM:
		- $$
a(t) = -\omega^{2}(A\cos(\omega t+\phi)) = -\omega^{2}x(t)
		$$
- The total mechanical energy in a system is:
	- $$
	ME_{total} = \frac{1}{2}kA^{2}=\frac{1}{2}mv_{max}^{2}
	$$