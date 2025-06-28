## Que es Domain Driven Design
Es un enfoque de desarrollo de software que se centra en la comprensión y modelado del dominio del negocio. El objetivo es crear modelos de dominio que sean reflejo fiel de las necesidades del negocio y que guíen tanto el diseño como la implementación del software.

***Objetivo de DDD:***
Lograr que el diseño del software se base en el entendimiento profundo del dominio del negocio. Esto permite gestionar la complejidad de los sistemas al partir de una colaboración constante entre expertos en el negocio y desarrolladores. 

***Porque usarlo?***
Ayuda a manejar la complejidad del dominio:
1. **Concentrarse en el negocio,** no en la tecnología.
2. **Fomentar la colaboración** entre los expertos en el dominio y desarrolladores.
3. Crear **modelos de dominio** que se convierten en el corazón de la solución.

## Principios clave de DDD
***Principales ideas:***
1. **Foco en el dominio:***
	1. DDD pone el dominio del negocio en el centro del proceso de diseño de software.
	2. Expertos del dominio (SH) trabajan junto a los desarrolladores para crear un modelo común que ambos entiendan.
2. **Lenguaje Ubicuo:** 
	1. DDD promueve el uso de un lenguaje común entre todos los involucrados en el desarrollo.
	2. El lenguaje ubicuo garantiza que todos los términos y conceptos en el modelo sean claros y compartidos por todos. 
3. **Modelo iterativo:**
	1. El modelo de dominio debe ser explorado y refinado a medida que se aprende más sobre el negocio y sus necesidades.
	2. Es un proceso evolutivo, donde el modelo y las soluciones se desarrollan y mejoran continuamente.


***Componentes principales:***
1. **Personas y cultura:** La gente del negocio y los desarrolladores deben compartir un mismo lenguaje y compartir una visión.
2. **Procesos y prácticas:** Promueve un enfoque iterativo y colaborativo entre desarrolladores y expertos del negocio. Involucra actividades como modelado conjunto, feedback rápido y ajustes continuos. 
3. **Herramientas y tecnologías:*** DDD utiliza tecnologías que facilitan la colaboración y la implementación del modelo de dominio.

## Tipos de dominios en DDD
1. **Core Domain:**
	1. Es el corazón del negocio
	2. Contiene las funcionalidades que definen el negocio y que son clave para la razón de ser del software
2. **Dominio genérico:
	1. Dominios comúnes a muchos negocios pero escenciales. 
3. **Dominio de soporte:**
	1. Son dominios complementarios que ayudan o soportan al core domain.

***La importancia de clasificar dominios:***
El **core domain** deben recibir más atención y esfuerzos en su desarrollo y optimización. Por otro lado los dominios genéricos y de soporte generalmente deben ser adquiridos como soluciones listas para no sobrecargar el desarrollo. 

## Modelado de dominio en DDD
***Que es:*** Es una representación abstracta y estructurada del problema que el sistema debe resolver. Este modelo incluye tanto conceptos clave como relaciones entre ellos, y se utiliza para guiar tanto el diseño del sistema como la implementación.

***Como crear:***
1. **Colaboración entre expertos del dominio y desarrolladores:** Ambos trabajan juntos para crear un modelo compartido. 
2. **Uso de ejemplos concretos** Para ilustrar cómo los conceptos del dominio se implementan en el software.
3. **Modelado de objetos:** Las entidades, objetos de valor, servicios y eventos del dominio deben ser modelados para reflejar la realidad del negocio. 

***Iteración del modelo:***
El modelo debe ser revisado y refinado constantemente a medidda que evoluciona la comprensión del negocio y se obtiene retroalimentación. **No es estático**

## Patrones en DDD
1. **Entidades:** Son objetos que tienen una identidad única a lo largo del tiempo, independiente de los cambios en sus atributos. 
2. **Objetos de valor:** Son objetos que se definen por sus atributos y no tienen identidad propia. Son inmutables.
3. **Agregados:** Son un conjunto de entidades y objetos de valor relacionados entre si. Solo la raíz del agregado debe ser accesible desde fuera. 
4. **Servicios:** Encapsulan lógica de negocio que no pertenece a una entidad ni a un objeto de valor. 
5. **Repositorios:** Proveen acceso a los objetos de dominio y los mantienen persistentes en la base de datos. 

## Contextos limitados en DDD
Un contexto limitado es una sección bien definida del sistema que tiene su propio modelo de dominio. Se utiliza para evitar superposición de conceptos en el mismo sistema, y cada contexto tiene sus propias reglas y lógica. 
	-> Evita la confusión entre entidades u objetos de valor que pueden tener significados diferentes en diferentes contextos. 

**Colaboración entre contextos:**
Cuando un contexto necesita interactuar con otro, se definen interfaces claras y mecanismos de comunicación entre ellos. 
