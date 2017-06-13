---
layout: post
title: Anneaux et Idéaux
date: 2017-05-12 14:38:56.000000000 +02:00
categories:
- Maths
tags: []
---

Nous avons tous appris à l'école ce qui est parfois connu sous le nom de "théorème fondamental de l'arithmétique", à savoir que tout nombre entier (positif) peut s'écrire de façon unique (à l'ordre des facteurs près) comme un produit de nombres premiers. Évidemment, les choses sont un tout petit peu plus compliquées si l'on veut traiter tous les entiers relatifs; y compris les négatifs. Dans ce cas, il faut prendre en compte une éventuelle multiplication par $-1$. Comme un des processus les plus répandus en mathématique repose sur l'idée de généraliser des propriétés intéressantes pour les appliquer en dehors de leur domaine initiale, on peut se demander s'il existe d'autres objets, sortes de généralisations des entiers relatifs, qui disposeraient d'un équivalent du théorème fondamental assurant l'existence et l'unicité de la décomposition en "facteurs premiers".

Dans ce post, je vais considérer des anneaux $(A,+,\times)$ qui seront toujours commutatifs. Ces anneaux peuvent être naturellement quotientés par des *idéaux*, c'est-à-dire des sous-groupes additifs $\mathfrak{a}$ tels que $A \mathfrak{a} \subset \mathfrak{a}$. Des exemples importants d'idéaux sont les idéaux *principaux*, c'est-à-dire l'ensemble des multiples d'un élément $x \in A$, ce que l'on note $(x)$.

Les idéaux sont en quelque sorte une généralisation des nombres entiers, et ils vont nous permettre d'étendre la notion usuelle de nombre premier. On dira qu'un idéal $\mathfrak{p}$ est *premier* si $xy \in \mathfrak{p}$ implique que $x$ ou $y$ appartiennent à $\mathfrak{p}$. Rappelons qu'un anneau $A$ est dit *intègre* s'il ne possède pas de diviseur de zéro, c'est-à-dire d'élément $x$ non nul dont le produit avec un autre élément de $A$ est nul. On a alors l'équivalence fondamentale

$$A / \mathfrak{p} \textrm{ est intègre } \Leftrightarrow \mathfrak{p} \textrm{ est premier.}$$
