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
    * Assemble and use image-based resources from across the Web, regardless of source. Compare pages, build an exhibit, or view a virtual collection of items served from different sites.
    * Cite and Share - IIIF APIs provide motivation for persistence, providing portable views of images and/or regions of images. Cite an image with confidence in stable image URIs, or share it for reference by others--or yourself in a different environment.
 * Support for institutional authentication
    * IIIF is designed to support access control and can leverage existing SSO systems, via the [IIIF Authentication API][auth]
 * System flexibility
   * Use any IIIF-compatible software for viewing, comparing and manipulating images, regardless of the back-end server. Swap parts of the stack at any time, or run multiple components in parallel at once.
 * Easy data transfer and sharing
    * IIIF is standards-based, uses RESTful API construction, JSON-LD, and follows Web patterns, simplifying processes for data migration and sharing
 * Avoidance of vendor lock-in, complicated migrations, and system overhauls
    * IIIF provides the ability to separate image delivery user interfaces from back end data stores, allowing repositories the ability to update image servers and databases without changing front end delivery, or vice versa, avoiding the need to re-architect the entire stack. With an active and growing community of organizations developing and supporting IIIF-compatible technologies, there are plenty of software options to choose from.
 * Reduction of long term total costs
    * A rich ecosystem of interoperable software, including many high quality, open source options, keeps licensing and operational costs low and predictable over time.
 * Combining content from across repositories
    * Unify presentation of content from many different stores (within or outside your institution) without complex or expensive system or data migrations. Bring together content from your institutional DAM, library digital collections, and external sources.
 * Publish once, re-use often
    * Deliver images from your own site for manifold uses; host a single copy and embed in other sites. No need to transfer images to others for them to locally load for one off analysis or republishing.  
 * A thriving global network
    * Join a global network of image suppliers making content available in a common , interoperable framework. Tap a growing suite of software tools and platforms. Maximize the use of your images on the Web. Unlock new potential with interoperability.

## Who is part of the IIIF community?

* The IIIF Community encompasses a large and growing group of interested and active individuals and organizations dedicated to leading and sustaining the IIIF. As a community-driven initiative, IIIF thrives on active discussion, input, and feedback from a wide array of diverse individuals from libraries, museums, cultural heritage institutions, software firms, and other organizations working with digital images and audio/visual materials. We welcome any organization or individual interested in adopting the IIIF, developing software to support it, or giving feedback on the effort to get involved. Participants in all IIIF activities are expected to follow the IIIF [code of conduct][conduct]. The [list of known IIIF community participants][community-list] is always growing. Additionally, the IIIF Consortium (IIIF-C) provides sustainability and steering for the initiative. For more information about the IIIF-C, see the [Consortium page][iiif-c] and [IIIF-C FAQ][iiifc-faq].

## How can I participate in the IIIF Community?

* Please see the [IIIF Community page][community-list] for details on how to get involved.

## What are the current IIIF specifications?

 * [Image API][image]
 * [Presentation API][presentation]
 * [Content Search API][search]
 * [Authentication API][auth]
 * In Progress: [IIIF for Audio/Visual materials][av]

##  How do the IIIF APIs relate to my current, internal interoperability layer?

* Some institutions implement IIIF using shims, or translation layers, on top of their existing interoperability layer.  In other cases, IIIF is implemented without dependencies on existing services. IIIF provides for different levels of compliance, beginning with the IIIF Image API. For more information, please see [IIIF technical details][tech-details].  

## Does IIIF replace or integrate with my Digital Asset Management (DAM) software?

* IIIF is a method for delivery of assets, not storage. Integration with your DAM software is dependent on your DAM provider. The IIIF community encourages DAM software providers to incorporate native IIIF support into their products.

## Does the IIIF Consortium serve as an aggregator of IIIF content?

* No, the IIIF Consortium and wider community does not have a single aggregation platform for content.  IIIF defines APIs that allow for interoperability between digital image repositories, including aggregators.  Because the IIIF APIs are well documented and understood, use of IIIF can enable aggregators such as Artstor, DPLA, and Europeana to access your images more easily.  

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
