---
title: "Racionando Números"
date: 2022-12-05T18:25:23-03:00
draft: true
math: true
cover:
    image: "posts/racionando-numeros/cover.jpg"
    alt: "cuadrados dispuestos racionalmente"
---
Sí, todos nos sentimos confiados en que sabemos usar fracciones --media docena
de empanadas siempre son 6 empanadas--, ¿pero sabemos porqué dos cuartos es un
medio? ¿porqué sumar es tan difícil? y sobre todo ¡¿a quién se le ocurrió que un
tercio más un medio son cinco sextos?!

{{< figure src="yoda-mate.jpg" height="200px" align=center title="Si seguir este artículo quieres, saber dividir y multiplicar primero debes">}}

## Toda historia tienen un principio
Romper cosas es algo inherente al ser humano, cuendo vemos a nuestros hermanitos
arrancarle las extremidades a las muñecas estamos en presencia de algo **muy**
importante. ¿A qué podemos considerar un muñeco entero? Tiene cabeza, tiene
brazos, tiene un torzo, quizás tenga dos piernas. Esto es $1$ muñeco. ¿Qué es la
mitad de un muñeco?

Podemos considerar la "cantidad de muñeco", su "masa", para saber si es *un*
muñeco o *medio*. Si el muñeco pesaba $100$ gramos, y después de jugar con nico
pesa $50$ gramos, perdió "la mitad" de su "masa". Podemos decir que dividimos
"la cantidad de muñeco" en dos partes.

$\text{un muñeco} = 1🧍= 100g$

$\text{medio muñeco} = \frac{1}{2}🧍 = 50g$

Las fracciones tienen dos números que las identenifican. El *denominador*
representa en cuantas partes "rompimos" el muñeco y el *numerador* nos dice
cuantos "trozos" de muñeco tenemos.

$$
\begin{aligned}
    \frac{\text{cantidad de trozos}}{\text{cantidad de partes}}
    =
    \frac{numerador}{denominador}
\end{aligned}
$$

Si en un día salvaje el pequeño rompe en tres partes una caja con cuatro
muñecos, tendríamos *12 partes* de *un tercio* de muñeco!

$$
\begin{aligned}
    \frac{12}{3}🧍
    =
    \frac{numerador}{denominador}
\end{aligned}
$$

Saquemos del juego al muñeco y veamos sólo los números que usamos. Hay muchas formas de definir a los números racionales ( $\mathbb{Q}$ ), sin embargo considero que la más sencilla es ver que en el *númerador* sólo hay números enteros ( $\Z = {0,-1,1,-2,2,-3,3...}$ ) y en el *denominador* sólo hay números naturales ( $\N = {1,2,3,4,...}$ ) ---presetemos atención a que el denominador **nunca** puede ser 0.

$$
\mathbb{Q} = \Big\\{\frac{p}{q}: p \in \Z, q \in \N\Big\\}
$$

No nos asustemos con la definición formal, esto se lee "el conjunto $\mathbb{Q}$ está formado por los elmento $\frac{p}{q}$, tal que $p$ pertenece a los números enteros y $q$ pertneces a los naturale". Es lo mismo que expliqué en el párrafo anterior.

Entendamos también que la barra que divide ambos números no significa nada en especial, es simplemente una convención, todos nos pusimos de acuerdo en escribir los números racionales de esta forma, pero podríamos haber elegido cualquier otra.

## Equivalencias

Vayamos a comprar un helado. En el mostrador vemos que cada kilo cuesta
$800\\$$. Si quisieramos llevar dos kilo, tendríamos que pagar $1600\\$$. Con
tres, $2400\\$$

$$
\begin{aligned}
    \frac{800\\$}{1kg} = \frac{1600\\$}{2kg} = \frac{2400\\$}{3kg}
\end{aligned}
$$

Vemos que las fracciones no sólo representan "porciones", sino también
equivalencias, relaciones "proporcionales". Supongamos que en vez de querer
llevar dos kilos, pedimos medio kilo o un cuarto. 

$$
\begin{aligned}
    \frac{800\\$}{1kg} = \frac{400\\$}{\frac{1}{2}kg} = \frac{200\\$}{\frac{1}{4}kg}
\end{aligned}
$$

Los números racionales tienen esta propiedad muy útil, pueden escribirse de
muchas formas, de hecho, infinitas.

Tras este "infinto" se esconde un número, el uno. Prestemos un poco más de atención al primer ejemplo y desgranemos cada igualdad.

$$
\begin{aligned}
    &\frac{1600\\$}{2kg} = \frac{800\\$}{1kg} \cdot \frac{2}{2}= \frac{800\\$}{1kg} \cdot 1\\\
    \\\
    &\frac{2400\\$}{3kg} = \frac{800\\$}{1kg} \cdot \frac{3}{3}= \frac{800\\$}{1kg} \cdot 1\\\
\end{aligned}
$$

Sabemos que $2/2$ es igual a uno, $3/3$ también, $4/4$, ...
No importa cuál sea, dividir cualquier número por sí mismo nos dará uno
( $\frac{a}{a}=1$ ). El número uno también tiene una propiedad asombrosa, es el
*elemento neutro de la multiplicación* lo cual significa que cualquier número
multiplicado por uno no cambiará de resultado ( $a\cdot 1 = a$ ).

