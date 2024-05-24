---
title: "El arte de doblar papel: Una fuente de inspiración para el diseño de estructuras aeroespaciales "
date: 2023-02-16T14:29:21+05:30
draft: false
disqus: true
github_link: "https://https://github.com/alejaboterob"
author: "Maria Alejandra Botero Botero"
tags:
  - Origami
  - Estructuras
  - Mecánica computacional
  - Proyectos
  - Aeroespacial
  - Proyecto Mecánica Clásica

image: /images/Origami-crane.jpg 
description: "El origami o el arte de doblar papel para convertirlo en diversos objetos tridimensionales, que van desde aviones de papel hasta animales, ha servido como fuente de inspiración para el diseño de estructuras cada vez más compactas y versátiles. Recientemente el entendimiento del origami desde modelos matemáticos y el interés creciente por el diseño asistido por computador han permitido la creación, el análisis y la simulación de estructuras desplegables.

En este artículo, se presentará el proyecto **Análisis y Diseño de Estructuras Desplegables Basadas en Origami**. El objetivo de este proyecto es desarrollar métodos para diseñar y analizar estructuras desplegables de tipo origami, principalmente para aplicaciones aeroespaciales."
toc:
---

El origami o el arte de doblar papel para convertirlo en diversos objetos tridimensionales, que van desde aviones de papel hasta animales, ha servido como fuente de inspiración para el diseño de estructuras cada vez más compactas y versátiles. Recientemente el entendimiento del origami desde modelos matemáticos y el interés creciente por el diseño asistido por computador han permitido la creación, el análisis y la simulación de estructuras desplegables.

En este artículo, se presentará el proyecto **Análisis y Diseño de Estructuras Desplegables Basadas en Origami**. El objetivo de este proyecto es desarrollar métodos para diseñar y analizar estructuras desplegables de tipo origami, principalmente para aplicaciones aeroespaciales.

## ¿Qué son las estructras desplegables?

Las estructuras desplegables son aquellas que pueden cambiar su configuración de manera significativa. Normalmente, pasan de un estado plegado y compacto a uno grande y desplegado (Tibert 2002). El origami se ha utilizado para diseñar estructuras de tamaño reducido, lo que facilita el transporte y montaje de productos voluminosos. Esta técnica de doblado de papel, también conocida como papiroflexia, se está implementando cada vez más en diversos ámbitos, como aplicaciones aeroespaciales, refugios, estructuras de rescate, instalaciones lúdicas, dispositivos médicos, entre otros.

## Uso de estructuras desplegables en el campo aeroespacial

En el campo aeroespacial, debido a los costos y restricciones de transporte en los vehículos espaciales o lanzadores, el uso de estructuras desplegables resulta esencial. Estas estructuras permiten reducir el tamaño de las cargas útiles al momento del lanzamiento conservando la funcionalidad de los dispositivos. 

El telescopio espacial JWST, lanzado en diciembre de 2021, es el observatorio científico infrarrojo más grande y complejo que se ha enviado al espacio hasta ahora. Sus componentes principales incluyen un enorme espejo primario para recolectar luz infrarroja, un parasol de gran tamaño para mantener el telescopio frío y cuatro instrumentos científicos para llevar a cabo sus operaciones científicas. Para hacernos una idea de las dimensiones de este gigante telescopio, su espejo principal se eleva a más de dos pisos de altura y, una vez desplegado, su parasol protector mide aproximadamente el tamaño de una cancha de tenis. 

Sin embargo, para poder ser lanzado al espacio debía considerarse el lanzador, un cohete Ariane 5, es por esto que el telescopio se pliega hasta aproximadamente una cuarta parte de su tamaño completo. Una vez en el espacio, fue desplegado gradualmente mientras se dirigía a su órbita.

<p align = "center">
<img alt="Dimensiones telescopio JWST" title="Dimensiones telescopio JWST" data-src="/blogs/images/JWST.png" class="cld-responsive" style="padding-bottom: 16px; display: block; margin: auto; {{ $style }}">
</p>
<p align = "center">
Dimensiones telescopio JWST. Fuente: NASA/JPL-Caltech
</p>

<p align = "center">
<img alt="Telescopio JWST plegado y ubicado en el Ariane 5" title="Telescopio JWST plegado y ubicado en el Ariane 5" data-src="/blogs/images/ariane.jpg" class="cld-responsive" style="padding-bottom: 16px; display: block; margin: auto; height:500px; {{ $style }}">
</p>
<p align = "center">
Telescopio JWST plegado y ubicado en el Ariane 5. Fuente: NASA
</p>

## Retos de las estructuras desplegables

Aunque las estructuras basadas en origami tienen muchas ventajas, como su facilidad de transporte y almacenamiento, también existen varios desafíos asociados con su uso. Estas estructuras son complejas, dado que poseen partes móviles y actuadores, que deben plegarse y desplegarse según la configuración deseada, garantizando una alta fiabilidad en la geometría final y la funcionalidad de la estructura. El análisis y la simulación computacional se convierten en una herramienta importante que permite visualizar y probar su comportamiento para que dichas estructuras puedan ser utilizadas exitosamente en el espacio. 


## Análisis y diseño de estructuras desplegables basadas en origami

En este proyecto se busca desarrollar métodos para diseñar y analizar estructuras desplegables tipo origami, principalmente para aplicaciones aeroespaciales. Para ello, se realizará una revisión del estado del arte respecto a la modelación de estructuras desplegables tipo origami. Además, se implementarán algoritmos que permitan analizar estructuras desplegables tipo origami en programas de software libre disponibles. Finalmente, se evaluarán las capacidades de simulación de los métodos desarrollados a través de una prueba de concepto experimental.

Para este proyecto se trabaja de la mano de la Fundación Cydonia, dedicada al desarrollo aeroespacial en Colombia. Esta fundación es la responsable del diseño, construcción y operación del Hábitat Análogo de Exploración Espacial Simulada en Colombia (HAdEES-C), primer hábitat de simulación para misiones análogas construido en Colombia. Sus instalaciones permiten simular algunas de las condiciones de Marte o la Luna acá en la Tierra, y probar aspectos relacionados con los viajes espaciales tripulados y la exploración planetaria. 

## Referencias

Tibert, Gunnar. 2002. “Deployable tensegrity structures for space applications”. PhD Thesis, KTH.

