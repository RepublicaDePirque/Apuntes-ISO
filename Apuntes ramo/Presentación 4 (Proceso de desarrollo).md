***Ciclo de vida:*** Existe un conjunto de actividades por las que pasa el sistema que se está desarrollando desdeq eu nace la idea inicial hasta que el software es retirado o reemplazado.

- *Funciones destacadas en un ciclo de vida:*
	- Determinar el orden de las actividades del proceso
	- Estableces los criterios de transición para pasar de una actividad a otra.
	- Definir las entradas y salidas de cada actividad
	- Describir los estados por los que se pasa en cada actividad.
- *Modelos:* Describen las distintas etapas y estados por los que pasa un producto de software: 
	- Concepción inicial
	- Pasando por su desarrollo
	- Puesta en marcha
	- Posterior mantenimiento
	- Retirada del producto
- *Tipos de modelos:* 
	- Principales diferencias:
		- Alcance del ciclo
		- Caracteristicas de las actividades del ciclo
		- Puede depender del tema
		- Estructura y sucesión de las actividades. 

***Modelo de desarrollo de software:*** Establece que las diversas actividades que se van realizando de una manera.
- **Lineal o cascada:**
	- *Actividades en orden lineal.*
	- *Recomendable cuando:*
		- Requisitos son bien conocidos
		- Productos son estables
		- Tecnología es entendida
		- No hay requisitos ambiguos
		- Ya existe experiencia de desarrollo en el equipo
		- El proyecto es corto
	- *No refleja la realidad*
- **V:**
	- *Variación del modelo en cascada:*
		- Cada actividad de prueba es contraparte de una actividad de desarrollo con el mismo ámbito.
	- *Se forman ciclos desarrollo-verificación-desarrollo...*
	- *Recomendable:* 
		- Proyectos de poco o mediano alcance
		- Recursos técnicos completamente disponibles y exista experiencia en el uso de ellos. 
- **Fase:**
	- *El mercado exige entregas prontas*
	- *Idea: Desarrollar en fases*
		- Diseñar el sistema para entregarlo por partes
		- Usuario obtiene funcionalidad parcial mientras se desarrolla.
	- ***Desarrollo iterativo incremental:***
		- *Iterativo:* Se entrega el sistema completo y se van haciendo mejoras en cada nueva versión.
		- *Incremental:* El sistema se particiona en subsistemas por funcionalidad y se van agregando funcionalidades por cada nueva versión.
- **Riesgo modelo espiral:** El orden de ejecución de las actividades de desarrollo es determinado por análisis de riesgo.
	- *Modelo iterativo:* Planificación -> Análisis de riesgo -> Ingeniería -> Evaluación -> Planificación -> ...
	- *En cada iteración se evalúan alternativas y se elíge una para eliminar o minimizar riesgo.*
	- *Ventajas:* 
		- Alto manejo de riesgo
		- Buen manejo de proyectos críticos
		- Buena documentación
		- Se pueden agregar funcionalidades extra
		- El software es realizado en etapas tempranas del proyecto
	- *Desventajas:* 
		- Puede ser costoso
		- Se necesita experiencia en el análisis de riesgo
		- El éxito del proyecto depende del analisis de riesgo
		- No funciona para proyectos pequeños
	- *Es recomendable cuando:* 
		- Costos y riesgo son importantes
		- Pequeños a grandes proyectos
		- Usuarios no saben lo que quieren
		- Requerimientos complejos
		- Nuevas lineas de productos
		- Cambios significativos esperados

***Proceso de desarrollo de software:***
- Es necesario establecer, gestionar y apoyar el trabajo de desarrollo.
- El termino tiende a unificar todas las actividades y prácticas que cubren esas necesidades.
- El principal objetivo de tal proceso es garantizar la construcción de un software adecuado, conforme a especificaciones y dentro de los límites de tiempo y costo.
- Modelar el proceso de software es una forma para mejorar el desaroollo y la calidad de las aplicaciones resultantes. 
- **SPEM:** Proporciona una sintaxis y estructura para cada aspecto de los procesos de desarrollo, incluyendo: 
	- Roles
	- Tareas
	- Artefactos
	- Lista de verificación
	- Productos de trabajo
	- Técnicas y herramientas
	- Estructuras de trabajo
	- etc

***Rational Unified Process (RUP):*** Es un framework para describir procesos de desarrollo de especificos:
	-  Modelo de proceso centrado en arquitectura.
	- Enfoque iterativo incremental.
- *Instanciación:* Manual o con IBM rational method composer.

![[Pasted image 20250426102141.png]]