Ahora sabemos bien porqué dos cuartos es un medio 🤓

$$
\begin{aligned}
    &\frac{2}{4} = \frac{1}{2} \cdot \frac{2}{2} = \frac{1}{2} \cdot 1 = \frac{1}{2}
\end{aligned}
$$

## Sumando

Para sumar necesitamos que ambas fracciones tengan el mismo denominador. Con la
equivalencia podemos usar "truquitos" --lógicos-- que nos permitan sumar
fracciones. Si tenemos medio kilo de helado y compramos un cuarto para la tía
que sólo le gusta la menta granizada ¿cuanto helado compramos?

$$
\begin{aligned}
    \frac{1}{2} + \frac{1}{4}
\end{aligned}
$$

Sabemos que multiplicar por uno no cambia el resultado. Una forma de escribir el
número 1 cómo fracción es $\frac{2}{2}$

$$
\begin{aligned}
    \frac{1}{2} \cdot 1 + \frac{1}{4}
    =
    \frac{1}{2} \cdot \frac{2}{2} + \frac{1}{4}
    =
    \frac{2}{4} + \frac{1}{4}
\end{aligned}
$$

En este punto, se suman los *númeradores* y voilà! sumamos dos fracciones 😎

$$
\begin{aligned}
    \frac{2}{4} + \frac{1}{4}
    =
    \frac{2+1}{4}
    =
    \frac{3}{4}
\end{aligned}
$$

Este proceso se puede generalizar para cualquier número racional.

$$
\begin{aligned}
    &\frac{a}{b} + \frac{c}{d} 
    = 
    \frac{a}{b} \cdot 1 + \frac{c}{d} \cdot 1
    =
    \\\
    \\\
    &\frac{a}{b} \cdot \frac{d}{d} + \frac{c}{d} \cdot \frac{b}{b}
    =
    \frac{ad}{bd} + \frac{cb}{bd}
    =
    \\\
    \\\
    &\frac{ad+cb}{bd}
\end{aligned}
$$

En resúmen

$$
\begin{aligned}
    \frac{a}{b} + \frac{c}{d} 
    =
    \frac{ad+cb}{bd}
\end{aligned}
$$

## Multiplicando

{{< figure src="slide-1.png" height="200px" align=center >}}
{{< figure src="slide-2.png" height="200px" align=center >}}
{{< figure src="slide-3.png" height="200px" align=center >}}

------------------------------------
ESTO TIENE QUE VENIR LUEGO DE EXPLICAR LA MULTIPLACIÓN Y LA SUMA


Seamos un poquito más estrictos, pero volvamos al primer ejemplo sacando la plata y el helado (toda la diversión 😤)

$$
\begin{aligned}
\frac{800}{1} &= \frac{1600}{2} \\\
\end{aligned}
$$

Al ser una igualdad, lo que está a la izquierda es idéntico a lo que está a la derecha. Por lo tanto, si utilizamos las mismas operaciones en ambos lados nada tendría que cambiar.

Empecemos eliminando
$$
\begin{aligned}
    \frac{800}{1} &= \frac{1600}{2} \\\
    \frac{800}{1} \cdot 2 &= \frac{1600}{2} \cdot 2\\\
    \frac{800}{1} \cdot 2 &= \frac{1600}{\cancel{2}} \cdot \cancel{2}\\\
    \frac{1600}{1} &= \frac{1600}{1}\\\
    1600 &= 1600\\\
\end{aligned}
$$

$$
\begin{aligned}
    \frac{800}{1} &= \frac{1600}{2} \\\
    \frac{800}{1} \cdot 2 &= \frac{1600}{2} \cdot 2\\\
    \frac{800}{1} \cdot 2 &= \frac{1600}{\cancel{2}} \cdot \cancel{2}\\\
    \frac{1600}{1} &= \frac{1600}{1}\\\
    1600 &= 1600\\\
\end{aligned}
$$

$$
\begin{aligned}
    \frac{800\\$}{1kg} &= \frac{1600\\$}{2kg} \\\
    \frac{800\\$}{1kg} \cdot 2 &= \frac{1600\\$}{1kg} \cdot 1\\\
    \frac{1600\\$}{1kg} &= \frac{1600\\$}{1kg}\\\
\end{aligned}
$$

$$
\begin{aligned}
    \mathbb{Q} = \Big\\{\frac{p}{q}: p \in \mathbb{Z}, q \in \mathbb{N}\Big\\}
\end{aligned}
$$

$$
\begin{aligned}
    \mathbb{Q} = \Big\\{\frac{p}{q}: p \in \mathbb{Z}, q \in \mathbb{N}\Big\\}
\end{aligned}
$$

# Sumando
$$
\begin{aligned}
    &\frac{a}{b} + \frac{c}{d} = \frac{ad+cb}{bd}
    &\text{definición}
    \\\
    \\\
    &\frac{a}{b} + 0 = \frac{a}{b}
    &\text{elemento neutro}
    \\\
    \\\
    &\frac{a}{b} + \frac{-a}{b} = 0
    &\text{inverso aditivo}
\end{aligned}
$$

# Multiplicanod 
$$
\begin{aligned}
    &\frac{a}{b} \cdot \frac{c}{d} = \frac{ac}{bd}\\\
    &\frac{a}{b} \cdot \frac{c}{d} = \frac{ac}{bd}
\end{aligned}
$$
