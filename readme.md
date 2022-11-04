#Strategy:
permite establecer en tiempo de ejecución el rol de comportamiento de una clase.
 Stretagy se basa en el polimorfismo para implementar una serie de comportamientos que podrán ser intercambiados durante la ejecución del programa,
 logrando con esto que un objeto se pueda comportar de forma distinta según la estrategia establecida.


#singleton:

 El patrón de diseño Singleton (instancia única) está diseñado para restringir la creación de
 objetos pertenecientes a una clase o el valor de un tipo a un único objeto.
 Su intención consiste en garantizar que una clase sólo tenga una instancia y proporcionar un punto de acceso global a ella.

#proxy: 
nos permite realizar ciertas acciones antes y después de realizar la acción deseada por el usuario.

#prototype:
Permite la clonacion de objetos los cuales estan creados mediante un pool de prototipos
Este patrón es especialmente útil cuando necesitamos crear objetos basados en otros ya existentes o cuando se necesita la creación de estructuras de objetos muy grandes, este patrón nos ayuda también a ocultar la estrategia utilizada para clonar un objeto.


#observer:

El patrón Observer se basa en la idea de centralizar la tarea de informar en manos del sujeto.
 Para conseguirlo, existe una lista en la que los observadores pueden registrarse. En caso de modificación, el sujeto los informa uno tras otro, sin necesidad de que los observadores lo pidan activamente.


#model view controller:


Es una herramienta compuesta de modelo-vista-controlador, que permite la separación adecuada de cada uno de los componentes en objetos,
y evita que estos se junten, por lo que no pueden estar dentro de una misma clase.
En pocas palabras, funciona para clasificar, la lógica del sistema y la interfaz que el usuario ve


#memento:

Este patron captura el estado de un objeto en un momento determinado con la finalidad de retornar ese estado en cualquier momento.

es utilizado cuando tenemos objetos que cambian en el tiempo y por alguna razón necesitamos restaurar su estado en un momento determinado.



#factory:

sirve para crear objetos sin tener que especificar su clase precisa.
  Esto quiere decir que el objeto creado puede intercambiarse con flexibilidad y facilidad.
El objeto real creados es enmascarado detrás de una interface común entre todos los objetos que pueden ser creado, 
con la finalidad de que estos pueden variar sin afectar la forma en que el cliente interactúa con ellos. 



#facade:


El objeto real creados es enmascarado detrás de una interface común entre todos los objetos que pueden ser creado, con la finalidad de que estos pueden variar sin afectar la forma en que el cliente interactúa con ellos. 



#dependency injection:


Tambien conocido como el patron del contenedor, tiene la funcion de proporcionar los objetosw necesarios para la creación o elaboración de un objeto más complejo
  



#decorator:

Permite estructurar tu lógica de negocio en capas, 
crear un decorador para cada capa y componer objetos con varias combinaciones de esta lógica, durante el tiempo de ejecución. El código cliente puede tratar a todos estos objetos de la misma forma, ya que todos siguen una interfaz común.


#data access object:

Independiza la aplicación de la forma de acceder a la base de datos, o cualquier otro tipo de repositorio de datos.
es un componente de software que suministra una interfaz común entre la aplicación y uno o más dispositivos de almacenamiento de datos, 
tales como una Base de datos o un archivo.


#command:


funciona para convertir una solicitud en un objeto independiente que contiene toda la información sobre la solicitud. Esta transformación te permite parametrizar los métodos con diferentes solicitudes, retrasar o 
poner en cola la ejecución de una solicitud y soportar operaciones que no se pueden realizar.


#abstract factory:

Permite crear y producir familias de objetos relacionados sin necesidad de especificar sus clases concretas
