---
title: Preguntas Frecuentes de IIIF (FAQs)
id: consortium
layout: spec
translation: Spanish
---

## ¿Qué es IIIF?

* IIIF (International Image Interoperability Framework, Marco Internacional de Interoperabilidad de Imágenes) es un conjunto de especificaciones de APIs compartidas que permiten la funcionalidad interoperable en los repositorios de imágenes digitales. IIIF abarca, y es impulsado por, una comunidad de bibliotecas, museos, archivos, compañías de software, y otras organizaciones que trabajan juntas para crear, evaluar, refinar, implementar, y promover las especificaciones de IIIF. Usando JSON-LD, datos enlazados, y protocolos web estándar de W3C como Anotación Web, IIIF facilita parsear y compartir datos de imagen digital, migrar entre sistemas tecnológicos, y ofrecer a académicos e investigadores un mejor acceso a las imágenes. En pocas palabras, IIIF posibilita una entrega de imágenes mejor, más veloz, y más barata. Permite aprovechar la interoperabilidad y la estructura de la Web para acceder a nuevas posibilidades y usuarios para recursos basados en imagen, al tiempo que reduce el mantenimiento a largo plazo y el bloqueo tecnológico. IIIF proporciona a los usuarios un rico conjunto de funcionalidades básicas para visualizar, enfocar, y reunir la mejor combinación de recursos y herramientas para ver, comparar, manipular, y trabajar con imágenes en la Web, en una experiencia portable–compartible, citable, e incrustable.

## ¿Cuáles son los beneficios de IIIF?

IIIF permite:

 * Funcionalidad interactiva avanzada para los usuarios finales
    * Entrega zoom y pan de imágenes rápida y enriquecida.
    * Manipulation of size, scale, region of interest, rotation, quality and format.
    * Anotación: IIIF es compatible nativamente con el [Modelo de Datos Anotación Web][wadm] del grupo de trabajo de anotación de W3C, que soporta anotar contenido en la Web. Los usuarios pueden comentar en, transcribir, y dibujar sobre, recursos basados en imágenes empleando la arquitectura inherente de la Web.
    * Reunir y utilizar recursos basados en imagen de la Web, con independencia de la fuente. Compare páginas, construya una exposición, o visualice una colección virtual de elementos servidos desde diferentes sitios.
    * Citar y Compartir: Las APIs de IIIF motivan la persistencia, proporcionando vistas portables de imágenes y/o regiones de imágenes. Cite una imagen con confianza en URIs de imagen estables, o compártala para que la referencien otros (o usted mismo en un entorno distinto).
 * Soporte de autenticación institucional
    * IIIF está diseñado para soportar control de acceso y puede aprovechar los sistemas SSO (single sign on, inicio de sesión único) existentes, a través de la [API de Autenticación de IIIF][auth]
 * Flexibilidad del sistema
   * Use cualquier software compatible con IIIF para visualizar, comparar, y manipular imágenes, con independencia del servidor backend. Intercambie partes de la pila en cualquier momento, o ejecute múltiples componentes a la vez, en paralelo.
 * Facilidad de transferir y compartir datos
    * IIIF está basado en estándares, emplea construcción RESTful de las APIs, JSON-LD, y cumple los patrones Web, simplificando los procesos de migrar y compartir datos.
 * Se evitan la dependencia de un proveedor, las migraciones complicadas, y los repasos generales del sistema
    * IIIF proporciona la capacidad de separar las interfaces de usuario de entrega de imágenes de los almacenes backend, lo cual permite que los repositorios actualicen los servidores de imagen y las bases de datos sin alterar la entrega frontend o, vice versa, evita el rediseño de la arquitectura de toda la pila. Con una comunidad activa y creciente de organizaciones que desarrollan y soportan las tecnologías compatibles con IIIF, existen numerosas opciones de software para elegir.
 * Reducción de los costos totales a largo plazo
    * Un rico ecosistema de software interoperable, que incluye muchas opciones de alta calidad y código abierto, mantiene los costos de operación y de licencias bajos y predecibles a largo plazo.
 * Se combinan contenidos de diversos repositorios
    * Unifique la presentación de contenidos desde muchos almacenes distintos (dentro o fuera de su institución) sin migraciones de sistema o datos complejas o costosas. Combine contenidos de su DAM (digital asset management, sistema de gestión de activos digitales) institucional, colecciones de bibliotecas digitales, y recursos externos.
 * Publique una vez, reutilice muchas veces
    * Entregue imágenes desde su propio sitio para usos variados; aloje una sola copia e incruste en otros sitios. No es preciso transferir las imágenes a otros para que estos las carguen localmente con fines de análisis o republicación.
 * Una próspera red global
    * Únase a una red global de proveedores de imágenes que presentan el contenido en un marco común, interoperable. Aproveche una suite en crecimiento de herramientas de software y plataformas. Maximice la utilización de sus imágenes en la Web. Descubra nuevo potencial con la interoperabilidad.

