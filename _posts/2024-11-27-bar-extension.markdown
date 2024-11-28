---
layout: post
title:  "Energy minimization for the bar extension problem" 
date:   2024-11-27 
categories: physics
---

**Source:** [YouTube video by G R Krishna Chand Avatar](https://youtu.be/3aXA0ySDmHw?si=BL8QN9w8nWwZHrsG) 

# Bar extension problem 
Total internal energy by integerating over internal (strain) energy density 

$$
U = \frac{1}{2}\int\sigma\epsilon d\tau = \frac{1}{2}\int\left(YA\frac{du}{dx}\right)\frac{du}{dx} dx
$$

Work done by external energy 

$$
W = \int qudx
$$

Total potential energy 

$$
\Pi = U - W = \int dx \left[\frac{1}{2}Y A\left(\frac{du}{dx}\right)^2 - qu\right] \equiv \int dx\pi\left(x,u,\frac{du}{dx}\right)
$$

We will reach a stable state under the minimization of potential energy: $\delta \Pi = 0$. 

Using the language of variational calculus, we can use the Euler-Lagrange differential equation which states that: 

$$
J = \int f(t,y,\dot{y}) dt \implies \frac{\partial f}{\partial y} - \frac{d}{dt}\frac{\partial f}{\partial \dot{y}} = 0 \iff \delta J = 0
$$

For the potential energy above, the Euler-Lagrange equation would be: 

$$
\delta \Pi = 0 \iff \frac{\partial \pi}{\partial u} - \frac{d}{dx}\frac{\partial \pi}{\partial u'} = 0
$$ 

Then the governing equation for beam extension problem becomes:

$$
-q - \frac{d}{dx}\left(YA\frac{du}{dx}\right) = 0
$$
