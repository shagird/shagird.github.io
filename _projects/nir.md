---
layout: post
title: "Swarming midges as self-propelled particles with long-range interaction"
date: 2024-11-27
category: project
short_description: "Simulating active matter models of midge swarms using a modified gravitational potential to model acoustic interactions to verify if the model can better reproduce the core dynamics of the swarms."
project_image: "/assets/images/NG1.png"
---

**PI: Dr. Nir Gov\
Professor, Department of Chemical and Biological Physics, Weizmann Institute of Science, Israel**

Collective behavior manifests in living systems mainly in two ways: flocking and swarming. Flocks are characterized by the individual particles breaking rotational symmetry which results in a global, polarized structure. While flocks are characterized by order, swarms on the other hand are inherently disordered. Despite this global disorder, swarm particles are tightly bound to the swarm and exhibit long-range correlations within the swarm. It is known that the swarms form in the presence of a marker like light source or surface of water. This although does explain a particle’s boundedness to the swarm but not the correlations. Thus, swarms pose an interesting problem: an emergent structure that appears disconnected but shows non-trivial correlations between particles. Since the swarms are stochastic structures, different modeling approaches can create natural-looking swarm-like structures. So researchers look at different physical measurements of the swarms and check which modeling approaches reproduces them.

In this project we are interested in modeling the swarming behavior of midges. Midges are small insect-like creatures that interact using sound. We are modeling them as self-propelled, long-range interacting particles. Prof Gov and his team developed a mechanistic model called adaptive gravity, where adaptive takes into account a midge’s ability to attenuate the intense signal, and gravity is the long-range interaction potential that models sound, as they both follow inverse-square law. We are modifying this adaptive gravity model by adding self-propulsion to it. We wanted to see what kind of behavior we would produce by treating midges like active particles instead of gravitational bodies and making forces change only the heading direction. This was in contrast to the phenomenological modeling schemes used by other researchers. To our surprise, this modified model was able to explain the observed behavior better than the original adaptive gravity model. This is a great result as many other communication systems, like vision, also follow inverse-square law, and we can use this model for other types of collective behavior, too. 

With this project, I am learning about mechanistic modeling and how we can model organismal-level behavior by modifying traditional physics laws with assumptions about various conservation laws and equilibrium characteristics and creating new ones that biological systems follow. On the computational side, I became comfortable with and appreciative of the Linux environment widely used by computational scientists by using it heavily for performing my simulations. 