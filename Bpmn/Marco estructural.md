DIagrama marco estructural

![[marco-estructural.png]]

> Los 3 primeros son lo mas relevantes desde el punto de vista del diseño

## Nivel 1 - Procesos descriptivos
- utilizados principalmente por [[Participantes#Process Owner Dueño del proceso|Process Owner]] y [[Participantes#Process Manager Gestor de Procesos|Process Manager]], como también los [[Participantes#Process Participant Usuario Ejecutivo de negocio|Process Participants]] y los [[Participantes#Process Analyst Analista de procesos|Process Analysts]] en las primeras fases de un proyecto.
- En este nivel se deben definir el contexto de los procesos que se deben levantar, modelar, documentar y eventualmente rediseñar.
- Otro objetivo es, validar el alcance r la funcionalidad principal de los procesos que deben levantarse.
- Se describe el flujo normal del proceso y como queremos que ocurra, sin considerar casos de excepción o errores.

> El nivel descriptivo sirve para validar en forma rápida el alcance del proyecto con los responsables del negocio y introducir al resto de los participantes en él.

## Nivel 2- Procesos operacionales
- Se desarrolla toda la lógica de los procesos al máximo detalle (se incluyen los casos de excepción, fallas e interrupciones que pueden ocurrir a nivel de negocio).
- El [[Participantes#Process Analyst Analista de procesos|Analista de procesos]] debe tener la habilidad de desarrollar un modelo en el nivel 2 que abarque toda la lógica a nivel de negocio y que sea transferible al siguiente nivel de implementación.

## Nivel 3a - Modelo técnico
- es la representación del modelo operacional en un [[Participantes#Process Engineer Ingeniero de Procesos Técnico|Process Engineer]], pero adaptandoel proceso de negocio a un modelo ejecutable.

> Como no siempre se implementan los modelos de negocio con un [[Participantes#Process Engineer Ingeniero de Procesos Técnico|Process Engineer]], se divide este nivel en un modelo téncino (Nivel 3a) que sigue detallando el modelo en un BPMS y el modelo de desarrollo propio (NIvel 3b).

## Nivel 3b - Especifiación para el desarrollo
- Si no se utiliza un [[Participantes#Process Engineer Ingeniero de Procesos Técnico|Process Engine]], entonces la lógica de negocio tiene que ser desarrollada en algún lenguaje de programación, asi que se debe elaborar especificaciones técnicas distitas a BPMN.

## Nivel 4b - Implementación
- Después del nivel [[Marco estructural#Nivel 3b - Especifiación para el desarrollo|Nivel 3b]] es necesario implementar técnicamente el proceso.