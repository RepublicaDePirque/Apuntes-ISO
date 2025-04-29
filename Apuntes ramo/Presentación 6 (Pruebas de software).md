*Porque falla el software:*
- Requisitos equivocados
- Requisitos faltantes
- Requisitos imposibles
- Diseños con defectos
- Código con defectos
- Diseño incorrectamente implementado

***Contexto:***
- *Error:* Acción humana que impacta en el software.
- *Defecto:* Existe en el codigo y puede causar una falla.
- *Falla:* Ocurre cuando un programa no se comporta adecuadamente.
- *Verificación:* Estamos construyendo el producto correctamente?
- *Validación:* Estamos construyendo el producto correcto?
	- Demostrar que los requisitos establecidos han sido implementados existosamente
	- Pruebas exitosas -> Sistema funciona como se había establecido.
- *Caja negra:* Funcionalidad de los componente inspeccionada perimetralmente.
	![[Pasted image 20250426112037.png]]
- *Caja blanca:* Se conoce la estructura interna de los componentes.
	![[Pasted image 20250426112113.png]]
***Diseño:***
**Casos de prueba:**
- Conjunto de entradas, condiciones y resultados esperados diseñado para conseguir un objetivo particular o condición de prueba.
- *Se requiere:* 
	- Definir escenarios
	- Identificar condiciones de entrada
	- Identificar salidas
	- Ejecutar las pruebas
![[Pasted image 20250426112354.png]]

- *Que casos tienen más probabilidad de detectar defectos?*
	- Mala idea sería hacerlo de manera aleatoria
	- Existen métodos para apoyar el diseño de forma más inteligente y sistemática. 
- *Metodos:*
	- *Caja negra:*
		- Particiones de equivalencia
		- Análisis de valores frontera
		- Adivinanza de defectos
	- *Caja blanca:* 
		- Cobertura de sentencias
		- Cobertura de decisiones
		- Cobertura de condiciones
- *10 principios:*
	1. Una parte necesearia de un caso de prueba es la definición de los resultados esperados
	2. Un programador debe evitar ser el propio tester
	3. Una organización debería evitar se los testers de su propio codigo
	4. Cualquier proceso de prueba debe incluir una revisión rigurosa de los resultados de cada prueba
	5. Los casos de prueba deben ser escritos considerando condiciones invalidas e inesperadas pero también validas y esperadas.
	6. No solo hay que verificar si el programa NO hace lo que debe hacer, sino que también HACE lo que NO debería hacer.
	7. Evitar el diseño de casos de prueba desechable a menos que el siftware sea también desechable
	8. No planificar un proceso de pruebas pensando que no se vana a encontrar defectos
	9. La probabilidad de identificación de nuevos defectos en una sección de un programa es proporcional al número de defectos ya encontrados en dicha sección
	10. Las pruebas de software son creativas e intelecualmente deafiantes.

***Proceso de pruebas:***
- *Que defectos debería descubrir?*
	- Algoritmos
	- Precisión y cómputo
	- Documentación
	- Capacidad o límites
	- Rendimiento
	- Acorde al estandar
	- Etc.
- *Políticas de pruebas:*
	- Solamente una prueba exhaustiva de prueba puede msotrar que un sistema está libre de defectos.
	- Las políticas de pruebas definen los enfoques que deben ser utlizados al momento de seleccionar las pruebas de un sistema.
- *2 enfoques:*
	- Prueba de componentes: Se verifica cada componente / Se analiza la responsabilidad del desarrollo del componente / Las pruebas se realizan de la experiencia de los desarrolladores.
	- Prueba del sistema: Se hace prueba a un grupo de componentes integrados / La responsabilidad dser traspasa a un equipo / Los test se basan en la especificación del sistema.

***Tipos de pruebas:***
- *Prueba del sistema:* Involucra la integración de componentes para crear sistemas. 
	- Se definen 2 fases:
		- Integración: Acceso  a todo el codigo fuente. El sistema es testeado en función de la integración de los componentes.
		- Entrega: El equipo de testing prueba el sistema completo para ser entregado como una caja negra.
- *Pruebas de integración:* Involucra la creación del sistema desde sus componentes y se hacern pruebas para identificar problemas que puedan surgir desde la integración de los componentes:
	- Integración top down: Desarrollo del esqueleto y se agregan componentes.
	- Integración bottom up: Integra la infraestructura de componentes y luego se le agregan funcionalidades.
- *Pruebas de regresión:* Es una selección completa o parcialde casos de prueba ya ejecutados que se vuelven a ejecutar para asegurar que las funcionalidades existentes del software operen correctamente.
	- Permiten identificar impactos negativos en el sistema debido a un cambio en algún componente

***Guías para el testing:***
- **STLC: Software testing life cycle**
	- *Plan de prueba:*
		- Plan estratégico de la pruebas
		- Analista QA determina el esfuerzo y costos estimados del proyecto y como se prepara y finaliza el plan
		- Actividades:
			- Preparación del plan
			- Selección de herramienta
			- Test de esfuerzo y estimación
			- Planificación de recursos y la determinación de funciones y responsabilidades
		- Entregables: 
			- Plan de pruebas
			- Estimación del esfuerzo
		- Necesidad:
			- Visión holisitca de todo
	- *Desarrollo de los casos de prueba:*
		- Involucra la creación, veriicación y trabajo de los casos de prueba
		- Se identican los datos de prueba
		- Actividades:
			- Creación de casos de prueba
			- Revisar las bases de los casos de prueba
			- Creación de datos de prueba
		- Entrgables: 
			- Casos/scripts de prueba
			- Datos de prueba
		- Necesidad:
			- Creatividad.
	  - *Configuración del ambiente de prueba:*
		  - La configuración del ambiente de prueba decida las condiciones del hardware o software donde el sistema será probado.
		  - Actividades:
			  - Entender la arquitectura, configuración del ambiente y prepara el hardware y software por cad requisito que será probado.
			  - Realizar pequeñas pruebas del sistema
		  - Entregables: 
			  - Ambiente preparado con los datos de prueba establecidos
			  - Resultados de las pruebas
		  - Necesidad:
			  - Conocer la tolerancia del sistema de software.
	  - *Ejecución de la prueba:* 
		  - El equipo se preocupa del plan de prueba y los casos de prueba
		  - Cualquier detalle encontrado en las pruebas se debe reportar.
		  - Actividades:
			  - Ejecutar pruebas acordes al plan
			  - Documentar los resultados
			  - Mapear defectos a casos de pruebas establecidos
			  - Seguir los defectos
		  - Entregables: 
			  - RTM completa
			  - Casos de prueba actualizados
			  - Reporte de defectos
		  - Necesidad:
			- Paciencia
	- *Cierre de ciclo:*
		- Equipo de testing conoce y analiza los artefactos del testing con el objetivo de identificar estrategias que se pueden implementar a futuro.
		- Actividades:
			- Evaluar el ciclo completo basado en atributos como tiempo, costo, software, objetivos, etc.
			- Preparar métricas de prueba
			- Documentar lo aprendido en el proyecto
		- Entregable:
			- Reporte de cierre de pruebas
			- Métricas de prueba
		- Necesidad: 
			- Diplomacia
	- *Criterios de completitud de testing:*
		- Usualmente se abandona al agotarse los recursos. 
		- En la práctica no se acaba.
	

