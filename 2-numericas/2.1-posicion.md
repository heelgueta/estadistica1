---
description: Capítulo 2.1 - Medidas de posición para caracterizar distribuciones
icon: map
---

# 2.1 Posición

Cuando observamos una variable numérica, nos interesa mucho más que un simple “promedio”. Ya en capítulos anteriores vimos la media y la mediana como medidas que resumen “dónde están” los datos. Pero la idea de ubicación puede llevarse mucho más lejos. ¿Dónde se ubica un sujeto dentro de la distribución general? ¿Cuánto equivale estar “arriba” o “abajo”? ¿Cómo puedo dividir a un grupo de estudiantes según su desempeño en una prueba sin caer en etiquetas vagas como “bajo, medio, alto”? La estadística tiene una respuesta elegante para esto: los cuantiles.

Este capítulo está dedicado a esas formas de segmentar una variable numérica para identificar posiciones relativas. Comenzaremos con la mediana, pero avanzaremos hacia cuartiles, deciles, percentiles y más. Además, exploraremos una de las visualizaciones más potentes y subestimadas de todo el análisis descriptivo: el boxplot.

***

#### 2.1.1 Mediana y la intuición de “posición”

La mediana es uno de los primeros conceptos que introduce la idea de ubicación. Si ordenamos todos los datos de una variable numérica de forma horizontal de menor a mayor, la mediana es el valor que deja la misma cantidad de observaciones a su izquierda y a su derecha. En ese sentido, al ser el "valor de al medio", ocupa la posición central en la distribución.

Este tipo de resumen es especialmente útil cuando los datos tienen valores extremos o asimetría. A diferencia de la media, la mediana no se ve arrastrada por un par de datos exagerados.

\[Ejemplo: Distribución de sueldos en una empresa donde el CEO gana 80 veces más que los trabajadores. Mostrar media vs mediana.]

***

#### 2.1.2 Cuantiles: dividir para ubicar

La mediana es el cuantil 0.5. Pero podemos generalizar la idea y dividir los datos en más partes. Si los separamos en cuatro partes iguales, obtenemos los **cuartiles**:

* Q1: el 25% de los datos queda debajo.
* Q2: es la mediana.
* Q3: el 75% de los datos queda debajo.

También existen otras divisiones comunes:

* **Deciles**: dividen en 10 partes (D1, D2, ..., D9)
* **Percentiles**: dividen en 100 partes. Muy usados en educación, salud y psicología.

\[Tabla: resumen comparativo entre cuantiles con ejemplos de percentiles en contextos reales, como IMC, puntajes PSU, percentiles de crecimiento infantil.]

Esta segmentación permite construir escalas relativas: saber que alguien está en el percentil 90 nos dice que supera al 90% de los casos en esa variable.

***

#### 2.1.3 El gráfico de cajas y bigotes (boxplot)

El **boxplot** es una herramienta gráfica que condensa mucha información:

* Mediana (línea dentro de la caja)
* Q1 y Q3 (los bordes de la caja)
* Rango intercuartil (Q3 - Q1)
* Bigotes: extensión de los datos sin considerar atípicos
* Valores atípicos: puntos individuales fuera del rango esperado

\[Placeholder: Ilustración de un boxplot con etiquetas explicativas. Mostrar versión clásica y una comparativa entre dos grupos.]

Este gráfico es robusto, compacto y perfecto para comparar distribuciones entre grupos sin depender de supuestos de simetría o normalidad. Además, hace visible la dispersión sin perder el foco en la posición.

***

#### 2.1.4 Rango intercuartil (RIC)

El **rango intercuartil (RIC)** es la diferencia entre el tercer y el primer cuartil: Q3 - Q1. Es una medida de dispersión que acompaña muy bien a la mediana, especialmente en datos no normales.

Su ventaja principal es su **robustez**: ignora completamente los valores extremos. Es decir, se centra en el “corazón” de los datos: el 50% central.

\[Ejemplo: Dos grupos con misma mediana pero diferente RIC. Mostrar cómo uno tiene datos más dispersos, aunque el centro parezca igual.]

***

#### 2.1.5 Otras formas de visualización posicional

Además del boxplot, existen otras visualizaciones útiles:

* **Violin plot**: combina boxplot con una estimación de densidad
* **Strip plot** o **jitter plot**: muestra cada punto, ideal para N bajos

\[Placeholder: Comparativa entre un boxplot y un violin plot sobre puntajes de ansiedad por género. Mostrar cómo el violin revela bimodalidad.]

***

#### 2.1.6 Aplicaciones prácticas

* **Educación**: ubicación en percentiles permite interpretar rendimientos en pruebas estandarizadas sin necesidad de entender la escala original.
* **Salud**: percentiles de crecimiento infantil, IMC, presión arterial.
* **Psicometría**: interpretación de resultados en tests de inteligencia, memoria, etc.

\[Placeholder: Tabla con percentiles típicos usados en psicología clínica infantil.]

***

#### 2.1.7 Consideraciones finales y límites

* Los cuantiles no presuponen normalidad ni simetría.
* Permiten comparaciones entre grupos de forma clara y directa.
* Son resistentes a outliers, pero no muestran la densidad ni la forma completa de la distribución.

Para complementar estas herramientas, necesitamos también saber cuánto varían los datos más allá de su posición. A eso nos dedicaremos en el próximo capítulo.

\[Mini box: “En qué casos no usar boxplots o cuantiles”]

***

**Apartados bonus sugeridos**

* Cómo generar boxplots en distintos software (Excel, R base, ggplot2, jamovi)
* Cómo interpretar percentiles clínicos: ¿estar en el 10% inferior es malo? Depende de qué.
* Comparación de grupos usando boxplots: \[Ejemplo visual con tres grupos simulados: mismo Q2 pero distintos Q1/Q3 y presencia de outliers]

\[Fin capítulo 2.1]
