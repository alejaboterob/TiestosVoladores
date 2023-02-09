---
title: "¿Cómo empecé mi propio blog?"
date: 2023-01-23T23:29:21+05:30
draft: false
disqus: true
github_link: "https://https://github.com/alejaboterob"
author: "Maria Alejandra Botero Botero"
tags:
  - Blog
  - Netlify
image: /images/post.jpg
description: "¿Cómo empecé mi propio blog con Netlify?"
toc:
---

# ¿Cómo empecé mi propio blog?

Si estás buscando una señal para empezar tu propio blog y compartir con tu yo del futuro o con el mundo algunos aprendizajes, experiencias y opiniones, aquí la tienes. 

Desde hace mucho quería empezar mi propio blog pero por otros proyectos nunca había dado tan siquiera el primer paso. Hace poco [Nicolás Guarín](https://nicoguaro.github.io/pages/about/) me convenció con un artículo,  “*inicia un p**o blog: Vamos, hazlo ahora mismo, es lo mejor que puedes hacer en la web”.*

>🔗 [Start a Fucking Blog](https://startafuckingblog.com)
>Go on, do it right fucking now - it's the best thing on the web you can do.


Gracias a esta página conocí [Netlify](https://netlify.com/), una plataforma gratuita desarrollada para alojar y administrar aplicaciones web que incluye dominios personalizados y funciona bastante bien para proyectos personales y sitios web estáticos como blogs, galerías de imágenes, portafolios, entre otros.

## ¿Cómo empecé mi propio blog desde cero?

 
Primero, busqué una plantilla libre que me permitiera empezar fácilmente. En [jamstackthemes](https://jamstackthemes.dev/) puedes encontrar muchas opciones.

[Jamstack Themes](https://jamstackthemes.dev/)

Yo elegí [hugo-profile](https://hugo-profile.netlify.app/) dado que tiene modo claro y oscuro, etiquetas para mis entradas del blog, buscador y un diseño minimalista, limpio y *responsive*. Cloné el repositorio en mi GitHub y luego de crear una cuenta en [Netlify](https://netlify.com/), conecté mi cuenta de GitHub para elegir el repositorio y configurar mi nuevo blog. Cambié el nombre del sitio para tener mi url personalizada y personalicé la plantilla a mi gusto. 

![Untitled](/blogs/images/Untitled.png)

[Netlify](https://netlify.com/) toma los cambios del repositorio de Github y los aplica automáticamente a mi blog, así que cada vez que hago un commit y push en mi repositorio, los cambios se muestran en mi sitio. Esto hace que sea muy sencillo administrar mi blog.

![Untitled](/blogs/images/Untitled%201.png)

Otra opción es empezar con una plantilla directamente desde [Netlify](https://netlify.com/). 

Ahora, con estos sencillos pasos tengo un blog en la web listo para comenzar a escribir sobre cosas que me apasionan como los tiestos voladores 🚀 ✈️.

## ¿Cómo personalicé mi blog?

Para continuar personalizando mi blog, desde GitHub abrí mi repositorio con GitHub Desktop y luego con un editor de código, como Visual Studio Code, empecé a configurar toda la página. Primero, en exampleSite edité el archivo config.yaml. 

![Untitled](/blogs/images/Untitled%202.png)

### Agregando comentarios y reacciones a mis artículos

Para agregar comentarios y reacciones a las entradas de blog utilicé [Disqus](https://disqus.com/), creé una cuenta y elegí el plan básico gratuito,  la configure en mi sitio y busqué el short name. En config.yaml agregué mi usuario en la línea disqusShortname y agregué el siguiente código.

![Untitled](/blogs/images/Untitled%203.png)

En config.yaml agregué mi Shortname en la línea ***disqusShortname:***.

Para configurar Disqus, agregué  en ***exampleSite/layouts/_default/single.html*** el código que se encuentra en Disqus al configurar el sitio,  luego de la línea  ***{{ template "_internal/disqus.html" . }}*** 

![Untitled](/blogs/images/Untitled%204.png)

### Agregando Google Analytics

Agregué el Id de medición de Google Analytics en la línea ***googleAnalytics: G-MEASUREMENT_ID***, luego de [configurar Analytics en un sitio web](https://support.google.com/analytics/answer/9304153?hl=es/&visit_id=638100275137119050-2188285274&rd=1).

En el archivo ***exampleSite/layouts/partials/head.html*** remplacé  {{ template "_internal/google_analytics.html"}} por el código suministrado por Google Analytics en la pestaña ***Instale la etiqueta de Google manualmente.*** 

## ¿Cómo agrego entradas a mi blog?

En la carpeta ***exampleSite/content/blogs*** agrego un archivo ***nombre.md***, un documento de texto simple, en el que mediante símbolos en el texto se define el formato de ciertas secciones. Los archivos **.*md*** están escritos en lenguajes de desarrollo Markdown, que pertenecen a los lenguajes *markup* o de marcado.  Estos archivos **.*md*** pueden abrir y editarse con cualquier editor de texto. Yo escribo mis entradas de blog en Notion y puedo exportarlas en formato Markdown. En Visual Studio Code también puedes editar estos archivos y visualizarlos, como se muestra [en este tutorial](https://medium.com/@felixmoreno_26363/c%C3%B3mo-previsualizar-cambios-en-tu-archivo-markdown-4e4c4419c7d7).  

El inicio del archivo siempre se ve como las siguientes líneas:

```markdown
---
title: "Mi título"
date: 2023-01-23T23:29:21+05:30
draft: false 
disqus: true
author: "Maria Alejandra Botero Botero"
tags:
  - Blog
  - Netlify
  - 
image: /images/post.jpg
description: ""
toc:
---
```

Aquí personalizo el título, autor, fecha y las etiquetas o *tags*. Además, agrego una imagen a la entrada de blog y elijo si es un borrador (*draft: true*) o una versión final (*draft: false*).

Una vez tengo listo mi archivo ***.md*** completo, solo es darle click en *commit* en GitHub y hacer *push*. Y así tengo una nueva entrada en mi blog.