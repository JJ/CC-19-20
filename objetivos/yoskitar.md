# Objetivos para CC de Óscar Jiménez Fernández

## Ejercicios de Cloud Computing
[Repositorio de ejercicios](https://github.com/yoskitar/Ejercicios-CC)

## Objetivos del hito 0

### Semana 0
- [X] Entender la metodología docente, de evaluación y de interacción de la asignatura.
- [X] Darse de alta y comprender el funcionamiento básico
   de git y [GitHub](https://github.com) y el grupo de Telegram de la
   asignatura; conocer y entender el resto de los recursos de la asignatura.
- [X] Entender el concepto de software libre y su aplicación práctica en clase.
- [X] Vernos las caras.
- [X] Comenzar a usar `git` desde línea de órdenes y comprender su papel como sistema para trabajo colaborativo y despliegue de aplicaciones. Un buen conocimiento de git es fundamental para trabajar en esta asignatura.
- [X] Comprender la metodología de desarrollo, prueba y despliegue en la que se basa la computación en nube.
- [X] Entender en qué consiste el proyecto de la asignatura y comenzar a trabajar en el mismo.

### Semana 1
- [X] Comprender la metodología de desarrollo, prueba y despliegue en la que se basa la computación en nube.
- [X] Entender las características de las aplicaciones que se despliegan en la nube.

### Semana 2
- [X] Comprender la metodología de desarrollo, prueba y despliegue en la que se basa la computación en nube.
- [X] Entender las características de las aplicaciones que se despliegan en la nube.

## Otros objetivos del hito 0

### Semana 0
- [X] Tener a punto una instalación Linux para llevar a cabo las actividades de la asignatura
- [X] Usar los métodos de entrega de los objetivos propuestos para la asignatura [usando GitHub](../objetivos/README.md).
- [X] Manejar de forma básica la línea de órdenes de Linux.
- [X] Aprender a instalar software libre en Linux.
- [X] Entregar el fichero de objetivos.
- [X] Entregar primeros ejercicios.
- [X] Conocer dónde se pueden obtener recursos cloud gratuitos para usar
  en la asignatura.
- [X] Crear el repositorio del proyecto.

### Semana 1
- [X] Remarcar lo necesario para alcanzar el primer hito del proyecto de
  la asignatura.
- [X] Manejar con soltura los diferentes recursos de línea de órdenes,
  especialmente en Linux.
  - [X] Saber manejar la historia de comandos anteriores.
  - [X] Configurar la línea de órdenes para presentar información de
    repos.
  - [X] Conocer permisos y cuales usar en cada momento.
- [X] Entender lo necesario para entregar el hito 0 del proyecto.

### Objetivos tutoría 11-octubre-2019

- [X] Entender correctamente la dinámica de la asignatura.
- [X] Entender correctamente la enseñanza basada en proyecto y por objetivos.
- [X] Entender correctamente qué significa *entender*.
- [X] Entender cómo se plantea un proyecto en informática.
  - [X] Requisitos funcionales y cómo especificarlos en un proyecto.
  - [X] A qué corresponde este proyecto en GitHub: hitos e *issues* y cómo buscar la correspondencia.
- [X] Entender la diferencia entre *frontend* y *backend* y cómo se pueden desarrollar de forma independiente.
  - [X] Entender también que muchas aplicaciones no necesitan un frontend.
- [X] Entender el concepto de *domain driven design*
  - [X] Hacer un ejemplo práctico.
- [X] Entender arquitecturas de paso de mensajes.

### Semana 2
- [X] Entender los errores cometidos en el hito
  - [X] Entender cómo se hace desarrollo colaborativo en git: resolver conflictos, sincronizar versiones...
  - [X] Entender por qué no se hace `git pull` sino `git pull --rebase` y
  como arreglarlo en ese caso
  usando un squash commits con
  [`git rebase -i`](https://stackoverflow.com/questions/5189560/squash-my-last-x-commits-together-using-git).
  - [X] Ejemplo de arquitectura basada en eventos: [cliente Slack y Celery](https://github.com/JJ/slack-bot-platzi/blob/master/cliente-con-celery.py) + [servidor de tareas](https://github.com/JJ/slack-bot-platzi/blob/master/PlatziTareas.py).
  - [X] Ejemplo adicional [Gateway](https://github.com/JJ/microservices-broker/blob/master/github-server/server-with-bunny.rb) + [worker](https://github.com/JJ/microservices-broker/blob/master/github-server/worker.go) + [procesador](https://github.com/JJ/microservices-broker/blob/master/github-server/procesa.py) + [store](https://github.com/JJ/microservices-broker/blob/master/github-server/store.p6).
- [X] Entender que las arquitecturas basadas en microservicios necesitan servicios adicionales.
  - [X] Configuración remota
  - [X] Log
  - [X] Almacén de datos.

- [X] Manejar con soltura los diferentes recursos de línea de órdenes,
  especialmente en Linux.
  - [X] Saber manejar la historia de comandos anteriores.
  - [ ] Configurar la línea de órdenes para presentar información de
    repos.
  - [X] Conocer permisos y cuales usar en cada momento.
- [X] Haber entregado el hito 0 del proyecto y entender qué se buscaba con
  el mismo.

## Objetivos del hito 1
### Semana 3
- [X] Entender las claves del desarrollo basado en pruebas.
- [X] Comprender el papel fundamental de la infraestructura virtual en
   este proceso.

## Otros objetivos del hito 1
- [X] El aprendizaje memorístico y el síndrome "qué hay que poner aquí".
- [X] Repasar ejercicios de autoevaluación:
  - [X] Ver bloque 2 de ejercicios de
  [primer tema](http://jj.github.io/CC/documentos/temas/Arquitecturas_para_la_nube)
      - [X] Por ejemplo, el de [antmordhar](https://github.com/antmordhar/EjerciciosCC/blob/master/ejerciciosTema1.md).
- [X] Recomendación especial de entregas
  - [X] Alberto Montes, por incluir los servicios imprescindibles en toda
    aplicación basada en microservicios.
- [X] Errores comunes en el segundo envío del proyecto
  - [X] Los diagramas de arquitectura incluyen qué se comunica entre
    diferentes microservicios, no cómo se comunica
  - [X] Sigue incluyendo interfaces de usuario.
  - [X] Siguen sin incluir ni logs ni configuración distribuida
    - [X] Y los que lo hacen siempre ponen etcd. (Otras
      alternativas:
      [zookeper](https://sysgears.com/articles/managing-configuration-of-distributed-system-with-apache-zookeeper/) (síndrome
      "qué hay que poner aquí")
- [X] Comprender el [primer hito del proyecto](http://jj.github.io/CC/documentos/proyecto/1.Infraestructura).
- [X] Entender qué son los brokers de mensajería y cómo se usan.
- [X] Tener manejo básico de los lenguajes usados en herramientas de
  provisionamiento, Python y Ruby.

## Objetivos del hito 2
[Ejercicios desarrollados para la adquisición de competencias relacionadas con los objetivos.](https://github.com/yoskitar/Ejercicios-CC/blob/master/Ejercicios%20Tema%202.md)

[Curso TDD](https://github.com/Miguel-y-Oscar/Geolocalizaciones-de-medios-sociales)

### Semana 4
- [X] Entender los conceptos de desarrollo basado en test y otros
   conceptos de calidad del software.
- [X] Entender el concepto de herramientas de construcción y su
   importancia en la infraestructura virtual.
- [X] Entender qué son los sistemas de integración continua y cómo
   usarlos.

   

### Semana 5
- [X] Entender las arquitecturas de software en la nube de uso en la
   actualidad.
- [X] Comprender el paper fundamental de la infraestructura virtual en
   este proceso.
- [X] Comprender el tipo de aplicaciones que se despliegan en la nube.

## Otros objetivos del hito 2
- [X] Darse de alta en plataformas que permitan llevar a cabo
   integración/despliegue continuo.
- [X] Familiarizarse con marcos de pruebas para el lenguaje en el que se
   esté desarrollando la aplicación.

- [X] Recomendaciones Hito 1
  - [X] [mald16](https://github.com/ibe16/CC-19-20-Proyecto), [`yoskitar`](https://github.com/yoskitar/Cloud-Computing-CC).
- [X] Entender problemas en el hito 1
  - [X] Estructuración de la documentación.
  - [X] Las entregas en hitos tratan de evaluar si se ha entendido un
    concepto. En este caso se trata del concepto de infraestructura virtual.
  - [X] Seguimos con el aprendizaje memorístico y el síndrome "qué hay que poner aquí".
  - [X] La infraestructura virtual puede incluir tecnologías específicas
    que no sean libres, pero nunca servicios externos, ni servicios
    específicos de un proveedor en la nube.
    - [X] Y en todo caso deben ser adecuadas para lo que se supone que son.
  - [X] Cuidado con Java
- [X] Tener manejo básico de los lenguajes usados en herramientas de
  provisionamiento, Python y Ruby.
- [X] Instalar las herramientas de línea de órdenes de las herramientas cloud.
- [X] Hacerse con alguna cuenta gratuita o bonificada de cloud.
- [X] Aprender la mínimo de los lenguajes necesarios para trabajar en la
  nube: Perl, Python y Ruby.

## Objetivos del hito 3
[Ejercicios desarrollados para la adquisición de competencias relacionadas con los objetivos de microservicios.](https://github.com/yoskitar/Ejercicios-CC/blob/master/Ejercicios%20Tema%203.md)

[Ejercicios desarrollados para la adquisición de competencias relacionadas con los objetivos de contenedores.](https://github.com/yoskitar/Ejercicios-CC/blob/master/Ejercicios%20Tema%204.md)

### Semana 6
- [X] Entender la arquitectura en capas de los microservicios usados en
   despliegues modernos.
- [X] Comprender el paper fundamental de la infraestructura virtual en
   este proceso.
- [X] Comprender el tipo de aplicaciones que se despliegan en la nube.
- [X] Entender el papel de los contenedores en la infraestructura virtual.
- [X] Comprender los procesos de definición de contenedores.

### Semana 7
- [X] Entender la configuración de infraestructura virtual desde contenedores.
- [X] Comprender cómo esta configuración forma parte de arquitecturas nativas en la nube.

### Semana 8
- [X] Entender el ecosistema de contenedores y diferentes alternativas a
   todas las aplicaciones.

### Semana 9
- [X] Repasar conceptos de microservicios
- [X] Repasar conceptos de contenedores

## Otros objetivos del hito 3
- [X] Aclaraciones sobre la corrección de los hitos.
- [X] Actualización de los objetivos y su importancia en la nota final.
- [X] [Usar registros de contenedores alternativos a Docker Hub como
   GitHub](https://github.com/yoskitar/Cloud-Computing-CC/packages/65803). 
- [X] Retro de la entrega del hito 2
- [X] Revisar errores frecuentes en la entrega retrasada
   - [X] [No dar medidas numéricas de prestaciones](https://github.com/yoskitar/Cloud-Computing-CC/issues/53).
   - [X] [El uso de `.dockerignore` no excusa que copiéis solo lo necesario](https://github.com/yoskitar/Cloud-Computing-CC/issues/54).
	- [X] [Dejar en el directorio principal sólo herramientas de construcción y ficheros de configuración](https://github.com/yoskitar/Cloud-Computing-CC/issues/57).

## Objetivos del hito 4

### Semana 10
- [X] Tener listos diferentes sistemas cloud donde se puedan desplegar máquinas
  virtuales.

- [X] Conocer diferentes lugares donde haya imágenes de sistemas operativos listas para usar.

- [X] Instalar y configurar diferentes sistemas de provisionamiento.

- [X] Entender los conceptos de los sistemas de máquinas virtuales y cómo configurarlos desde línea de órdenes.
- [ ] Entender las nociones básicas de seguridad.

### Semana 11

- [X] Entender los recursos para automatización de actividades en la nube.
- [X] Entender el concepto de infraestructura definida por software.
- [X] Entender el concepto de sistema completo y cómo arrancarlo.

## Otros objetivos del hito 4

- [X] Entender los errores de la entrega del hito 3.
   - [X] El README.md es del proyecto que estáis haciendo, con enlaces adicionales (y precisos) para corregir. Por favor, entenderlo así.
   - [X] No quiero ni un loquesea login más, por favor.
   - [X] [Hacer benchmarks cuantitativos está bien, hacerlos bien y de forma precisa está mejor.](https://github.com/yoskitar/Cloud-Computing-CC/issues/67)
	   - [X] No basta bajarse un URL n veces, sino que hay que seguir una secuencia de POST/GET delete simultánea de varios clientes a la vez. 
	 - [X] Si los resultados son sorprendentes, hay que revisar el proyecto. 
	 - [X] No sé de donde habéis sacado lo de 10 y 1000, pero debéis entender lo que hacéis. Por ejemplo, si tenéis sólo una copia del servidor, no debéis lanzar 10 peticiones a la vez porque lo sobrecargáis. Usad un número de peticiones simultáneas y servidores similares.
	 - [X] [Prácticamente nadie crea usuarios dentro del contenedor. Aunque no es imprescincible, es una buena práctica que conviene seguir.](https://github.com/yoskitar/Cloud-Computing-CC/blob/master/Dockerfile)
	- [X] Los commits deben siempre, salvo en casos excepcionales, referirse a un issue. Los issues no están para cerrarlos y pasar el test. 
- [ ] Instalarse los diferentes clientes de líneas de órdenes de los sistemas en la nube a los que se tenga acceso.

## Objetivos del hito 5

[Ejercicios desarrollados para la adquisición de competencias relacionadas con los objetivos provisionamiento y VMs.](https://github.com/yoskitar/Ejercicios-CC/blob/master/Ejercicios%20Tema%205.md)

### Semana 12

- [X] Entender los conceptos medición de prestaciones
- [X] Entender los conceptos detrás del provisionamiento de una máquina virtual o contenedor.
- [X] Entender las diferentes fases de despliegue de una aplicación.

## Otros objetivos del hito 5

- [X] Probar sistemas de aprovisionamiento, especialmente Ansible.
- [X] Entender la *galaxia* de Ansible y en qué nos puede ayudar.