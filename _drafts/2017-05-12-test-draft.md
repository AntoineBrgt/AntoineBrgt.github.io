---
layout: post
title: Le bon test !
date: 2017-05-12 14:38:56.000000000 +02:00
categories:
- Maths
tags: []
---

Nous avons tous appris à l'école ce qui est parfois connu sous le nom de "théorème fondamental de l'arithmétique", à savoir que tout nombre entier (positif) peut s'écrire de façon unique (à l'ordre des facteurs près) comme un produit de nombres premiers 

Dans ce post, je vais considérer des anneaux $(A,+,\times)$ qui seront toujours commutatifs. Ces anneaux peuvent être naturellement quotientés par des *idéaux*, c'est-à-dire des sous-groupes additifs $\mathfrak{a}$ tels que $A \mathfrak{a} \subset \mathfrak{a}$. Des exemples importants d'idéaux sont les idéaux *principaux*, c'est-à-dire l'ensemble des multiples d'un élément $x \in A$, ce que l'on note $(x)$.

Les idéaux sont en quelque sorte une généralisation des nombres entiers, et ils vont nous permettre d'étendre la notion usuelle de nombre premier. On dira qu'un idéal $\mathfrak{p}$ est *premier* si $xy \in \mathfrak{p}$ implique que $x$ ou $y$ appartiennent à $\mathfrak{p}$. Rappelons qu'un anneau $A$ est dit *intègre* s'il ne possède pas de diviseur de zéro, c'est-à-dire d'élément $x$ non nul dont le produit avec un autre élément de $A$ est nul. On a alors l'équivalence fondamentale

$$A / \mathfrak{p} \textrm{ est intègre } \Leftrightarrow \mathfrak{p} \textrm{ est premier.}$$
