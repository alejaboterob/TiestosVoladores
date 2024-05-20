---
title: "Del concepto a la realidad: Un recorrido por el proceso de diseño"
date: 2023-07-18T14:29:21+05:30
draft: false
disqus: true
github_link: "https://https://github.com/alejaboterob"
author: "Maria Alejandra Botero Botero"
tags:
  - Diseño
  - Ingeniería de Sistemas
  - Aeroespacial
image: /images/Origami-crane.jpg 
description: "El diseño es una parte fundamental de la ingeniería y del desarrollo de cualquier producto, desde algo tan simple como un objeto de uso cotidiano hasta algo tan complejo como una nave espacial. El diseño aeroespacial, aplicado a misiones espaciales, naves espaciales, satélites, cohetes y vehículos como orbitadores o *rovers*,  requiere un enfoque multidisciplinar que abarca desde la ciencia de los materiales y la propulsión hasta los factores humanos y la seguridad. Sin embargo, el diseño aeroespacial no es muy diferente del diseño de productos, sobre todo en cuanto a los principios y prácticas de diseño y el énfasis en el diseño centrado en el usuario. En esta entrada del blog, abordaremos los procesos de diseño utilizados en el diseño de productos y en el diseño aeroespacial, destacando algunas similitudes entre ambos campos y haciendo énfasis en los términos particulares empleados en el campo aeroespacial."
toc:
---

El diseño es una parte fundamental de la ingeniería y del desarrollo de cualquier producto, desde algo tan simple como un objeto de uso cotidiano hasta algo tan complejo como una nave espacial. El diseño aeroespacial, aplicado a misiones espaciales, naves espaciales, satélites, cohetes y vehículos como orbitadores o *rovers*,  requiere un enfoque multidisciplinar que abarca desde la ciencia de los materiales y la propulsión hasta los factores humanos y la seguridad. Sin embargo, el diseño aeroespacial no es muy diferente del diseño de productos, sobre todo en cuanto a los principios y prácticas de diseño y el énfasis en el diseño centrado en el usuario. En esta entrada del blog, abordaremos los procesos de diseño utilizados en el diseño de productos y en el diseño aeroespacial, destacando algunas similitudes entre ambos campos y haciendo énfasis en los términos particulares empleados en el campo aeroespacial.
## El proceso de diseño

El proceso de diseño típico se ve de la siguiente manera, partiendo de un concepto que se estudia, se desarrolla y continua evolucionando mientras es producido, probado y opera hasta el fin de su ciclo de vida. Esto quiere decir que el diseño generalmente es un proceso iterativo, donde al final de cada etapa se obtiene una versión con características o funcionalidades mejoradas. 

<p align = "center">
<img alt="Proceso de diseño" title="Proceso de diseño" data-src="/blogs/images/diseno_img/1.png" class="cld-responsive" style="padding-bottom: 16px; display: block; margin: auto; {{ $style }}">
</p>

En el campo aeroespacial, el proceso de diseño está enmarcado en la **ingeniería de sistemas** (*Systems Engineering*), no haciendo referencia al pregrado en relación con las tecnologías de la información y la comunicación ofrecido bajo este nombre, sino a lo que NASA define como un enfoque metódico y multidisciplinar para el diseño, desarrollo, operación, mantenimiento y retiro de un sistema. Teniendo en cuenta que un "sistema" es una combinación de elementos que funcionan juntos para producir la capacidad requerida para satisfacer una necesidad. 

En *NASA Systems Engineering Handbook*, se describen las siguientes fases del ciclo de vida de un proyecto:

<p align = "center">
<img alt="" title="Ciclo de vida de un proyecto" data-src="/blogs/images/diseno_img/2.png" class="cld-responsive" style="padding-bottom: 16px; display: block; margin: auto; {{ $style }}">
</p>

## Uso de estructuras desplegables en el campo aeroespacial

En el campo aeroespacial, debido a los costos y restricciones de transporte en los vehículos espaciales o lanzadores, el uso de estructuras desplegables resulta esencial. Estas estructuras permiten reducir el tamaño de las cargas útiles al momento del lanzamiento conservando la funcionalidad de los dispositivos. 

El telescopio espacial JWST, lanzado en diciembre de 2021, es el observatorio científico infrarrojo más grande y complejo que se ha enviado al espacio hasta ahora. Sus componentes principales incluyen un enorme espejo primario para recolectar luz infrarroja, un parasol de gran tamaño para mantener el telescopio frío y cuatro instrumentos científicos para llevar a cabo sus operaciones científicas. Para hacernos una idea de las dimensiones de este gigante telescopio, su espejo principal se eleva a más de dos pisos de altura y, una vez desplegado, su parasol protector mide aproximadamente el tamaño de una cancha de tenis. 

Sin embargo, para poder ser lanzado al espacio debía considerarse el lanzador, un cohete Ariane 5, es por esto que el telescopio se pliega hasta aproximadamente una cuarta parte de su tamaño completo. Una vez en el espacio, fue desplegado gradualmente mientras se dirigía a su órbita.


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

