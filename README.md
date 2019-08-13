# Nuevas reglas para el Marco de topología en gvSIG Desktop
## Google Summer of Code (GSoC) 2019 - OSGeo

* Propuesta: [Crear nuevas reglas para el marco de topología en gvSIG Desktop](https://wiki.osgeo.org/wiki/GvSIG_GSoC_2019_Ideas)

* [Página Wiki](https://github.com/Maureque/2019GSoC_versionHablaHispana/wiki)

* Repositorio que contiene todas las reglas desarrolladas para el marco de topología: https://github.com/gvsig-sandbox

## Introducción
Se desarrolla una nueva caja de herramientas topológicas. Esta herramienta provee un grupo de reglas de integridad que verifica la validación de las geometrías en relación a los datos. Se puede crear un nuevo modelo de datos topológicos para cada proyecto. Esta caja de herramientas proporciona un nuevo conjunto de herramientas para navegar, encontrar y corregir diferentes errores de validación para cada regla topológica. Actualmente, hay pocas reglas implementadas y con acciones limitadas.
Este proyecto analiza, implementa y optimizá un nuevo conjunto de reglas que se incorporan al marco de topología. Estas herramientas se pueden crear en Java o en Jython a través de la herramienta de creación de secuencias de comandos en gvSIG.

## Para empezar

Se incluyen comentarios y recursos de ayuda con el proceso de descarga y de lanzamiento, de descarga y ejecución de pruebas.

### Pre-requisitos

* JRE/OpenJRE 7 o posterior
* [gvSIG 2.4.0](http://www.gvsig.com/en/products/gvsig-desktop/downloads) - Descarga

Descargar e instalar la versión apropiada de **JRE/OpenJRE** para el correspondientes **SO** y **arquitectura**.  
Descargar la correspondiente versión de **gvSIG Portable** según el **OS** y **arquitectura**.  
Descomprimir el archivo ZIP, **NO** directamente en ```C:\``` (Windows) o ```/dev/sda/``` (Linux) y en una ruta **SIN** espacios.  
Ejemplo: crear una carpeta ```gvsig-desktop``` en ```C:\``` (Windows) o ```/dev/sda/``` (Linux) y descomprimir en esa ubicación.  
Dentro de la carpeta descomprimida, buscar ```gvsig-desktop.cmd``` en Windows o ```gvSIG.sh``` en Linux y ejecutar.

### Instalación

* [Prueba para calificar y poder participar de GSoC 2019](https://github.com/Maureque/GSoC_2019/) - Descarga
* [Administrador de complementos](https://www.youtube.com/watch?v=PrGhD9qm8ok) - Video Tutorial
* [Instalar complemento desde archivo](https://www.youtube.com/watch?v=2kcNanjW5Y8) - Video Tutorial

### Ejecutando

* [Lanzador y compositor de scripts](https://www.youtube.com/watch?v=ea5ZjpIEHaE) - Video Tutorial
 
### Comprobando las bases

* [Curso gvSIG](https://www.youtube.com/playlist?list=PLTwZbMzUIxFINjiceQ4yTauymW9d0jYVh) - Video Tutorial

## Autor

* **Mauro Carlevaro**

## Mentores
* **Óscar Martínez, Mario Carrera Rodriguez, Alfred de Jager and Francisco Peñarrubia.**

## Licencia

Este proyecto esta licenciado bajo la licencia GPLv3.

## Agradeciemientos

* gvSIG Association
* OSGeo
