# Entendiendo los diagramas de casos de uso (use cases diagrams)

Aunque los casos de uso son descripciones de la funcionalidad del sistema que deben existir en forma textual (Ver esta entrada). Estos son usualmente acompañados por diagramas que capturan detalles como los nombres de los casos de uso, los límites de los sistemas, los actores y las relaciones entre ellos. El estándar UML proporciona notación para cada uno de estos detalles.

Estos diagramas siempre se dibujan desde la perspectiva de la organización sin distinguir entre procesos automáticos y manuales, hay que tener presente que los diagramas de caso de uso son la vista estática del sistema.

Lista de los elementos generales para un diagrama de casos de uso:

Actor: Un actor representa un rol ejecutado por una persona externa, por un proceso o por cualquier cosa que interactue con el sistema.


Caso de uso (use case): Un caso de uso es un clasificador que representa una unidad de funcionalidad proporcionada por un sistema, un subsistema o una clase que puede intercambiar mensajes entre las acciones del sistema y uno o más actores.



Paquete (package): Sirve para la agrupación de elementos, puede contener otros paquetes.


Límite (System Boundary): El limite del sistema consiste de todos los casos de uso que están relacionados con el dominio del sistema.


Asociación (association): La participación de un actor en un caso de uso, instancias del actor e instancias del caso de uso se comunican una con otra.


Extend: Esta relación desde un caso de uso A a un caso de uso B indica que una instancia de un caso de uso B puede ser aumentado por el comportamiento especificado en A.


Include: Este relación se utiliza para indicar que un caso de uso es una subrutina de otro caso de uso.

Los casos de uso son organizados de forma jerárquica con las relaciones: extend, e include.

Una herramienta muy buena para hacer diagramas es visual paradigm, hay versiones para Windows, Mac y Linux, se puede descargar una versión community edition del sitio.
