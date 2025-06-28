## Que es SCM?
Es el conjunto de procesos, herramientas y buenas prácticas que permiten:
- **Controlar y gestionar los cambios** que sufre un sistema de software a lo largo del tiempo.
- **Evitar el caos** en proyectos donde múltiples personas modifican el mismo software.
- **Garantizar trazabilidad, integridad y control** sobre versiones y configuraciones del producto.

***Objetivo principal:***
Permitir que el software evoluciones ordenadamente sin perder el control sobre sus versiones, componentes y doocumentación. 

***Problemas sin SCM:***
- Cambios descontrolados
- Versiones perdidas
- Errores que se propagan
- Dificultades para colaborar.

**Hay que evitar impacto negativo al hacer cambios**

***Beneficios del SCM:***
- Reduce trabajos duplicados
- Coordina  cambios concurrentes entre varios desarrolladores
- Asegura trazabilidad de cambios 
- Facilita recuperación ante errores
- Mantiene registros de quien hizo qué, cuándo y por qué

***Elementos de un SCM:***
1. **Componentes:**
	- Herramientas para almacenar, acceder y versionar ítems de configuración. 
2. **Elementos de proceso:**
	- Actividades y procedimientos que definen cómo se gestionan los cambios.
3. **Elementos de construcción:**
	- Automatización para construir versiones del software de manera confiable y repetible.
4. **Elementos humanos:**
	- Roles y responsabilidades del equipo para ejecutar correctamente el SCM.

***Repositorio SCM:***
Es como una base de datos del proyecto que permite:
- Guardar todas las versiones del coodigo
- Registrar cambios y metadaos
- Integrarse con otras herramientas de desarrollo.
Ofrece soporte para:
- Versionado
- Gestión de cambios
- Auditoría
- Trazabilidad de requerimientos

***ICS:***
- Todo objeto relevante para el desarrollo, como código fuente, especificaciones, casos de prueba, documentación, etc.
- Pueden ser productos completos o parte de ellos.
- Deben estar identificados, controlados y trazados.

***Preguntas clave que responde SCM:***
1. Cómo identificar los ítems de configuración.
2. Cómo gestionar versiones y documentación.
3. Cómo controlas cambios antes y después de liberar el software.
4. Quień aprueba los cambios.
5. Cómo asegurar que los cambios se hicieron correctamente.
6. Cómo informar a otros del cambio.

***Capas del proceso de SCM:***
1. **Identificación:** Nombrar y organizar cada ítem.
2. **Control de versiones:** Usar un repositorio, asignar identificadores a cada versión, permitir reconstrucción completa.
3. **Auditoría de configuración:** Validar que los cambios fueron correctos, documentados y aprobados. 
4. **Reporte de configuración:** Qué, Quién, Cuándo, Qué afecta.

***Planificación del SCM:***
**Etapas clave:**
1. *Identificar configuración:* 
	- Buscar límites del sistema y evitar gestionar lo innecesario.
	- Componentes comunes: Código, pruebas, requisitos.
2. *Definir baselines:*
	- Un baseline es una versión oficial y estable.
	- Cambiarla requiere procedimientos formales. 
3. *Controlar configuración:*
	- Aplicar reglas y procesos para que los cambios no introduzcan errores.
4. *Registrar estado:*
	- Mantener un historial completo de entregas, cambios y versiones.
5. *Auditar y revisar:*
	- Validar que los entregables cumplen con lo acordado.

***Versiones vs entregas:***
- *Gestión de versiones:* Se enfoca en nombrar y mantener versiones diferenciables del software.
- *Gestión de entregas:* Asegura que las versiones correctas se empaquetan y se distribuyen formalmente. 
