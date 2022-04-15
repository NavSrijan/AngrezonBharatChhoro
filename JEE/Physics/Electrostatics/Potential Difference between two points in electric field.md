---
date: 14-04-2022
tags:
- Physics
- Electrostatics
- 
---
```ad-note
title: Definition 
Work done in displacing a unit positive charge from one point to another against electric forces is called the potential difference between these points.
```

![](https://i.imgur.com/xE018ti.png)
$U_{A}=qV_{A}$
$U_{B}=qV_{B}$
When charge q, is displaced from A to B, work done:
$$W=U_{B}-U_{A}$$
$$\Rightarrow \boxed{W=q(V_{B}-V_{A})}\tag{eq. 1}$$
$$\text{Work}=\text{Charge}\times \text{Potential Difference}$$

eq. 1 gives work done by external agent in displacing the charge against the electric forces of the field.
Work done by electric field is given as:
$$W=q(V_{A}-V_{B})$$
$$\boxed{V_{A}-V_{B}=\frac{W}{q}}$$

## Relation between E and V
$\Delta V=\frac{W_{ext.}}{q}=\frac{-W_{cons.}}{q}$
$=\frac{-\int{\vec{F_{elec}}\cdot \vec{dr}}}{q}=\frac{-\int{q \vec{E}\cdot \vec{dr}}}{q}$
$$\boxed{\Delta V=-\int{\vec{E}\vec{dr}}}$$
$$\boxed{\vec{E}=\frac{-dv}{dr}= \frac{-dv}{dx}\hat{i}-\frac{-dv}{dy}\hat{j}-\frac{-dv}{dz}\hat{k}}$$
$\frac{dv}{dr}$ is also known as [[Electric Potential Gradient]]
- Field is the negative gradient of potential.

### Using the relation between E and V
#### Case 1: V is given $\vec{E}$ is asked 
V will be given as a function of position coordinates, V = f(x) then, the [[Electric Field]] in that direction is:
$E_{x}=\frac{-dV}{dx}$ (y, z $\Rightarrow$ constant)
$E_{y}=\frac{-dV}{dy}$ (x, z $\Rightarrow$ constant)
$E_{z}=\frac{-dV}{dz}$ (x, y $\Rightarrow$ constant)

==Basically just partial differentiation==

Question to help:
![](https://i.imgur.com/uiPZqvY.png) $\tag{question}$
### Case 2: $\vec{E}$ is given and then V is asked 
$$\boxed{\Delta V=-\int_{A}^{B}{\vec{E}\,d \vec{S}}}$$
In case of uniform field, it gets simplified to:

$$\boxed{\Delta V=-\vec{E}\cdot \vec{S}}$$
