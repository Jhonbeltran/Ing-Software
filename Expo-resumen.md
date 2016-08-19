# Reutilización en el ciclo de vida

Podemos realizarla cuando:

- librerias alimentadas por terceros
- Cuando tenemos dos modulos de una misma aplicacion 
- Existen similitudes entre dos aplicaciones diferentes
- Para aumentar el rendimiento de un sistema ya existente.

* Ventajas de la reutilizacion de codigo
	- Reduce tiempo y costes de desarrollo
	- Aumenta la fiabilidad
	- Mantiene la unidad (en el caso de una sola aplicacion)
	- Recordar la frase de "no volver a inventar la rueda"

 Problemas a la hora de implementar la reutilizacion de codigo
	- Dificultad para reconocer los componentes potencialmente reutilizables
	- Dificultad de catalogación y recuperación
	- Codigos escritos de forma poco legible (convencion sobre configuración)


# Síntesis automatica del software



Modelo propuesto por Robert Balzer en 1983, este paradigma intenta automatizar las etapas de diseño e implementación utilizando el concepto de transformación. 
También se denomina a este paradigma Síntesis Automática de Software.

Fases:

- Se definen los requisitos informales
- Análisis de requisitos
- Especificación formal (cada parte agrega detalle hasta que convierte 
		en un programa equivalente)
- Transformación
- Integración del sistema final


# Modelos para desarrollo de sistemas Orientados a Objetos

* Nace en la decada de los 90 como alternativa a las metodologias tradicionales
* Se centra en el producto y no en el proyecto (cada solicitud del usuario es 
	considerada un obejto)
* Su mantenimiento es mas sencillo, los cambios se realizan sobre los componentes

- Modelo fuente
	fases:

	- Planificación del negocio (fase de analisis y de estudio de las necesidades)
	- Construcción 
		a. Planificación: 
		b. Investigación: 
		c. Especificación: 
		d. Implementación:
		e. Revisión:
	- Entrega garantizando su funcionalidad
	- Periodos
		a. Crecimiento:  se construye el sistema
		b. Madurez: mantenimiento del producto


- Modelo Agrupamiento: grupo de clases relacionadas
	cada modulo maneja su cilo de vida
	- Subciclo de vida: 
		- Especificación: 
		- Implementación: 
		- Verificación/Validacion: 
		- Generalizacion: 


- Modelo Remolino: nos ofrece una vision multiciclica
	dimenciones:
	- Amplitud: ¿cuantos elementos lo compondrian?
	- Profundidad: ¿que nivel de abstracción empleará?
	- Alternativa: soluciones a bugs
	- Alcance: hasta donde se quiere llegar considerando cambios


- Modelo pinball

	- La pelota representa un proyecto completo o un subproyecto.
	- El jugador es el equipo de desarrollo.
	- Se procede de forma iterativa a encontrar clases, atributos
	métodos e interrelaciones y definir colaboraciones, herencia,
	agregación y subsistemas.
	- Por último se pasa a la programación, prueba e
	implementación.
	
	Hay dos estilos a la hora de “jugar”:
	- Seguro: tecnologías y métodos probados.
	- Al límite: Mayor riesgo, más ventajas.
