---
title: Clase 2
author: Hernan Madrid
date: '2018-05-07'
slug: clase02
categories:
  - Clases
tags:
  - Clases

---

#INTRODUCCIÓN



## R Markdown

Este es un ejercicio del uso de markdown, una herramienta que viene incluida en RStudio y que pernite construir informes en base a los análisis realizados en R. Para mayor información vea: <http://rmarkdown.rstudio.com>.

1.Comando search () permite ver los packages actuales en funcionamiento.

```
search()
```
2.La siguiente función -**library(help=“base”)**- permite explorar y conocer las funciones básicas de R.

```
library(help=“base”) 
```
3.Ejercico básico 


(a) Calcule: $24 * 5 - e^2$

(b) calcule: log(5) + $\frac{phi}{\sqrt{<12>}}$ 


#OBJETOS EN R
Ejercicio: La función **mean()** obtiene el promedio de los datos. Calcule el promedio de 3,4,5,6,7,8.¿Cuál es el resultado?.

**Solución incorrecta**


```r
mean(3,4,5,6,7,8)
```

```
## [1] 3
```

**Solución correcta**, que no olvida que R es un ***lenguaje de programación orientado a objetos***, por ende la secuencia de números debe ser abordada como un *objeto VECTOR*. Para ello se usa la letra "c" seguido de paréntesis. La x es una nueva variable a la cual se le ha asignado el vector, de esa forma después de calcula la media de x, donde está contendio los valores del vector antes construidos.


```r
x=c(3,4,5,6,7,8)
mean(x)
```

```
## [1] 5.5
```

Un objeto es una colección de información indexada, bajo un nombre previamente definido diferenciando mayúsculas de minúsculas. Para asignar un objeto, utilizaremos los símbolos “=”, “->” o “<-”.

Cada asignación puede ir en una fila diferente, o bien seguido de “;”.




## Including Plots

You can also embed plots, for example:

<img src="/post/clase02_files/figure-html/pressure-1.png" width="672" />

```
##      Mobile      Juneau     Phoenix Little Rock Los Angeles  Sacramento 
##        67.0        54.7         7.0        48.5        14.0        17.2
```
Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
