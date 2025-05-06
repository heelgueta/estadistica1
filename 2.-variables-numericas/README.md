---
description: >-
  Técnicas para describir con mayor detalle el comportamiento de variables
  numéricas.
icon: dice
---

# Sección 2

Hasta ahora hemos aprendido algunas estrategias básicas para explorar datos, incluyendo tablas de frecuencia, gráficos de barras e histogramas, y medidas de tendencia central como la media o la mediana. Estas herramientas nos han permitido dar un primer vistazo a nuestros datos y detectar patrones generales. Sin embargo, cuando nos enfrentamos a variables numéricas, los desafíos se vuelven más complejos. No basta con saber "cuánto hay" de algo o dónde está el promedio; necesitamos formas más precisas de describir cómo se distribuyen los valores, cuánto varían, y cómo se pueden comparar entre diferentes contextos.

En esta sección nos enfocaremos en tres herramientas clave para trabajar con variables numéricas: medidas de posición (como cuartiles y percentiles), medidas de dispersión (como la desviación típica), y transformaciones como la estandarización de puntajes. Cada una de estas herramientas responde a una necesidad distinta, pero juntas permiten una comprensión más fina y matizada de los datos numéricos. También discutiremos cuándo estas herramientas funcionan bien y cuándo pueden resultar engañosas, en función de la forma de la distribución o del contexto.

Este recorrido también sirve como puente hacia el análisis bivariante, donde ya no nos enfocaremos en una sola variable, sino en las relaciones entre ellas. Pero antes de llegar allá, necesitamos dominar estas herramientas univariantes con un poco más de detalle.

***

**2.1 Posición**

Cuando trabajamos con distribuciones que no son perfectamente simétricas, vimos que la mediana puede ser una mejor medida de centro que la media. La mediana es en sí misma una medida de posición, que divide la distribución en dos mitades. Pero podemos generalizar esta idea segmentando los datos en más partes iguales: cuartiles (4 partes), quintiles (5), deciles (10), percentiles (100), etc. A estas divisiones las llamamos cuantiles, y nos permiten caracterizar con mayor detalle la posición relativa de los sujetos.

Nos enfocaremos especialmente en los cuartiles y en el uso del boxplot (o "diagrama de cajas y bigotes") como una herramienta visual poderosa para representar esta información. Este gráfico no solo muestra la mediana y los cuartiles, sino que también permite detectar posibles valores atípicos y comparar distribuciones entre grupos.

También introduciremos la nocion de rango intercuartil (RIC) como una forma robusta de estimar la dispersión, especialmente cuando los datos presentan asimetría o valores extremos. Cerraremos esta sección con una descripción de los percentiles y algunas consideraciones sobre su aplicación práctica en contextos como educación y salud.

***

**2.2 Dispersión**

La variabilidad es una característica clave de los datos. Saber cuál es el valor típico no es suficiente si no sabemos cuánto se alejan los datos de ese valor. Presentaremos otra herramienta fundamental: la desviación típica.

La desviación típica (o desviación estándar) nos permite cuantificar, en la misma unidad de la variable, cuánto tienden a alejarse los datos de su media. Para llegar a ella construiremos paso a paso la fórmula, entendiendo cómo se relaciona con el concepto de distancia al centro . Discutiremos también su utilidad y sus limitaciones. Recordaremos los conceptos de simetría y curtosis como descriptores de la forma de la distribución.

***

**2.3 Estandarización**

Cuando queremos comparar valores provenientes de distintas variables o de sujetos en distintos contextos, necesitamos llevar esos valores a una escala común. Ahí entra la estandarización. Comenzaremos explorando la distribución normal como modelo que resume cómo se comportan muchas variables en poblaciones grandes, y desde allí introduciremos los puntajes z.

Un puntaje z indica cuántas desviaciones estándar separan un valor de la media. Esta transformación nos permite comparar sujetos entre sí, estimar percentiles, y pensar en lo "esperable" y lo "no esperable" dentro de una distribución. También exploraremos otras transformaciones como puntajes T, y ejercicios para convertir entre bruto, z y percentil. Cerraremos con algunas aplicaciones prácticas de estos conceptos, incluyendo ejemplos de salud y educación, y una breve discusión sobre cómo estas ideas se vinculan con el pensamiento inferencial.
