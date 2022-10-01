# Carta de restaurante interactiva

### Problema a resolver:
  En muchas ocasiones cuando vamos a un restaurante nos encontramos con el dilema de no saber qué plato pedir al no saber qué ingredientes lleva (principalmente la gente vegetariana o alérgica a algún producto), si el plato está disponible o no, cuanto tiempo tardará en prepararse, o las calorias y cantidad de comida en gramos que contendrá el plato, por lo que acabamos recurriendo a pedir el mismo menú de siempre y a desesperarnos porque no nos ponen de comer.



### Como solucionarlo:
  Esta carta interactiva mostrará fotos de todos los platos que se encuentren en la carta del restaurante, así como sus ingredientes y toda la información acerca de estos. Además, aparecerá un tiempo aproximado de preparación del plato en ese momento para que el cliente se haga una idea de cuanto deberá esperar. También aparecerá si el plato está disponible y cuantos platos han preparado de ese tipo en ese día, que nos indicará si es un plato popular en el establecimiento.

### Lógica de negocio:
  El tiempo de preparación de cada plato se calculará dinámicamente analizando cuantos cocineros hay en la cocina disponibles en ese momento o cuanto tiempo tardarán en ponerse a preparar dicho plato, cuantos fogones se encuentran disponibles, el tiempo de cocción, el tiempo del horno (que dependerá de si está ya caliente o no), el resto de comandas que hay antes, etc. También se irá calculando la cantidad de ingredientes disponibles en ese momento por si el plato dejara de 
estar disponible para servirse.
  
  
* [Clave: ](Configuracion/clavepublica.png)
* [Configuración: ](Configuracion/config.png)
