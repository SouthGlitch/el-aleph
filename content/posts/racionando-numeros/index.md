---
title: "¿Qué son los números racionales?"
date: 2022-12-05T18:25:23-03:00
draft: false
math: true
cover:
    image: "posts/racionando-numeros/cover.png"
    alt: "cuadrados dispuestos racionalmente"
ShowToc: true
---
Sí, todos nos sentimos confiados en que sabemos usar fracciones --media docena
de empanadas siempre son 6 empanadas--, ¿pero sabemos porqué dos cuartos es un
medio? ¿porqué sumar es tan difícil? y sobre todo ¡¿a quién se le ocurrió que un
tercio más un medio son cinco sextos?!

{{< figure src="yoda-mate.jpg" height="200px" align=center title="Si seguir este artículo quieres, saber dividir y multiplicar primero debes">}}

## Definición
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

Saquemos del juego al muñeco y veamos sólo los números que usamos. Hay muchas
formas de definir a los números racionales ( $\mathbb{Q}$ ), sin embargo
considero que la más sencilla es ver que en el *númerador* sólo hay números
enteros ( $\Z = {0,-1,1,-2,2,-3,3...}$ ) y en el *denominador* sólo hay números
naturales ( $\N = {1,2,3,4,...}$ ) ---presetemos atención a que el denominador
**nunca** puede ser 0.

$$
\mathbb{Q} = \Big\\{\frac{p}{q}: p \in \Z, q \in \N\Big\\}
$$

No nos asustemos con la definición formal, esto se lee "el conjunto $\mathbb{Q}$
está formado por los elmento $\frac{p}{q}$, tal que $p$ pertenece a los números
enteros y $q$ pertneces a los naturales". Es lo mismo que expliqué en el párrafo
anterior.

Entendamos también que la barra que divide ambos números no significa nada en
especial, es simplemente una convención, todos nos pusimos de acuerdo en
escribir los números racionales de esta forma, pero podríamos haber elegido
cualquier otra.

## Equivalencias

Vayamos a comprar un helado. En el mostrador vemos que cada kilo cuesta
$800\\$$. Si quisieramos llevar dos kilos, tendríamos que pagar $1600\\$$. Con
tres, $2400\\$$. Hay una relación, cada $800\\$$ podemos comprar $1kg$ de helado.

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

Tras este "infinto" se esconde un número, el uno. Prestemos un poco más de
atención al primer ejemplo y desgranemos cada igualdad.

$$
\begin{aligned}
    &\frac{1600\\$}{2kg} = \frac{800\\$}{1kg} \cdot \frac{2}{2}= \frac{800\\$}{1kg} \cdot 1\\\
    \\\
    &\frac{2400\\$}{3kg} = \frac{800\\$}{1kg} \cdot \frac{3}{3}= \frac{800\\$}{1kg} \cdot 1\\\
\end{aligned}
$$

Sabemos que $2/2$ es igual a uno, $3/3$ también, $4/4$, ... No importa cuál sea,
dividir cualquier número consigo mismo nos dará uno ( $\frac{a}{a}=1$ ). El
número uno también tiene una propiedad asombrosa, es el *elemento neutro de la
multiplicación* lo cual significa que cualquier número multiplicado por uno no
cambiará de resultado ( $a\cdot 1 = a$ ).

Ahora sabemos bien porqué dos cuartos es un medio 🤓

$$
\begin{aligned}
    &\frac{2}{4} = \frac{1}{2} \cdot \frac{2}{2} = \frac{1}{2} \cdot 1 = \frac{1}{2}
\end{aligned}
$$

## ¿Cómo sumar fracciones?

Para sumar necesitamos que ambas fracciones tengan el mismo denominador. Con la
equivalencia podemos usar "truquitos" --lógicos-- que nos permitan igualar los
denominadores de dos fracciones distintas. Si tenemos medio kilo de helado y
compramos un cuarto para la tía que sólo le gusta la menta granizada ¿cuanto
helado compramos?

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

En este punto, se suman los *númeradores* y voilà! pudimos sumar dos fracciones
😎

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

## ¿Cómo multiplicar fracciones?
Con cosas enteras es bastante fácil, tres tartas más tres tartas son seis
($3+3=2 \cdot 3=6$). Multiplicar números enteros es sumar muchas veces.

