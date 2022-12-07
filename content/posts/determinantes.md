---
title: "Determinantes"
date: 2022-12-05T14:55:00-03:00
draft: true
math: true
markup: "mmark"
---

Supongamos que existe una matriz $A$. Si agarramos cualquier fila y la
multiplicamos por 2, tenemos una matriz nueva, que la vamos a nombrar $A'$. Pasa
algo muy curioso entre los determinantes de ambas matrices, *están
relacionados*. El $det(A')$ será igual a $2det(A')$.

$$
\begin{aligned}
&A = \begin{pmatrix}
    a & b \\\
    c & d 
\end{pmatrix},
A' = \begin{pmatrix}
    2a & 2b \\\
    c & d 
\end{pmatrix}
\\\
\\\
&det(A') = 2det(A)
\end{aligned}
$$

Esto pasa con cualquier matriz y con cualquier número. Ahora probaremos con la
matriz $B$, vamos a multiplicar su segunda fila por $\frac{1}{2}$. El $det(A')$
será $2det(A)$

$$
\begin{aligned}
B = \begin{pmatrix}
    a & b \\\
    c & d 
\end{pmatrix},
B' = \begin{pmatrix}
    \frac{1}{2}a & \frac{1}{2}b \\\
    c & d 
\end{pmatrix}\\\
det(B') = \frac{1}{2}det(B)
\end{aligned}
$$

!!!!AGREGAR DEMOSTRACIÓN $\uparrow$

¿Qué pasará si todas las filas de la matríz están multiplicadas por el mismo
número? Supongamos otra matriz, que será $Pepe$ (ya es aburrido usar siempre
letras). También está $Mirko$, que es prducto entre $k$ y $Pepe$. Cada fila de
$Mirko$ es el resultado de multiplicar cada fila de $Pepe$ por $k$.


$$
\begin{aligned}
&Pepe = \begin{pmatrix}
    a & b \\\
    c & d 
\end{pmatrix},
Mirko = 4 \cdot Pepe = \begin{pmatrix}
    ka & kb \\\
    kc & kd 
\end{pmatrix}\\\
\end{aligned}
$$

Usando la propiedad anterior, podemos "factorizar" k de cada fila

$$
\begin{aligned}
|Mirko| = |k\cdot Pepe| =
\begin{vmatrix}
    ka & kb \\\
    kc & kd 
\end{vmatrix}
= k\begin{vmatrix}
    a & b\\\
    kc & kd 
\end{vmatrix}
= kk\begin{vmatrix}
    a & b\\\
    c & d 
\end{vmatrix}
=k^2|Pepe|
\end{aligned}
$$

Bien, tenía pinta de ser "intuitivo" que se pueda sacar la k del determinante, algo parecido a factorizar. Pero ¿por qué $k^2$? Si nos fijamos bien, $Pepe$ y $Mirko$ son dos matrices $\mathbb{R}^{2 \times 2}$.

Para clarificar, vamos a tener que a ser un poco más clásicos. Definimos una
matriz $A \in \mathbb{R}^{n \times n}$, y otra $B = kA$. 

$$
\begin{aligned}
    B = \begin{pmatrix}
        ka_{11} &\dots &ka_{1n}\\\
        \vdots & \ddots & \vdots\\\
        ka_{n1} & \dots & ka_{nn}\\\
    \end{pmatrix}
    = k\begin{pmatrix}
        a_{11} &\dots &a_{1n}\\\
        \vdots & \ddots & \vdots\\\
        a_{n1} & \dots & a_{nn}\\\
    \end{pmatrix}
\end{aligned} $$ 

Si intentamos buscar el determinante de $B$ podemos ayudarnos
de esta propiedad para obetener su determinante. 

$$ \begin{aligned}
&\begin{vmatrix} ka_{11} &\dots &ka_{1n}\\\
        \vdots & \ddots & \vdots\\\
        ka_{n1} & \dots & ka_{nn}\\\
    \end{vmatrix}
    = 
    k\begin{vmatrix}
        a_{11} &\dots &a_{1n}\\\
        \vdots & \ddots & \vdots\\\
        ka_{n1} & \dots & ka_{nn}\\\
    \end{vmatrix}
    = 
    k^2\begin{vmatrix}
        a_{11} &\dots &a_{1n}\\\
        a_{21} &\dots &a_{2n}\\\
        \vdots & \ddots & \vdots\\\
        ka_{n1} & \dots & ka_{nn}\\\
    \end{vmatrix}=\\\
    &=
    k^i\begin{vmatrix}
        a_{11} &\dots &a_{1n}\\\
        \vdots & \ddots & \vdots\\\
        a_{i1} &\dots &a_{in}\\\
        \vdots & \ddots & \vdots\\\
        ka_{n1} & \dots & ka_{nn}\\\
    \end{vmatrix}
    = \dots =
    k^n\begin{vmatrix}
        a_{11} &\dots &a_{1n}\\\
        \vdots & \ddots & \vdots\\\
        a_{n1} & \dots & a_{nn}\\\
    \end{vmatrix}
\end{aligned}
$$

$$
\begin{aligned}
    det(B) = \begin{vmatrix}
        ka_{11} &\dots &ka_{1n}\\\
        \vdots & \ddots & \vdots\\\
        ka_{n1} & \dots & ka_{nn}\\\
    \end{vmatrix}
    =
    k^n\begin{vmatrix}
        a_{11} &\dots &a_{1n}\\\
        \vdots & \ddots & \vdots\\\
        a_{n1} & \dots & a_{nn}\\\
    \end{vmatrix}
    =
    k^n det(A)
\end{aligned}
$$

$$
\begin{aligned}
    &k \in \mathbb{R}, A \in \mathbb{R}^{n\times n}\\\
    &det(kA) = k^n\cdot det(A)
\end{aligned}
$$

Ejemplo

$$
\begin{aligned}
    \begin{vmatrix}
        ka & kb\\\
        kc & kd\\\
    \end{vmatrix}
    = 
    k \cdot \begin{vmatrix}
       a & b \\\
       kc & kd \\\
    \end{vmatrix}
    =
    k^2 \cdot \begin{vmatrix}
       a & b \\\
       a & d \\\
    \end{vmatrix}
\end{aligned}
$$
