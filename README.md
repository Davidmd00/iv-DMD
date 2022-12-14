# Gestión de un centro de estética

### Problema a resolver:
En un centro de estética es muy importante la gestión de los distintos tipos de citas, ya que cada una requiere una duración distinta dependiendo del tipo de tratamiento que se necesite. El problema aparece si no tenemos una buena gestión de las citas y no controlamos de manera precisa el tiempo de duración de cada cita o la capacidad de improvisar ante contratiempos inesperados como la avería de aparatos o gente que falte a su cita, ya que esta mala gestión conlleva a la disminución tanto de clientes como de beneficios por parte del centro.

Otro problema aparece si no hacemos un buen cálculo del inventario y no podemos predecir la cantidad de productos que necesitaremos para las citas que daremos en las próximas semanas.


### Como solucionarlo:
La solución consiste en crear un sistema de citas automático para ajustar cada cita en el tramo horario más adecuado dependiendo del tipo de tratamiento que se vaya a dar y diversos factores como las citas anteriores o los productos que vayan a utilizarse. El cliente elegirá el día que desea la cita, y si la prefiere por la mañana o por la tarde.

### Lógica de negocio:
Se creará un algoritmo que reconocerá el tipo de cita y calculará el tiempo aproximado de duración, teniendo en cuenta factores como el tiempo de preparación, si es necesario encender y calentar previamente alguna máquina, si las máquinas ya están listas por la cita anterior, el número y especialización de los trabajadores ese día, etc. Pero en el cálculo también influirán factores que no podemos predecir exactamente pero debemos tenerlos en cuenta, por lo que se contará con registros que indiquen la probabilidad en que las máquinas suelen fallar, qué productos suelen acabarse antes, qué día de la semana y a que hora suele ausentarse más la gente que pide cita, que día de la semana acude más gente sin cita previa, etc.
Para el inventario se llevará un contador de cada producto del centro que irá cambiando dependiendo de sus usos en las citas a lo largo de la semana, teniendo en cuenta los que se usarán en las citas reservadas para no quedarse sin stock.
  
  
* [Clave: ](Configuracion/clavepublica.png)
* [Configuración: ](Configuracion/config.png)