Si tenemos una tarta y la dividimos por la mitad, tendremos *media* tarta. Si
volvemos a dividir la *media* tarta por la *mitad*, tendremos un *cuarto* de
tarta. 

{{< figure src="slide-1.png" height="200px" align=center >}}
{{< figure src="slide-2.png" height="200px" align=center >}}

Si sumamos dos *cuartos* de tarta vamos a tener *media* tarta. Si sumamos dos
*mitades* de tarta vamos a tener una tarta *entera*.

{{< figure src="slide-3.png" height="200px" align=center >}}

Cuando multiplicamos fracciones, el *denominador* nos dice "partime esto en
tantas partes" y el *numerador* "dame tanta cantidad de estas partes"

Si tenemos una tarta y la multiplicamos por $\frac{2}{3}$ lo que hacemos es
partir la tarta en tres partes iguales y llevarnos dos pedazos

{{< figure src="slide-4.png" height="200px" align=center >}}

## El inverso multiplicativo.

El número uno es el elemento más importante en la multiplicación, cómo dijimos
antes, todo número (¡cualquiera!) multiplicado por $1$ nos dará el mismo número

$$1\cdot a = a$$

¿Pero cómo podemos encontrar el número uno en cualquier lado? Podemos
preguntarnos ¿por cual número tengo que multiplicar al 7 para obtener uno?

$$7\cdot b = 1$$

Los números racionales nos permiten al multiplicar partir los números enteros en
partes iguales. Si tengo 7 "unidades" y las reparto entre 7 "elementos",
¿cuantas unidades tiene cada elemento?

$$7\cdot \frac{1}{7} = 1$$

A $\frac{1}{7}$ se lo conoce cómo el *inverso multiplicativo* de 7. Saber usarlo
será **fundamental** para que luego podamos dividir fracciones

Todos los números racionales tienen un inverso multiplicativo, y se representa
con un $a^{-1}$.

$$ a \cdot a^{-1} = 1$$

Calcular el inverso multiplicativo es muy fácil, podemos dividir a ambos lado el número $a$

$$ 
\begin{aligned}
    &a \cdot a^{-1} = 1\\\
    &\frac{a \cdot a^{-1}}{a} = \frac{1}{a}
\end{aligned}
$$

Con lo cual, ¡cancelamos $a$ del lado izquierdo!

$$\frac{\cancel{a} \cdot a^{-1}}{\cancel{a}} = \frac{1}{a} $$

Voilà!, hemos definido el inverso multiplicativo 😎

$$a^{-1} = \frac{1}{a}$$

Veamos un ejemplo un poquitito menos abstarcto. ¿Cuál será el inverso
multiplicativo de 117? 

Arrancamos igual que antes

$$117\cdot 117^{-1} = 1$$

Despejamos $117^-1$

$$117^{-1} = \frac{1}{117}$$

Listo! ¿fácil no?

Podemos usar la misma idea para encontrar el inverso multiplicativo de una
fracción. Intentemos buscar $(\frac{a}{b})^{-1}$. Va a ser algo tedioso, pero
les prometo que después se hacer muy fácil y casi sin pensar

$$
\frac{a}{b}\Big(\frac{a}{b}\Big)^{-1} = 1
$$

Primero tenemos que dejar solito $(\frac{a}{b})^{-1}$ en el lado izquierdo,
podemos empezar cancelando $b$, multiplicando a la izquierda y a la derecha por
ese mismo número número.

$$
\begin{aligned}
    &b\cdot \frac{a}{b} \Big(\frac{a}{b}\Big)^{-1} = 1\cdot b
    \\\ \\\
    &\cancel{b}\cdot\frac{a}{\cancel{b}}\Big(\frac{a}{b}\Big)^{-1} = 1\cdot b
    \\\ \\\
    &a\cdot\Big(\frac{a}{b}\Big)^{-1} = b
\end{aligned}
$$

Bien, ahora tenemos que cancelar $a$, para eso podemos dividir a la izqueirda y
a la derecha.

