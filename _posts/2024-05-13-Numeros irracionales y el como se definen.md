---
title: ¿Como se definen los números irracionales?
categories: [Conjuntos, Números]
tags: [matemáticas]     # TAG names should always be lowercase
math: true
toc: true
---

Todos hemos tenido y usado una regla, un instrumento para medir con el que dibujamos líneas y que nos acompañó en los cursos de educación básica para crear figuras matemáticas y medir objetos, pero ¿Qué tantas matemáticas esconde esa simple regla?.

Puede sonar un poco raro, pero no pudimos entender con total precisión la regla, mas específicamente: la recta real sino hasta la segunda mitad del siglo XIX cuando un matemático alemán llamado Julius Dedekind definió los números irracionales con su idea de _cortar_ la recta real en puntos específicos usando como ayuda los números racionales. 

### Racionales y sus subconjuntos
Antes de pasar en los aspectos técnicos del _como_ recordemos que los racionales ($\mathbb{Q}$) son todos los números que se puedan escribir como una división de dos enteros, teniendo el denominador distinto de 0. 

$$\mathbb{Q} = \{a,b\in \mathbb{Z}: \frac{a}{b} \land b \ne 0 \}$$

Notemos que dentro de los racionales tenemos conjuntos interesantes y que han sido estudiados por siglos e incluso milenios. Tenemos a los números naturales ($\mathbb{N}$) que son los números que usamos para contar y que dependiendo de la rama de las matemáticas o el autor puede o no incluir el cero.

$$\mathbb{N} = \{1,2,3,4,5,\cdots,n \}$$

$$\mathbb{N}_0 = \{0,1,2,3,4,5,\cdots,n \}$$

Tenemos igual los números enteros ($\mathbb{Z}$) que tienen los números naturales, los enteros negativos y el cero.

$$\mathbb{Z} = \{\cdots,-3,-2,-1,0,1,2,3,\cdots\}$$

Los racionales son un conjunto extenso, pero no logran definir todos los tipos de números que hay. Un ejemplo de esto es $\sqrt{2}$ que no puede escribirse como una división de dos enteros, cosa que según lo que se cuenta le costó la vida a manos de Pitágoras a la persona que lo descubrió.

### ¿Como son los irracionales?

Muchos saben que números como $e$ o $\pi$ son irracionales pero ¿siguen algún patrón? ¿hay mas irracionales que racionales? ¿sabemos donde están?. Las respuestas a estas preguntas son fascinantes y en este post resolveremos la primera y tercera pregunta, dejando para un futuro el tamaño de dichos conjuntos. Pues bien, los irracionales son números, que vistos en su forma decimal, no siguen ningún patrón mas que tener infinitos decimales, puesto que cualquier número que tenga un fin o tenga decimales periódicos (es decir, un patrón numérico que se repita) pueden ser escritos como la razón de dos números enteros.

### La construcción de los irracionales de Dedenkind 

Imaginemos que tomamos un número  $r$, esto cortará a los racionales en dos conjuntos, un conjunto $L$ que tendrá los racionales menores o iguales a $r$ y el conjunto $R$ que tendrá a los racionales mayores que $r$. Cada cortadura de Dedekind representa un único número real. Si el conjunto ( $\mathbb{L}$ ) tiene un máximo, entonces la cortadura representa ese número racional máximo. Si no tiene máximo, la cortadura representa un número irracional.