## Fichero de objetivos de la asignatura.

### Ejercicios: 
[Tema1](https://github.com/carlos-el/Ejercicios-CC/blob/master/Tema1-Arquitecturas_para_la_nube.md), 
[Tema2](https://github.com/carlos-el/Ejercicios-CC/blob/master/Tema2-Desarrollo_basado_en_pruebas.md)
[Tema4](https://github.com/carlos-el/Ejercicios-CC/blob/master/Tema4-Contenedores_y_como_usarlos.md)

### Objetivos del hito 0:

- [x] Entender la metodología docente, de evaluación y de interacción de la asignatura.
- [x] Darse de alta y comprender el funcionamiento básico de git y GitHub y el grupo de Telegram de la asignatura.
- [x] Entender el concepto de software libre y su aplicación práctica en clase.
Vernos las caras.
- [x] Comenzar a usar git desde línea de órdenes y comprender su papel como sistema para trabajo colaborativo y despliegue de aplicaciones. 
- [x] Comprender la metodología de desarrollo, prueba y despliegue en la que se basa la computación en nube.
- [x] Entender en qué consiste el proyecto de la asignatura y comenzar a trabajar en el mismo.
- [x] Tener a punto una instalación Linux para llevar a cabo las actividades de la asignatura.
- [x] Usar los métodos de entrega de los objetivos propuestos para la asignatura usando GitHub.
- [x] Manejar de forma básica la línea de órdenes de Linux.
- [x] Entregar el fichero de objetivos y los primeros ejercicios usando GitHub.
- [x] Conocer dónde se pueden obtener recursos cloud gratuitos para usar en la asignatura.

- [x] Entender las características de las aplicaciones que se despliegan en la nube.
- [x] Entender correctamente la dinámica de la asignatura.
- [x] Entender correctamente la enseñanza basada en proyecto y por objetivos. 
- [x] Entender cómo se plantea un proyecto en informática. 
- [x] Entender la diferencia entre frontend y backend y cómo se pueden desarrollar de forma independiente. 
- [x] Entender el concepto de domain driven design
- [x] Entender arquitecturas de paso de mensajes.

### Objetivos del hito 1:

- [x] Entender las claves del desarrollo basado en pruebas.
- [x] Comprender el paper fundamental de la infraestructura virtual en este proceso.
- [x] Entender el concepto de "infraestructura como código" e "infraestructura virtual" para ponerlo en práctica en el hito número 1.

- [x] Revisar y entender recomendación especial de entregas
  * Alberto Montes, por incluir los servicios imprescindibles en toda
    aplicación basada en microservicios.
    
- [x] Solventar los errores comunes en el segundo envío del proyecto
  * Los diagramas de arquitectura incluyen qué se comunica entre
    diferentes microservicios, no cómo se comunica
  * Sigue incluyendo interfaces de usuario.
  * Siguen sin incluir ni logs ni configuración distribuida
    * Y los que lo hacen siempre ponen etcd. (Otras
      alternativas:
      [zookeper](https://sysgears.com/articles/managing-configuration-of-distributed-system-with-apache-zookeeper/) (síndrome
      "qué hay que poner aquí")
- [x] Comprender el [primer hito del proyecto](http://jj.github.io/CC/documentos/proyecto/1.Infraestructura).
- [x] Entender qué son los brokers de mensajería y cómo se usan.
- [x] Hacer un ejercicio práctico de domain driven design.
- [x] Tener manejo básico de los lenguajes usados en herramientas de
  provisionamiento, Python y Ruby.

### Objetivos del hito 2:

- [x] Entender las arquitecturas de software en la nube de uso en la actualidad.
- [x] Comprender el paper fundamental de la infraestructura virtual en este proceso.
- [x] Comprender el tipo de aplicaciones que se despliegan en la nube.

- [x] Entender problemas en el hito 1 
- [x] Tener manejo básico de los lenguajes usados en herramientas de provisionamiento, Python y Ruby.
- [x] Instalar las herramientas de línea de órdenes de las herramientas cloud.
- [x] Hacerse con alguna cuenta gratuita o bonificada de cloud.
- [x] Aprender la mínimo de los lenguajes necesarios para trabajar en la nube: Perl, Python y Ruby.
- [x] Aprender a realizar test unitarios, de integración y de cobertura en proyectos cloud.
- [x] Aprender a configurar herramientas de integración continua y de construcción
- [x] Realizar [proyecto](https://github.com/carlos-el/ProyectoCursoTDD-Notas) del curso de tdd para la afianzación de los conocimientos anteriores.

### Objetivos del hito 3:

- [x] Entender la arquitectura en capas de los microservicios usados en despliegues modernos.
- [x] Comprender el paper fundamental de la infraestructura virtual en este proceso.
- [x] Comprender el tipo de aplicaciones que se despliegan en la nube.
- [x] Entender el papel de los contenedores en la infraestructura virtual.
- [x] Comprender los procesos de definición de contenedores.
- [x] Alta en Docker Hub si no se ha hecho ya, así como instalación de las herramientas de Docker.
- [x] Tener manejo básico de los lenguajes usados en herramientas de provisionamiento, Python y Ruby.

- [x] Entender la configuración de infraestructura virtual desde contenedores.
- [x] Comprender cómo esta configuración forma parte de arquitecturas nativas en la nube.
- [x] Probar diferentes microframeworks y quedarse con el más adecuado para el proyecto. Entender las diferencias entre ellos. Esto se ha realizado sobre Flask y Falcon (ambos para python). Despueas de comprobar sus características hemos comprobado que Falcon es el más adecuado para el proyecto ay que aunque no cuenta con sistema de plantillas (tampoco lo necesitaremos) tiene un mejor rendimiento y es igual de fácil de configurar.

- [x] Entender el ecosistema de contenedores y diferentes alternativas a todas las aplicaciones.
- [x] Instalar podman y buildah, aplicaciones alternativas que siguen el estándar OCI. Se puede comprobar sobre el primer ejercicio incluido en [este](https://github.com/carlos-el/Ejercicios-CC/blob/master/Tema4-Contenedores_y_como_usarlos.md) enlace.
- [x] Usar registros de contenedores alternativos a Docker Hub como GitHub. En nuestro caso ha sido GitHub.

- [x] Repasar conceptos de microservicios
- [x] Repasar conceptos de contenedores
- [x] Revisar errores frecuentes en la entrega retrasada
- [x] Dejar en el directorio principal sólo herramientas de construcción y ficheros de configuración.
- [x] Investigar sobre herramientas medidas numéricas de prestaciones como Taurus y [como usarlas](https://www.blazemeter.com/blog/how-execute-load-test-using-taurus-docker-image/) de manera correcta.
- [x] Aprender a usar Taurus de manera adecuada enviando [distintos tipos de peticiones](https://gettaurus.org/docs/JMeter/#HTTP-Requests).

- [x] Tener listos diferentes sistemas cloud donde se puedan desplegar máquinas virtuales.
- [x] Conocer diferentes lugares donde haya imágenes de sistemas operativos listas para usar.
- [x] Instalar y configurar diferentes sistemas de provisionamiento.
- [x] Entender los conceptos de los sistemas de máquinas virtuales y cómo configurarlos desde línea de órdenes.
- [x] Entender las nociones básicas de seguridad.

- [x] Entender los recursos para automatización de actividades en la nube
- [x] Entender el concepto de infraestructura definida por software.
- [x] Entender el concepto de sistema completo y cómo arrancarlo.
- [x] Tener listas instalaciones que funcionen de [ansible con EC2](https://sysgears.com/articles/managing-configuration-of-distributed-system-with-apache-zookeeper/), herramienta de línea de órdenes de Amazon.
- [x] Entender los conceptos medición de prestaciones
- [x] Entender los conceptos detrás del provisionamiento de una máquina virtual o contenedor.
- [x] Entender las diferentes fases de despliegue de una aplicación.