- *RUP tiene 2 dimensiones:* 
	- Horizontal (tiempo): Ciclo de vida en fases o iteraciones
	- Vertical (workflow): Disciplinas de proceso; agrupan actividades.
- *Artefactos:* Entradas y salidas de actividades.
- **Todo proyecto tiene 4 fases:**
	- *Concepción
	- *Elaboración*
	- *Construcción*
	- *Transición*
- *Disciplinas (9):*
	- Modelado de negocio
	- Requisitos
	- Análisis y diseño
	- Implantación
	- Prueba
	- Despliegue
	- Gestión de cambio y configuración
	- Gestión del proyecto
	- Ambiente
- *Roles:* 36 en 6 grupos
- *Artefactos:* 76

***OPENUP:*** Versión ligera de RUP:
- *Disciplinas (5):*
	- Requerimientos
	- Arquitectura
	- Desarrollo
	- Testeo
	- Gestión de proyecto
- *Roles:* 7
- *Artefactos:* 17
-> **Inception:**
	- Definir ambito y arquitectura del proyecto
	- Definir requisitos
-> **Elaboration:**
	- Priorizar workstreams con buissnes del negocio
	- Hacer estimaciones de plazos y costos
-> **Construction:**
	- Desarrollar, probar y entregar work packages incrementalmente. 
	- Mostrar al negocio incrementos en la solución y recabar feedback
-> **Transition:** 
	- Solución beta para validar que se cumple expectativas del negocio
	- Lograr acuerdo del negocio con que la solución está completa

***EPF composer:*** Es una herramienta que permite generar macros de procesos de software para una organización.
- Basado en modelos reutilizables que permiten tomar las mejores prácticas del mercado e integrarlas en el framework de procesos organizacionales.
- Ambiente de desarrollo Eclipse:
	- Permite automatizar, parametrizar y publicar métodos.
	- Añadir, eliminar y cambiar procesos de acuerdo con las necesidades de su proceso
	- Publicar y comunicar el contenido para servir de guía a su equipo de trabajo


***Mejoramiento de procesos de software (SPI):***
- Inmadurez en la ingeniería de software
- 3 factores críticos:
	- Personas
	- Tecnologías 
	- Procesos
- Principio básico: Mejorar la calidad del producto mejorando la calidad del proceso de software
- La capacidad de los procesos puede ser mejorada

- Conjetura básica: Se puede mejorar la calidad del producto por medio de mejorar la calidad del proceso de software.
- **Mejoramiento del proceso de software:**
	- Metodología deliberada y planeada que sigue prácticas de documentación estandarizadas para capturar en documentos cada elemento del proceso de software y para determinar su valor agregado.
- Surge la herramienta ETVX

- **Diagrama ETVX:**
	- SPI es un proceso compuesto de actividades
	- Cada actividad se controla con el modelo Entry-Task-Verification-Exit
	- Requiere:
		- Conjunto preefinido de criterios de entradas
		- Tareas
		- Verificaciones
		- Un conjunto predefinido de criterios de salida

![[Pasted image 20250426104221.png]]

- Objetivos SPI:
	- Entender el estado presente de la práctica de la ingeniería de software y la gestión en una organización
	- Seleccionar áreas de mejoramiento donde los cambios tendrán grandes beneficios en el tiempo
	- Enfocar e insertar valor agregado
	- Combinar procesos efectivos con personas motivadas, preparadas y creativas

***CMMI - Modelo de madurez de capacidades:*** 
- SEI - Software Engineering Institute
- *Objetivos:* 
	- Estableces estándares de excelencia en ing. de software
	- Acelerar transición de tecnología y métodos avanzador a la práctica.
- *Principal resultado:* 
	- Modelos de madurez de proceso de software
	- Procesos
	- Arquitectura de software
- *5 Niveles para procesos:*
	1. Inicial
	2. Repetible
	3. Definido
	4. Administrado
	5. Optimizante
- *Marco evolutivo organizado en cinco niveles para lograr la mejora continua de procesos*
- *Ventajas:*
	- Especifico para el desarrollo y mantenimiento de software
	- Definido como un conjunto de áreas clave de procesos
	- Tiene un modelo de evaluación
	- Popular
	- Existen empresas evaluadoras

***Capability Maturity Model (CMM):*** Descompone cada nivel de madurez en 3 partes.
- Áreas clave: Objetivos a se alcanzados para tener un nivel de madurez particular
- Prácticas claves: Procedimientos y actividades que contribuyen a alcanzar los objetivos
- Indicadores clave: Permiten determinar el cumplimiento de los objetivos y son la base de procedimiento de evaluación