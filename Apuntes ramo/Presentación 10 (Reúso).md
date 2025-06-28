## Reúso de software:
***Qué es?***
Es una estrategia dentro de la ingeniería de software cuyo objetivo principal es reutilizar software o conocimiento ya existente para evitar reinventar la rueda cada vez. 

***Objetivos:***
- Reducir costos de desarrollo y mantenimiento.
- Acelerar tiempo de entrega.
- Mejorar la calidad del software.
- Aumentar la productividad.

***Importancia de planificar el reuso:***
El reuso no debe ser utilizado ciegamente. Es fundamental que sea planificado y sistemático, para evitar problemas derivados de la integración de componentes no adecuadamente analizados. Es necesario evaluar las ventajas y desventajas en función de los requisitos del sistema.

***Escala del reuso de software:***

*Reuso de software*

1. **Sistemas o aplicaciones completas:**
	- Se reutilza el sistema en su totalidad, generalmente sin modificaciones. 
2. **Componentes o módulos:**
	- Se reutilizan subsistemas o componentes, integrandolos. 
3. **Clases y funciones:**
	+ Reúso más fino, a nivel de clases o funciones dentro del codigo.

*Reuso de conocimiento*

1. **Frameworks:**
	- Conjunto de herramientas y estructuras de diseño reutilizables que definen la arquitectura y el comportamiento del sistema. 
2. **Patrones de diseño:**
	- Son soluciones sistematizadas para problemas comunes en el diseño de software, que se han probado y documentado a lo largo del tiempo. 
3. **Arquitectura de referencia y modelos dde componentes:**
	+ Proveen un vocabulario y propiedades cualitativas para analizar y estructurar los sistemas. 


***Lecciones aprendidas en la práctica:***

1. **Reuso de barrido:** Copy paste de código de internet sin análisis previo.
2. **Reuso de salvación:** Es cuando se reutiliza software para compensar atrasos en el desarrollo. 
3. **Reuso planificado:** Debe ser analizado y justificado desde un punto de vista técnico. 

## Arquitectura de software:
***Que es:***
Define la estructura global del sistema, describiendo cómo se organizan y conectan los componentes del software. Esto incluye:
- **Elementos:** Los componentes de procesamiento, datos y los conectores entre ellos.
- **Forma:** Las propiedades e interacciones entre estos elementos.
- **Rationale:** La justificación detrás de las decisiones arquitectónicas. 
*Arquitectura = Elementos + Forma + Rationale*

***Evolución del concepto de arquitectura de software:***
- **Jan Bosch:** Conjunto de decisiones de diseño arquitectonico que afectan la estructura:
	- Agregann componentes
	- Imponen funcionalidad en los componente existentes
	- Agregan restricciones
- **Taylor, medvidovic y dashofy:** No todas las decisiones no son arquitectónicas, por ejemplo, usar "Merge sort" no es una decision de arquitectura.
***Por qué es importante?:***
Define como se organizan los esfuerzos del equipo, como se resuelven problemas de escalabilidad y rendimiento, y cómo se mantendrá el sistema a largo plazo.


## Stakeholders y concerns
**SH**: Son quienes tienen un interés en el sistema, como: 
- Usuarios
- Clientes
- Desarrolladores
- Operadores
**Concerns:** Preocupaciones o intereses de los SH que deben ser resueltas en el diseño de la arquitectura. 

## Del problema a la solución
**El espacio del problema:** Representa los conceptos y relaciones que definen el dominio del sistema. Se define mediante:
- Modelos de dominio
- Historias de usuario

**El espacio de la solución:** El espacio de la solución incluye las posibles opciones de diseño para resolver el problema. Pueden tener ventajas y tradeoffs. 

## Evaluación de arquitectura
***Que es:***  Consiste en determinar si es adecuada para los objetivos y requisistos del sistema, esto mediante métodos y escenarios de evaluación

**Métodos comunes de evaluación:**
1. **Escenarios de validación:** Justificar cómo las decisiones arquitectónicas soportan los requisitos. 
2. **Evaluación de patrones y atributos:** Determinar si el patrón arquitectónico elegido satisface las propiedades deseadas.
3. **Desafíos de las decisiones:** Atacar las decisiones arquitectónicas y defenderlas ante un grupo crítico.

## Estilos de arquitectura de software
***Que es un estilo arquitectónico:*** Familia de sistemas que comparten ciertas características estructurales y propiedades de comportamiento. 

Es importante estudiar estilos porque:
1. **Comunicaciones efectivas:** Facilitan el entendimiento entre arquitectos.
2. **Previsión de propiedades sistemáticas:** Como rendimiento, seguridad, mantenibilidad, etc. 
3. **Evitar combinaciones arbitrarias de componentes:** Lo que reduce complejidad y mejora la escalabilidad. 

***Ejemplos comúnes:***
- **Monolítico:** Todo el sistema en una unidad, pero dificil de escalar. 
- **Cliente-servidor:** Separación entre el cliente y el servidor.
- **Microservicios:** Descomposición en servicios pequeños, autónomos y desacoplados. Ideal para escalabilidad.
- **Pipes and filters:** Flujo de datos procesados en etapas (filtros), común en procesamientode datos o imágenes.
- **Event-Driven:** Los sistemas reaccionan a eventos. Ideal para sistemas asíncronos y distribuidos.
- **Layered:** Separación en capas: Presentación, lógica de negocio, acceso a datos. Muy común en web-apps.