$$
\begin{aligned}
    &\frac{a\cdot\Big(\frac{a}{b}\Big)^{-1}}{a} = \frac{b}{a}
    \\\ \\\
    &\frac{\cancel{a}\cdot\Big(\frac{a}{b}\Big)^{-1}}{\cancel{a}} = \frac{b}{a}
    \\\ \\\
    &\Big(\frac{a}{b}\Big)^{-1} = \frac{b}{a}
\end{aligned}
$$

Este fue un poco más difícil, pero esta estrategia nos sirve para todos los
números. Probemos encontrar $(\frac{13}{7})^{-1}$

$$
\begin{aligned}
    &\frac{13}{7}\cdot\Big(\frac{13}{7}\Big)^{-1} = 1
    \\\ \\\
    &13\cdot\Big(\frac{13}{7}\Big)^{-1} = 1 \cdot 7
    \\\ \\\
    &\Big(\frac{13}{7}\Big)^{-1} = \frac{7}{13}
\end{aligned}
$$

¿Y para $(\frac{303}{11})$?

$$\Big(\frac{303}{11}\Big)^{-1} = \frac{11}{303}$$

Ya no parece taaan intimidante, ¿verdad?

## ¿Cómo dividir fracciones? 
Volvamos al ejemplo de la multiplicación de fracciones. Si tenemos una tarta y
la partimos a la mitad ---la dividimos por dos--- tendremos media tarta, si
hacemos lo mismo otra vez tendremos un cuarto de tarta. 

$$\frac{\frac{1}{2}}{2} = \frac{1}{4}$$

¡MOMENTO! Esto ya lo habiamos visto, cuando multiplicamos una fracción por otra
fracción, el denominador nos dice cuantas veces hay que partir y el numerador
cuantas partes nos quedamos: ¡dividir $\frac{1}{2}$ entre dos es lo mismo que
multiplicar $\frac{1}{2}\cdot\frac{1}{2}$ !

$$\frac{\frac{1}{2}}{2} = \frac{1}{2}\cdot\frac{1}{2} = \frac{1}{4}$$

Pasa otra cosa muuuy interesante ¿se acuerdan del inverso multiplicativo? ha
vuelto, es más, siempre estuvo ahí y nunca nos dimos cuenta

$$2^{-1} = \frac{1}{2}$$

Por lo tanto, podemos escribir la expresión anterior así

$$\frac{\frac{1}{2}}{2} = \frac{1}{2}\cdot 2^{-1} = \frac{1}{2}\cdot \frac{1}{2}$$

Hemos desbloqueado un poder: dividir. Cómo ya dejamos atrás las muñecas, el
helado y las tartas, avanzaremos con una definción hecha y derecha.

$$\frac{a}{b} = a \cdot b^{-1}$$

Dividir dos números racional es simplemente multiplicar el primero por el
*inverso* del segundo. 

Vamos con otro ejemplo ¿Cuanto es $\frac{17}{7}$ dividido entre $\frac{13}{27}$?
El resultado va a tener números bastante feos, pero no nos asustemos que está
todo perfectamente calculado.

$$
\begin{aligned}
    \frac{\frac{17}{7}}{\frac{13}{27}} = 
    \frac{17}{7} \cdot \Big(\frac{13}{27} \Big)^{-1} =
    \frac{17}{7} \cdot \frac{27}{13}=
    \frac{459}{91}
\end{aligned}
$$

Uno más bonito, ¿Cuanto es $\frac{2}{3}$ dividido $\frac{3}{5}$?

$$
\begin{aligned}
    \frac{\frac{2}{3}}{\frac{3}{5}} = 
    \frac{2}{3} \cdot \frac{5}{3}=
    \frac{10}{9}
\end{aligned}
$$

--------

Hemos llegado al final de esta bella historia, con muñecos rotos, helado y tartas. Falta muchísimo, por ejemplo ¿qué significa simplificar? ¿qué representa la proporcionalidad? ¿QUÉ PASA CON EL CERO Y PORQUÉ NO LE GUSTA A LOS DENOMINADORES?

En futuras entradas veremos todo esto, si necesitas un profe para clases de
apoyo no dudes en llamarme.

mail: nahuelrabeywork@gmail.com
cel:  +54 9 11 3213-4807

Todo esto cuesta tiempo, si te sirvió el apunte y te sobran unas monedas podes
pasarme a este alias danza.biela.bueno.mp

muchas gracias ^_^