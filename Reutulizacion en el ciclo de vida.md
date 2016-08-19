# Reutilización en el ciclo de vida

Podemos realizarla cuando:

- Cuando importamos librerias alimentadas por terceros
- Cuando tenemos dos modulos de una misma aplicacion (Estilos, header, footer).
- Existen similitudes entre dos aplicaciones diferentes (cuando tenemos desarrollado .
	un codigo para administrar un supermercado y decidimos adaptarlo a un restaurante)
- El diseño de aplicativos = especificar modulos + interrelaciones entre ellos.
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

imagenes: http://www.inouthostel.com/wp-content/uploads/Reutiliza2.jpg
			https://xgfk10csj.files.wordpress.com/2010/11/gp_lizenz.jpg


# Síntesis automatica del software

imagenes: https://procesosoftware.wikispaces.com/file/view/1990s32.jpg/268203978/800x211/1990s32.jpg

- Se definen los requisitos informales

Este modelo, propuesto por Robert Balzer en 1983, aplica una serie de 
transformaciones usando un soporte automatizado para convertir una 
especificación formal (modelo matemático) en un sistema implementable 
(ejecutable). Es decir, este paradigma intenta automatizar las etapas 
de diseño e implementación utilizando el concepto de transformación. 
También se denomina a este paradigma Síntesis Automática de Software.

Fases:

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
		a. Planificación: se evaluan requerimientos (analisis inicial del software)
		b. Investigación: se buscan tecnologias vinculadas al diseño y Construcción
		c. Especificación: se realiza el detalle del diseño de los elementos 
			implementados en el software
		d. Implementación: Se efectua la construccion del software
		e. Revisión: Pruebas
	- Entrega garantizando su funcionalidad
	- Periodos
		a. Crecimiento:  se construye el sistema
		b. Madurez: mantenimiento del producto

imagenes: http://3.bp.blogspot.com/-ys_bK8WaRrA/T61OUjmFm1I/AAAAAAAAALo/DlQBW-8QZio/s1600/Orientado+a+Objetos.png

- Modelo Agrupamiento: grupo de clases relacionadas
	cada modulo maneja su cilo de vida
	- Subciclo de vida: 
		- Especificación: identificar requerimientos
		- Diseño: Establecer modelos de soluciones
		- Implementación: Se construye el software
		- Verificación/Validacion: garantizando calidad
		- Generalizacion: Repetir exitos

imagenes: http://kerncountylibrary.org/wp-content/uploads/2015/04/Puzzle-pieces.jpg

- Modelo Remolino: nos ofrece una vision multiciclica
	dimenciones:
	- Amplitud: ¿cuantos elementos lo compondrian?
	- Profundidad: ¿que nivel de abstracción empleará?
	- Alternativa: soluciones a bugs
	- Alcance: hasta donde se quiere llegar considerando cambios

imagenes: http://xn--quesignificasoarcon-83b.com/wp-content/uploads/2015/04/remolino-negro-con-blanco-842616.jpg


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

imagenes:  https://houstonagentmagazine.com/wp-content/uploads/2012/06/pinball.jpg


