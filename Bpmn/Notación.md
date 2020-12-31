## Lo que BPMN debe cumplir y lo que no

BPMN fué desarrollado para modelar procesos, y su simbología no puede representar las siguientes estructuras:

- Mapas de procesos.
- Estructuras organizacionales.
- Estructuras de datos.
- Estrategias y modelos de negocio.
- Reglas de negocio.

> BPMN se concentra en el modelamento de los procesos y no de otras estructuras organizaciones. BPMN no fué concebida como una notación para modelar otras estructuras de la arquitectura empresarial.

> Modelos BPMN pueden relacionarse con otros modelos de una arquitectura empresarial.

>BPMN ofrece la posibilidad de ampliarse a través de incluir simbolos propios o de relaciones con otros objetos de una arquitectura empresarial. 


## Elementos básicos de BPMN

En un principio en un proceso hay que hacer ciertas cosas (actividades), pero a lo
mejor sólo bajo ciertas condiciones (Gateways) y además pueden ocurrir cosas
(eventos). A estos objetos se les denomina en BPMN objetos de flujo y se conectan
por medio de un flujo de secuencia, pero sólo dentro de un pool, o lanes dentro de un
pool. Si se requiere una relación entre dos o más pools se utilizan flujos de mensaje.

Además existen objetos llamados artefactoslos cuales enriquecen de información la
descripción de un proceso, pero los cuales no tienen ninguna influencia en la lógica
del proceso. Cada artefacto puede relacionarse con cualquier objeto de flujo a través
de objetos del tipo asociación. También está permitido utilizar símbolos propios
como artefactos.

**Figura elementos básicos de BPMN**
![[elementos-bpmn.png]]

Si en un proceso es importante mostrar como van cambiando de estado (información), entonces en un objeto de negocio (solicitud, contrato, etc) podemos utilizar el objeto de datos para y relacionarlo con el objeto de tipo asociación a las actividades. 

## Las diferentes vistas de un proceso

BPMN parte de la base que en un diagrama pueden representarse a uno o más participantes (no confundir participante con un rol, un departamento o usuario). Un participante es para BPMN en primer lugar un elemento lógico, que obedece a las siguientes reglas:

- En un proceso existe un sólo participante.
- Este participante posee el control absoluto sobre la lógica del proceso. Otros participantes no pueden influenciar este proceso, en algunas ocasiones ni siquiera saben como está organizado.
- El participante es por definición el responsable del proceso.
- SI varios participantes deben interactuar con otros procesos, deben de hacerlo por medio del intercambio de información (flujo de mensaje), información que apoya la operación del proceso.

> Debido a estos principios, se da que cada participante tenga su propia vista sobre el proceso general, es decir, diferentes perspectivas. Este hecho nos dice	 que un proceso de negocio puede llegar a tener (y por lo general tiene) varios modelos de procesos, tantos procesos como participantes existan.

> El objeto que en BPMN representa un participante es un pool.


## Modelos, instancias, token y correlaciones


## Simbología y atributos