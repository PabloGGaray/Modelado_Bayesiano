# Prefacio

La estadística trata sobre la recolección, organización, análisis e interpretación de datos, es por ello que la estadística es esencial para el correcto análisis de datos. 

Existen dos grandes conjuntos de herramientas para analizar datos:

**Análisis Exploratorio de Datos (EDA)**: Consiste en resúmenes numéricos como la media, moda, desviación estándar, rangos intercuartiles, etc (esto se conoce también como estadística descriptiva). Además hace énfasis en el uso de métodos visuales para inspeccionar los datos, como por ejemplo histogramas y gráficos de dispersión.

**Estadística Inferencial**: Consiste en usar datos para generar enunciados que exceden los propios datos. A veces esto implica realizar predicciones, a veces entender los detalles de algún fenómeno en particular o elegir entre varias explicaciones plausibles.

> Este curso es sobre inferencia Bayesiana, pero como verán hacemos uso de métodos parcialmente inspirados en el análisis exploratorio de datos para resumir, interpretar, evaluar y comunicar los resultados de tales inferencias.

Muchos de los cursos y libros sobre estadística, principalmente aquellos dirigidos a no-estadísticos, enseñan una serie de recetas que más o menos tienen la siguiente forma. 

1. Diríjase a la alacena estadística
2. Elija una lata y ábrala
3. Agregue datos a gusto
4. Revuelva hasta que los p-valores estén a punto

La principal meta de estos cursos es la de enseñar a usar la lata adecuada y con suerte alguna que otra discusión sobre el _emplatado_. Esta aproximación pedagógica, dificulta entender conceptualmente la unidad de los diferentes métodos enseñados y tiene como resultado la reproducción de prácticas poco transparentes y/o útiles. 

En este curso se intenta una aproximación totalmente diferente. También aprenderemos recetas, pero intentaremos que los platos tengan un sabor más casero y menos enlatado, aprenderemos a mezclar ingredientes frescos que se acomoden a diferentes situaciones gastronómicas.

Este enfoque es posible por dos razones:

* Una es ontológica: La estadística es una forma de modelado unificada bajo el marco de la teoría de probabilidad.
* La otra es técnica: Software moderno permite a los practicantes definir, resolver y analizar modelos de forma cada vez más sencilla.

## A quienes está dirijido?

Este es un curso introductorio para personas sin conocimiento previo de estadística o ciencia de datos. Se asume familiaridad con Python y librerías de Python usadas en análisis de datos como Numpy, matplotlib, Pandas, etc.

Quienes no sepan Python, pero tengan familiaridad con otros lenguajes de programación también podrán aprovechar el curso, aunque puede que experimente un poco más de fricción.

Por último quienes no tengan interés en aprender a usar código para analisis de datos pueden aún aprovechar parte del material para obtener una visión a vuelo de pájaro de los métodos Bayesianos.

## Cómo usar este material

* Versión estática: Al hacer click en los archivos que se muestran arriba (los que terminan en ipynb) podrás leer una versión estática del material. Es decir podrás ver el texto y las figuras pero no podrás modificarlos, ni interactuar con el material.

* Versión interactiva online [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Grupo-de-modelado-probabilista/Modelado_Bayesiano/main).

* Versión interactiva local. También es posible descargar el material y ejecutarlo en tu propia computadora. Para ello hacé click [acá](https://github.com/Grupo-de-modelado-probabilista/Modelado_Bayesiano/archive/main.zip) y sigue las instrucciones de la próxima sección (Instalación).


## Instalación
Para usar este material es necesario tener instalado Python. Se recomienda la versión 3.9 o superior. Además es necesario instalar los siguientes paquetes:

* PyMC 5.3.0
* ArviZ 0.15.1
* Preliz 0.3.0

Se recomienda instalar primero [Anaconda](https://www.continuum.io/downloads). Luego instalar el resto de los paquetes con los comandos:

* `conda install -c conda-forge pymc arviz`

## Contribuciones
Todo el contenido de este repositorio es abierto, esto quiere decir que cualquier persona interesada puede contribuir al mismo. Todas las contribuciones serán bien recibidas incluyendo:

* Correcciones ortográficas
* Nuevas figuras
* Correcciones en el código Python, incluidas mejoras de estilo
* Mejores ejemplos
* Mejores explicaciones 
* Correcciones de errores conceptuales

La forma de contribuir es vía Github, es decir los cambios deberán ser hechos en forma de _pull requests_ y los problemas/bugs deberán reportarse como _Issues_.