## ¿Quién es parte de la comunidad IIIF?

* La Comunidad IIIF abarca un grupo grande, y en crecimiento, de individuos y organizaciones interesados y activos dedicados a liderar y sostener IIIF. Como iniciativa impulsada por la comunidad, IIIF se beneficia de la discusión activa, los aportes, y los comentarios de numerosos y diversos individuos pertenecientes a bibliotecas, museos, instituciones de patrimonio cultural, firmas de software, y otras organizaciones que trabajan con imágenes digitales y materiales audiovisuales. Agradecemos a cualquier organización o individuo interesado en adoptar IIIF, desarrollar software para soportarlo, o comentar sobre el esfuerzo para participar. Los participantes de toda actividad de IIIF deben cumplir el [código de conducta][conduct] de IIIF. La [lista de participantes conocidos de la comunidad IIIF][community-list] crece constantemente. Adicionalmente, el Consorcio IIIF (IIIF Consortium, IIIF-C) aporta sostenibilidad y dirección a la iniciativa. Para mayor información sobre IIIF-C, vea la [página del Consorcio][iiif-c] y las [Preguntas Frecuentes de IIIF-C][iiifc-faq].

## ¿Cómo puedo participar en la Comunidad IIIF?

* Por favor, vea la [página de la Comunidad IIIF][community-list] para los detalles sobre como participar.

## ¿Cuáles son las especificaciones actuales de IIIF?

 * [API de Imagen][image]
 * [API de Presentación][presentation]
 * [API de Búsqueda de Contenido][search]
 * [API de Autenticación][auth]
 * En Progreso: [IIIF para Materiales Audiovisuales][av]

##  ¿Cómo se relacionan las APIs de IIIF con mi capa de interoperabilidad interna actual?

* Algunas instituciones implementan IIIF usando shims, o capas de traducción, encima de sus capas de interoperabilidad existentes. En otros casos, IIIF se implementa sin depender de los servicios existentes. IIIF permite distintos niveles de cumplimiento, empezando por la API de Imagen de IIIF. Para más información, por favor, vea los [detalles técnicos de IIIF][tech-details].  

## IIIF reemplaza o se integra a mi software de Gestión de Activos Digitales (Digital Asset Management, DAM)?

* IIIF es un método de entrega de activos, no de almacenamiento. La integración a su software DAM depende de su proveedor de DAM. La comunidad IIIF alienta a los proveedores de software DAM a incorporar soporte nativo de IIIF en sus productos.

## ¿El Consorcio IIIF sirve como agregador de contenido IIIF?

* No, el Consorcio IIIF y la comunidad no tienen una plataforma de agregación única para el contenido. IIIF define APIs que posibilitan la interoperabilidad entre repositorios de imágenes digitales, incluyendo agregadores. Como las APIs de IIIF están bien documentadas y comprendidas, el uso de IIIF puede facilitar el acceso a sus imágenes de agregadores como Artstor, DPLA, y Europeana.

[search]: {{ page.webprefix }}/api/search/
[presentation]: {{ page.webprefix }}/api/presentation/
[image]: {{ page.webprefix }}/api/image/
[apps-demos]: {{ site.url }}{{ site.baseurl }}/apps-demos
[iiifc-faq]: {{ site.url }}{{ site.baseurl }}/community/consortium/faq
[iiif-c]: {{ site.url }}{{ site.baseurl }}/community/consortium
[community-list]: {{ site.url }}{{ site.baseurl }}/community/
[auth]: {{ page.webprefix }}/api/auth/
[wadm]: https://www.w3.org/TR/2017/REC-annotation-model-20170223/
[conduct]: {{ site.url }}{{ site.baseurl }}/event/conduct/
[av]: {{ site.url }}{{ site.baseurl }}/community/groups/av/
[tech-details]: {{ site.url }}{{ site.baseurl }}/technical-details/
