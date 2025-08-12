---
Created: "2025-05-03"
Type: Zettel
aliases: 
References: 
Links: 
tags:
---
- The position of the center of mass of a system of particles is:
	- $$
	x_{cm} = \frac{\Sigma m_{i}x_{i}}{\Sigma m_{i}} = \frac{m_{1}x_{1} + m_{2}x_{2}+\dots}{m_{1} + m_{2} +\dots}
	$$
- The velocity of the center of mass can be derived using a derivative
	- $$
	v_{cm} = \frac{dx_{cm}}{dt} = \frac{d}{dt}(\frac{\Sigma m_{i}x_{i}}{\Sigma m_{i}}) = \frac{\Sigma m_{i}v_{i}}{\Sigma m_{i}}
	$$
- And similarly for acceleration, which appears identical to [[Newton's Laws|newton's second law]], just rearranged
	- $$
	a_{cm} = \frac{dv_{cm}}{dt} = \frac{d}{dt}(\frac{\Sigma m_{i}v_{i}}{\Sigma m_{i}}) = \frac{\Sigma m_{i}a_{i}}{\Sigma m_{i}}
	$$
- For a rigid object with shape, the center of mass is
	- $$
	r_{cm} \frac{1}{m_{total}} \int r dm \implies x_{cm} = \frac{1}{m_{total}} \int x dm 
	$$
	- Essentially the average value theorem of an axis with regards to mass
- Mass density can be used to take the integral of x with regards to mass by replacing the differential    
	- Volumetric mass density: $\rho = \frac{m}{v}$
	- Surface mass density: $\sigma = \frac{m}{A}$
	- Linear mass density: $\lambda = \frac{m}{L}$