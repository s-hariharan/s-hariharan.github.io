---
layout: project
title: Grain Growth using Monte Carlo Methods
categories: projects
permalink: research/anisotropy-solid
---

Anisotropy in crystalline materials plays an important role in determining bulk properties of the material. When the melt of metal is solidified by removing heat, dendritic growth of the solid phase is observed. Anisotropy present in crystalline materials makes the dendrites to prefer few planes over the other.

In this study, we try to incorporate interfacial energy and attachment kinetic anisotropy using the extended Cahn-Hilliard model. The mathematical formulation for the solidification phenomena is based on the classic work by Kobayashi.

For the numerical implementation we have gone with a finite difference scheme. The simulation parameters would be published later.


<figure>
  <img class="full" src="/images/research/anisotropy/kobayashi.png" alt="Kobayshi">
  <figcaption>Reproduction of Kobayashi's work.</figcaption>
</figure>


<figure>
  <img class="full" src="/images/research/anisotropy/unrotated.png" alt="Using extended CH model">
  <figcaption>Resulting morphology using extended Cahn-Hilliard Model.</figcaption>
</figure>

Since anisotropy is being incorporated using higher order tensor fields (which lead to cubic anisotropy in this case), rotation of the field results in rotation of the preferred planes.

<figure>
  <img class="full" src="/images/research/anisotropy/rotated.png" alt="rotated">
  <figcaption>Resulting morphology using extended Cahn-Hilliard Model when rotated by 45 degrees.</figcaption>
</figure>
