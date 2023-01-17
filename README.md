# Primera entrega: Análisis de datos con Python

> ## Temática: Causas de muerte en el mundo y en Argentina

* 1. Motivación y audiencia
* 2. Objetivo
* 3. Preguntas e hipótesis
* 4. Contexto analítico
* 5. Análisis Exploratorio de Datos (EDA)
* 6. Recomendaciones Preliminares a partir del EDA
* 7. Evaluando modelos de Machine Learning

## 1. Motivación y audiencia

El estudio de la Salud Pública es uno de los temas que nos interesaba investigar. En la búsqueda de datasets relacionados con este área encontramos varios posibles conjuntos de datos que en general trataban sobre diversos aspectos ligados a la salud en el mundo. Sin embargo, en muchos casos, al observar más detenidamente el contenido de dichos datasets encontrabamos diversos problemas, sea por el tamaño de la muestra, la falta de claridad en las variables, la cantidad de celdas nulas (sin datos), entre otros inconvenientes. En el caso del dataset elegido, contamos con una muestra interesante, que abarca no sólo a todos los países sino que además con datos anuales cubriendo un período de 30 años. Por otro lado, los valores de las variables son fácilmente interpretables, en tanto refieren a cantidades (números enteros). De esta forma podemos, por ejemplo, preguntarnos: ¿Cuántas personas fallecieron en Afghanistan en el año 1993 por Malaria? Siendo la respuesta "108". Son datos simples, pero cuando los análizamos en su evolución a los largo de 30 años, comparando las variables entre sí, y en relación a otros países, o a los valores mundiales, cobran un interés significativo.

Respecto a quiénes podrían estar dirigidos los insights obtenidos de este análisis, consideramos que la audiencia principal podría tratarse de organizaciones gubernamentales, ya que son éstas las dedicadas a la promoción y la prevención en el ámbito de la salud, y serían éstas las que podrían utilizar esta información para tomar decisiones sobre cómo abordar problemas de salud a nivel local, provincial o nacional.

## 2. Objetivo

El objetivo de este análisis podría ser el de comprender mejor las tendencias y patrones en las causas de muerte a nivel global y cómo estos pueden variar entre diferentes grupos, sean países, continentes o segmentos geo-políticos específicos. Se podrían responder preguntas sobre las causas de muerte más comunes, cómo han cambiado a lo largo del tiempo, y cómo pueden variar dependiendo del recorte poblacional que hagamos. 

Teniendo en cuenta la audiencia a la que irían dirigidos nuestros resultados, el objetivo también podría ser el de utilizar los datos para identificar prioridades y objetivos de salud pública, a fin de que las organizaciones gubernamentales puedan tomar medidas efectivas para mejorar la salud y prevenir enfermedades u otros factores de riesgo.

## 3. Preguntas e hipótesis

En este dataset encontramos el número de muertes a nivel mundial, dividido por causa, por país y por año, desde el 1990 hasta el 2019. Se trata de diversas causas de muerte, que en principio no tendrían relación, ya que van desde aspectos psico-sociales hasta aspectos hereditarios o accidentales, aunque bajo un análisis más detenido podrían develar correlaciones.
Resultaría interesante hacer dos tipos de análisis, por un lado, a nivel mundial, cómo fluctúan los datos, buscando indicadores significativos; por otro lado, analizar los datos agrupando países según algún criterio, como por ejemplo "países de América del Sur", o tomar algún país en particular, como por ejemplo Argentina, y analizar sus cambios a través del tiempo, qué particularidades se destacan, y buscar correlaciones en los datos.
Además, pordíamos hipotetizar que algunas de las "causas" relacionadas a niveles de desarrollo de los países, como por ejemplo la muerte por malaria o por deficiencias nutricionales, podrían mostrar una correlación negativa con algunas variables como la muerte por enfermedades ligadas a la edad avanzada, como el Alzheimer.  En este sentido, sería interesante buscar entre todas las variables tanto las correlaciones positivas como las negativas.
En resumen:
* ¿Cuáles son los indicadores más significativos?
* ¿Qué correlaciones se observan, tanto positivas como negativas?
* ¿Qué cambios se observan en la distribución a lo largo de los años?
* ¿Se observa algún punto de quiebre en la distribución temporal?
* A partir de los casi 30 años de la muestra, ¿qué se podría predecir sobre la evolución de las variables a futuro?
* Interesa evaluar el comportamiento de variables ligadas a aspectos psico-sociales (interpersonal violence, self-harm, drug use disorders), así como variables ligadas a lo accidental (road injuries, drownings).
* En terminos generales interesa agrupar todas las variables según su "tipo", para evaluar resultados generales y correlaciones, para luego comparar los resultados por "tipo".

En cuanto a las posibles hipótesis:
* Habrá a lo largo de los años un descenso de las muertes ligadas al subdesarrollo de los países, como por ejemplo, la muerte por malaria o por deficiencias nutricionales.
* Habrá a lo largo de los años un aumento de las muertes por neoplasma (tumores) y por enfermedades ligadas a la edad avanzada (Alzheimer), así como también en las variables ligadas a aspectos psico-sociales (autolesión). 
* Es decir, habrá una correlación negativa entre las variables ligadas a niveles de desarrollo de los países, y variables ligadas a la edad avanzada o a aspectos psico-sociales.

## 4. Contexto analítico

> ### Dataset: "Cause of Deaths around the World (Historical Data)"
> #### [Este Dataset contiene datos históricos sobre causas de muertes en el mundo]
> #### Fuente: https://www.kaggle.com/datasets/iamsouravbanerjee/cause-of-deaths-around-the-world

## -> Para continuar con el análisis ir a los archivos en la carpeta "notebooks" 
