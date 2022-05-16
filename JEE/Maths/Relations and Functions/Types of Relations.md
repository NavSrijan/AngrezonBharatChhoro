---
date: 04-05-2022
tags:
- Maths
- Relations and Functions
- 
---

# Empty Relation 
Let A be a set and $\phi \subset A\times A$, it follows that $\phi$ is a relation on A which is called the empty relation.
Example, 
$A=\{1,2,3\}$
$xRy \Leftrightarrow y=3x+2$
$R=\{\}$

# Universal Relation
Let A be a set and $A\times A \subseteq A\times A$, it follows that $A\times A$ is a relation on A which is called the universal relation.
Example,
A={1,2,3}
$xRy \Leftrightarrow x+y\geq 2$
$R=\{(1,1),(1,2),(1,3),(2,1),(2,2),(2,3),(3,1),(3,2),(3,3)\}$

# Identity Relation 
If every element of A is related to itself only.
$$\boxed{I_{A}=\{(a,a):a\in A\}}$$
Example,
$A=\{1,2,3\}$
$R_{1}=\{(1,1),(2,2),(3,3)\}$
```ad-note 
title:Note 
![](https://i.imgur.com/0YPSM4J.png)

```

# Reflexive Relation 
A relation R on a set A is said to be reflexive, if every element of A is related to itself. _Basically, Identity with extra elements allowed._
$$\boxed{(a,a) \in R, \forall\, a\in A}$$
![](https://i.imgur.com/MEN34Dq.png)

# Symmetric Relation 
A relation R on  a set A is said to be a symmetric relation if,
$$\boxed{(a,b) \in R \Rightarrow (b,a)\in R, \forall\, a,b\,\in A}$$
i.e. $aRb \Rightarrow bRa, \forall\,a,b\in A$
Example,
$A=\{1,2,3\}$
$R_{1}={(1,2),(1,3),(2,2),(2,1),(3,1)}$

# Transitive Relation 
Relation Ron set Ais transitive if $xRy$ and $yRz\Rightarrow xRz$

Example,
$A = \{1,2,3,4,5\}$
![](https://i.imgur.com/0wDzKBT.png)



```ad-note 
title:Remark 
Relation is not transitive only when $xRy$ and $yRz$ but not $xRz$. In all other situations R is transitive.
```

# Equivalence Relation 
Relation R defined on any set A is equivalence relation if 
- R is _reflexive _
- R is _symmetric_ 
- R is _transitive_

Example,
$A=\{1,2,3,4,5\}$
$R = \{(1,1),(2,2),(3,3),(4,4),(5,5),(1,5),(5,1)\}$
