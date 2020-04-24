# Java

## Aprendizajes, cosas por mejorar, comentarios y recursos

## General

- Se hablo de la historia de Java y todas sus caracteristicas como lenguaje de programación.
- Las características se comprendieron en su totalidad, lo reflejo las sesiones de simulación de entrevista.
- Durante en clase se mencionaron ciertas preguntas de Java que son comunes en entrevistas que fueron muy bien interiorizadas por los participantes.
- Se instalo el JDK para Java 8.
- Se hizo una explicación de manera detallada de tres conceptos clave de Java como lo son JDK, JRE, JVM. Durante las entrevistas se noto la comprension de este conceptos.
- Se hizo la configuración de variables de entorno para que programas identifiquen Java y tambien poder ejecutarlo desde la consola.
- Se utilizo Eclipse IDE para el desarrollo de aplicaciones con Java.
- Se escribio lógica de programación con la sintaxis de Java y toda sus propiedades que define.
- Previo a la introducción de escribir código orientado a objetos se hablo del analisis y diseño orienteado a objetos.
- Se hablo de los cuatro pilares de la POO (abstraccion, encapsulamiento, herencia y polimorfismo).
- Se realizaron varias practicas con Programación Orientada a Objetos.
- Se tomaron situaciones y objetos de la realidad para la realización de diferentes programas con enfoque orientado a objetos.

## Caracteristicas de Java
Write Once, Running Anywhere (WORA)

## JDK, JRE, JVM

- Uso de imagenes para demostrar las capas del JDK
![JDK_JRE_JVM Image](https://www.oracle.com/ocom/groups/public/@otn/documents/digitalasset/2167990.jpg)

### JDK

#### Bytecode
Se hablo del bytecode como el resultado final al compilar un codigo fuente Java que correra en una maquina virtual.

### JRE

#### APIs

### JVM

## Compilación 

- Se explico el proceso de compilación a través de un [recurso en linea](https://medium.com/@thelukaswils/understanding-compilers-for-humans-ba970e045877).

## Instalación de Java

- Buscar JDK en pagina oficial de Oracle
- Descargar archivo instalador y ejecutar programa en sistema operativo
- Configurar variables de entorno, actualizacion de Path y creacion de JAVA_HOME

## IDE
- Se explico que son este tipo de programas y todas las funciones que ofrecen al desarrollar software.

- Se desglosaron un conjunto de caracteristicas y funciones (escrito en el pizarron).

### Primer programa con Java

#### Estructura de un proyecto Java
- Se hizo enfasis en que es importante tener un orden en los proyectos manteniendo los archvos en carpetas.
- Creacion de carpetas (terminal)

#### Definición de un archivo con código Java

- Reglas para la creacion de un archivo hablando de su nombre y la extensión

- Se hizo uso de la terminal a través del shell de Git Bash para realizar este proceso.

#### Estructura basica de un programa Java

- El nombre de la clase debe ser el mismo que el del archivo
- Un programa debe estar en una clase
- Definición del metodo main
- Explicación de las partes de un main
- Instrucciones para dar salida de texto a consola (System.out.println)
- Programa que muestre en consola "Hola Mundo"
- Se compilo a través del comando javac (terminal)
- Se corrio a través del comando java (terminal)

### Basicos del lenguaje de programación Java

- Los basicos como definición de variables, tipos de datos y operadores se realizaron en terminal.

- Estructuras de control selectivas fueron realizadas en Sublime Text (todavia no se tenia un IDE)

#### Variables

- Se hablo de las convenciones validas para el nombramiento de una variable mediante un [recurso en linea](https://mathbits.com/MathBits/Java/DataBasics/Namingrules.htm).
- Se hablo de las variables o contantes y sus convenciones.

#### Datatypes

- Se hicieron programas demostrativos cubriendo la definicion y utlizacion de los diferentes tipos de datos.
- Se hizo un programa en consola con este objetivo a través de nano.
- Se hablo de la conversión de tipos de datos (casting).

###### Notas: 

- Se hizo enfasis en los 8 tipos de datos primitivos.
- Se dejo claro que un String no es un dato primitivo, es una clase.
- No se mencionaron los rangos de valores de los tipos de datos (pendiente).
- Valores predeterminados en las variables.

#### Operators

- Se utilizo SublimeText para la creación de archivos y desarrollo de programas.
- Se hablo de los diferentes tipos de operadores.
- Se hizo un programa para demostracion con operaciones sobre valores.
- Variables con tipos de datos y literales.
- Se hizo la compilacion y la ejecucion del programa (terminal).

#### Flow controls

- Se hizo uso de un IDE para desarrollar: Eclipse
- Se explico que es eclipse.
- Se dieron instrucciones de localización y descarga.
- Se dieron instrucciones de descompresion y creacion de acceso directo.
- Se ejecuto eclipse.
- Se explico las distintas funciones, ventanas y perspectivas para trabajar en eclipse.
- Se hablo del proceso de compilacion y ejecucion de un archivo Java en eclipse.
- Se explicaron los diferentes tipos de estructuras de control selectivas.
- Se hizo la introducción a maneras de obtener entrada de usuario.
- Se hablo de creacion de objetos a través de clases (parcial).

#### Loops

- Se hablo de los distintos tipos de ciclos.
- Se hicieron ejemplos demostrativos utilizando los 3 ciclos.
- Se hizo uso de programas con entrada de usuario.

#### Functions

- Se hablo de funciones haciendo una mezcla con ciclos.
- Se definieron funciones sin parametros, con parametros, con tipos de parametos, con retorno o sin retorno.
- Se invocaron funciones
- Se invocaron funciones con argumentos.
- Se proceso el retorno de una funcion.
- Se llamaron funciones dentro de otras funciones (reutilizar). 
- Se crearon funciones para la reutilizacion de comportamientos o subprogramas.
- Se explico el tipo de retorno void.
- Se hablo de la recursividad, una funcion que se llama a si misma.
- Se hablo de una call stack a través de un recurso en internet.
- Se hizo un ejemplo de recursividad.

## Fundamentos de Orientado a Objetos

- Se comenzo hablando sobre lo que es el analisis y diseño orientado objetos.
- Se introducio al enfoque orientado objetos
- Se mencionaron los 4 pilares del enfoque orientado a objetos.
- Se hizo una practica donde a todos los participantes se les pregunto que fueron los conceptos de abstraccion y polimorfismo con ejemplos rapidos.
- Se hablo de UML como lenguaje para diseño un problema OO.
- Se hizo la utilizacion de los recursos del programa pasado para la explicación del enfoque OO y UML.
- Se hablo de interfaces.
- Se hizo un ejercicio de herencia.
- Se realizo una actividad en parejas para el analisis de un problema con el objetivo de practicar el enfoque OO.
- Se compartieron plantamientos de problemas para trabajo opcional.
- Se definio un problema de una plataforma online y se comenzo a realizar el analisis con un efoque OO.

- Se utilizo una metodologia de identificar primero todos los sustantivos. Los datos se escribieron en un editor de texto.
- Se categorizaron los sustantivos que fueran caracteristicas de objetos para crear clases.
- Se identificaron acciones con verbos en infinitivo para definir metodos para las clases.
- Se comenzo a darle diseño al sistema usando notacion UML.
- Se utilizo una plataforma en linea para el diagramado con notacion UML.
- Se dio una explicacion de la interfaz y las figuras que se pueden utilzar.
- Se utilizaron las figuras de notacion UML.
- Se crearon clases en notacion a partir del analisis previo.
- Se agregaron atributos de las clases.
- Se hablo del nivel de acceso para los miembros y como se denota con los simbolos de UML.
- Se decidieron los tipos de datos para los atributos. Tipos de datos primitivos y objetos de clases asi como arreglos de referencias.
- Se decicidio el nivel de acceso de los metodos, si reciben o no parametros y tipo de retorno (void, type).
- Se identificaron tipos de relaciones, pueden ser asociacion, generalizacion, agregación, composición, realizacion y dependencia.
- Se señalaron con el simbolo correcto de UML.
- Se señalaron dominios de cardinalidades (1-1, 1-*, *-1, 1-4, *-*, 1..*-1, 0..* - 1)
- Se le dio un acomodo final al diagrama.
- Al final los diagramas que crearon fueron con diseño de implementación.

###### Notas: 
- Los participantes vieron la importancia de ver un problema con un analisis y un diseño orientado a objetos. 
- También queda de experiencia el no tratar de hacer algo muy grande para la demostracion desde la primera vez (fueron 18 clases).
- Los conceptos de abstracción y encapsulamiento trabajarlos para futuro para dejarlos mas claros.

## Programacion Orientada a Objetos


### Class

- Se creo un nuevo proyecto en eclipse para la creacion de las clases del diagrama anterior.
- Partiendo de una clase en notación UML se creo la estructura en un archivo de Java.
- Se dieron instrucciones de creacion de una clase. Esta clase no tendra un metodo main.
- Se explico la definicion de una clase en Java.
- Se explico que es y la importancia del nombre de la clase.
- Se hablo de los niveles de acceso.
- Se explico la sección de declaracion de atributos.
- Se hablo de variables de clase y variables de instancia.
- Se explico que es el metodo constructor, como se estructura y las reglas que deben seguir, además, los tipos de constructores.
- Se hablo de el constructor parametrizado el envio de parametros y la asignacion de los atributos de la clase.
- Se hablo de la palabra reservada this y sus usos en un constructor.
- Se hablaron de los metodos getters y setters y su importancia.
- Se definio las reglas que siguen los metodos getters y setters.
- Se hablo de la definicion de un POJO.

### Object

- Se explico el proceso de la instanciación de una clase (crear objeto).
- Se hablo de new y su comportamiento a través de un metodo constructor.
- Se crearon objetos a través de los diferentes tipos de constructores.
- Se inicializaron atributos a través de los metodos setters.
- Se obtuvieron los valores de los atributos mediante los metodos getters.


### Inheritance

- Se explico como implementar el concepto de herencia en Java a través de la palabra extends.
- Se definieron las clases hijas para aplicar herencia.
- Se hablo de como hacer referencia a los atributos de la clase padre y metodos a través de la palabra reservada super.
- Metodos constructor del padre y sus atributos.
- Se hizo el cambio de modificador de acceso a protected para la visibilidad de las clases hijas.
- Se utilizo un recurso en linea de la documentación oficial para la explicación y comprensión y por que/donde utilizarlos.
- Se hizo el llamado de los diferentes constructores del padre en la clase hija para inicializar los valores del padre.
- Se hablo de la clase Object como la clase padre de toda clase en Java de manera implicita.
- Se hablaron de los metodos de Object.

#### Override methods

- Se hablo de la sobre-escritura de metodos.
- Se hablo como sobre-escribir en Java paso a paso.
- Se sobre-escribio el metodo toString.
- Se genero un formato de string en el metodo toString para salida en consola.
- Se hizo la prueba de la salida mandando el objeto completo a la instruccion de salida.
- Se solicito a los participantes la creacion de dos clases mas del problema anterior basandose en el diagrama.

#### Relationships

- Se hizo la asociacion de una clase con otra a través de un metodo en una clase.

- Se crearon mas objetos de las clases nuevas.
- Se crearon metodos en la clase main para separar la logica de la creacion de objetos y mostrarlos en consola.
- Se hizo la implementacion para tomar datos por teclado para crear un objeto con datos dinamicos.
- Se recalco la importancia de un constructor para crear una instancia de la clase.
- Se hablo mas a detalle del proceso de instanciacion y reserva de memoria.
- Se hablaron de conceptos como Stack, Heap y String Pool en Java.

###### Notas:

- Importante darle enfasis a un metodo constructor, getters y setters.
- Al explicar this y super genera dudas (prepararlo).
- Los modificadores de acceso la compresión se dificulta (prepararlo).
- La anotación @Override causa confusiones hablando de la sobre-escritura (prepararlo).
- Terminos como encapsulacion y encapsulamiento causan problemas, hablando en que lado de la clase se ve reflejado eso (interno).
- Diferencia entre los metodos accesos public, private, protected.
- Se hizo una explicación de la reserva de memoria en Java (prepararlo mas).
- Trabajo con variables de clase y de instancia para explicar (prepararlo).

### Polymorphism and Abstract Classes

- Nuevo proyecto para la demostración de los conceptos.
- Se le pidio a los participantes que definieran la abstaccion del problema.
- Se identificaron clases y sus relaciones.
- Se fueron definiendo tipos de clases; padre, hijas, interfaces y clases abstractas.
- Se hizo un diagrama con diseño conceptual UML.
- Se creo clase padre con atributos y metodos.
- Se creo una clase hija para realizar herencia.
- Se realizo herencia a través de extends.
- Se crearon metodos constructores de la clase hija que recibieran valores para los atributos heredados.
- Se hizo referencia a los metodos constructor del padre pasando los parametros.
- Se creo una interface.
- Se explico como definir una interface en Java.
- Se hablo lo que es una interface de nuevo pero ya con un enfoque en Java.
- Se hablo el objetivo final de una interface.
- Se recalco que las interfaces son solo definicion de metodos (que tiene que hacer).
- Cascaron del comportamiento.
- Se hablo de variables staticas y finals que definen las interfaces (variables de clase).
- Se dijo que los metodos se les llama abstractos.
- se explico que una interface es una clase pero de puros metodos.
- Las interfaces se implementan.
- Se creo una nueva clase para hacer la implementación de la interface.
- Se definio los metodos a sobre-escribir a través de @Override.
- Se hizo una implementación del metodo de la interface dependiendo el tipo de la clase.
- Se creo una clase para la composición de un objeto de la interface para realizar el comportamiento de manera polimorfica.
- Se hablo de polimorfismo dinamico.
- se hablo de asignamiento polimormico.
- Se crearon instancias de la clase de la interface a través de constructores de clases que implementaron la interfaz.
- Se crearon instancia de la clase que implemento la interfaz.
- Se pasaron a un constructor para la inicializacion de los atributos.
- Se observo el polimorfismo dinamico al mandarle un objeto que implementa la interface.

#### Abstract Class

- Se hablo de clases abstractas.
- Se explico la manera de crear un clase abstracta a través de la palabra reservada abstract.
- Se hablo de que una clase abstracta define metodos abstractos (al menos uno).
- Define atributos y tambien metodos que no son abstractos.

###### Notas:

- Se hizo la utilizacion de un recurso externo para explicar el tamaño de los tipos de datos primitivos y el rango de valores que pueden almacenar.
- Siempre es bueno abrir la posibilidad de que los participantes creen el problema para realizar la abstraccion. Esto da posibilidad de dimensionar el alcance de lo que se esta aprendiendo.
- Al ser un ejemplo abierto despierta y mantiene una dinamica entre los participantes.
- Hablar de tipos de polimorfismo (static and dynamic)
- Se menciono las diferencias de las interfaces y las clases abstractas.
- Se le pidio a los participantes la crecion de una clase que implementara la interfaz recien realizada.
- Se hablo del polimorfismo estatico (sobrecarga) y polimorfismo dinamico (sobre escritura).
- Se hizo un repaso profundo de las interfaces y clases abstractas.
- Se dio espacio para hablar las diferencias de una interfaz de una clase abstracta, se creo una tabla comparativa.
- Se utilizo un recurso externo para mostrar las diferencias de estas dos.
- Es importante el profundizar mas la razon del por que una interfaz o una clase abstracata (preparar).

#### Packages

- Se hablo de la manera de organizar las clases de Java a través de paquetes.
- Se vieron convenciones para definir nombres a paquetes, se utilizo un [recurso en linea](https://docs.oracle.com/javase/tutorial/java/package/index.html).
- Se hablo de que los paquetes categorizan un conjunto de clases que engloban una funcion.
- Se hablo de las importaciones a través de la palabra import.
- Se hizo la explicación sobre como hacer la importación de clases desde otros paquetes (import).
- Se explico como hacer la navegacion para importar una clase o muchas clases desde un paquete.

###### Notas: 

- Falto hablar de importaciones estaticas.

### Error handling

#### Throwable, Errors, Exceptions and try-catch-finally block

- Se ocupo un espacio para hablar de los errores y las excepciones, además, como controlar las excepciones.
- Se hablo de las interrupciones inesperadas de una aplicacion Java llamados Throwable.
- Se hablo de lo que es un Error y algunos casos de cuando puede pasar, además del por que.
- Se hablo de las excepciones que son, por que son importantes y sus tipos.
- Se hablo de los tipos de excepciones: checked y unchecked.
- Se hablo de cuando sucede una excepcion de tipo checked y algunos ejemplos de estas.
- Se hablo de excepciones unchecked y algunos tipos de estas.
- Para el manejo de excepciones se hablo del bloque try-catch, uso e implementacion.
- Se explico por que utilizarlo y en que consisten sus partes.
- Se hablo que un bloque try-catch contiene las excepciones para no detener la ejecucion de una aplicación Java.
- Se hablo que un buna instruccion try puede ir seguido de muchos catch para varias excepciones.
- Se hablo que un bloque try-catch tiene un finally como un bloque de código final a ejecutarse.
- Se dio un repaso de errores y excepciones para aprovechar la definición de una propia excepcion.
- Se hablo de las palabras throw y throws para la creación  y delegación de la excepcion por un metodo.
- Se hablo que la creacion y delegacion de excepciones tiene el objetivo para el quien implemente el código tiene que manejarla, hablando de creacion de API.


###### Notas:

- Estos temas fueron agregados como un extra para los participantes, debido a que es importante conocerlo para su formacion como desarrolladores Java.
- El tema fue digerible por parte de los participantes además de que vieron su utilidad e importancia.
- Se creo un ejemplo MajaderiaException para domostracion de su manejo con un bloque try-cath, como crearla y delegarla para su control.

### Collections

#### Data Structures

- Se hablaron de lo que son las estructura de datos.
- Se hablaron de propiedades de las estructuras de datos.
- Se hablo del problema hablando de lo que son los datos en la actualidad.
- Se utilizo un [recurso en linea](https://medium.com/free-code-camp/10-common-data-structures-explained-with-videos-exercises-aaff6c06fb2b) para apoyo.

##### Arrays and Matrices (fixed or statics)

- Se hablo de las estructuras de datos como arreglos o matrices.
- Se volvio a mencionar propiedades de los arreglos y matrices.
- Se hablo que los arreglos y matrices manejan tamaños fijos.
- Se hablo de estructuras de datos fijas.
- Se hablaron de las situaciones de la realidad y aplicaciones donde los datos son muchos.

##### Dynamic Data Structures

##### Linked Lists, Double Linked List (dynamic)

- Se hablo que es importante que los datos crezcan conforme se requiere.
- Se hablo de estructuras dinamicas.
- Se menciono lo que son las listas ligadas.
- Se hablo de lo que es un nodo.
- Se hablo de las partes de un nodo (valor, nodo apuntador).
- Se hablo que un valor puede ser cualquier cosa.
- Se hablo de los nodos parte de una lista (cabeza, cola).
- Se hablo que un nodo apunta a null como primera vez hasta que se enlaza.
- Se explico como es que se enlazan los nodos.
- Se hablo del como recorrer este tipo de estructuras.
- Se hablo de las operaciones basicas.
- Se creo un prototipo de implementacion en Java.
- Se hablo de listas doblemente ligadas.
- Se hablo de la propiedad de las listas doblemente ligadas.
- Se hablo de las propiedades de un nodo en este tipos de listas.
- Se hablo del nodo anterior y siguiente.
- Se explico que estas listas permiten avanzar hacia adelante como atras.
- Se le pidio a los participantes que vieras sus aplicaciones.
- Se hizo la implementacion de un nodo para la creacion de la lista en Java.
- Se hablo de las operaciones de listas asi como el avanzar y retroceder.
- Se hablo de las listas circulares.
- Se hablo que es una lista circular y sus aplicaciones.
- Se demostro como se ve una lista  circular.
- Una lista circular no tiene inicio o final, pero se puede indicar cuales son.

##### Stacks and Queues

- Se hablo de un tipo de listas como pilas o colas.
- Se hablo de las pilas y su nombre tecnico FIFO
- Se hablo del comportamiento de una pila con ejemplos de la realidad.
- Se ilustro como se ve una pila y como los elementos se van organizando.
- Se hablaron de las propiedades de una pila.
- Se determinaron las operaciones basicas de las pilas (push, pop).
- Se determinaron mas operaciones para manipulacion de los datos (peek, size, is_empty)
- Se mencionaron los usos en la computacion y programas.
- Se hablaron de las colas (queue) y su nombre tecnico LIFO.
- Se hablaron de situaciones de la realidad que son colas.
- Se ilustro como se ve una cola visualmente.
- Se hablo de como los elementos se van organizando conforme van llegando.
- Se definieron las operaciones basicas de las colas (enqueue, dequeue) para manipular los datos.
- Se hablo de operaciones extras para manipulacion de los datos en las colas (size, is_empty).
- Se hablo un tipo de colas que son las dobles.
- Se explico que las colas dobles son pilas y colas a la vez.
- Se explico que las colas dobles fucionan operaciones de las pilas y colas.
- Se explico que de las colas dobles se ingresan y sacan elementos al principio como al final.
- Se explico que listas, pilas y colas son estructuras de datos lineales.

##### Non-Linear Data Structures

##### Trees and Graphs

- Se explico que para otro tipos de problemas no es suficiente estructurar los datos de manera lineal.
- Se hablaron de las estructuras de datos no lineales.
- Se explico que son los arboles, sus usos en la computacion y por que se necesitan.
- Se explico como construir un arbol.
- Se explico de las partes de un arbol.
- Se hablo de que tienen nodos.
- Se hablo del nodo raiz.
- Se explico que el primer nodo raiz es conocido como padre.
- Se hablo de los nodos que salen de una raiz como hijos.
- Se explico que cuando un nodo tiene nodos hijo se vuelve padre.
- Los nodos hijos se conocen como hermanos.
- Se hablo que los arboles tienen niveles empezando desde la raiz hasta el ultimo nodo hijo.
- Se explico que los arboles tienen utilidad en busquedas.
- Se hablo que los arboles tienen recorrimientos.
- Se hablo de los recorridos preorden, inorden y postorden.
- Se le agrego un simbolo a los nodos para poder darle claridad al recorrido.
- Se hizo un ejemplo de recorridos con ayuda de los participantes.
- Se hablo que los datos no necesariamente van a tener solo un enlace.
- Se explico que existe otro tipos de problemas los cuales necesitan solución a través de la computacion.
- Se hablo de los grafos, sus aplicaciones y en que cosas estan utilizadas.
- Se ilustro visualmente como se construye un grafo.
- Se explico que los grafos son utilizados para encontrar caminos o soluciones mas optimas a problemas.
- Se explico que son los mapas con ejemplos de utilidades en la realidad.
- Se explico que un mapa constituye de una clave por la cual se accedera a un valor.
- Se ilustro visualmente un mapa con un ejemplo sencillo (agenda de contactos).
- Se hablo de las funciones hash para poder definir una clave unica.
- Se hizo enfasis en por que los participantes deben seguir aprendiendo estructuras de datos para su formacion como desarrolladores.

###### Notas:

- Se hicieron dibujos explicados en el pizarron.
- Se menciono que las estructuras de datos son abstracciones (caracteristicas y comportamientos) para crear clase y objetos.
- La recursividad en las estructuras de datos hace dificil el comprender como es que se pueden crear de esa manera y manipular.
- Trabajar en una explicación mas clara para poder hacer que se entienda que se tiene que anidar la estructura que permite almacenar datos y ligarlos a otros (nodo).
- No se menciono que el proceso de juntar dos nodos se llama enlazar, pero se hizo enfasis que se encadenan para hacer la cadenita.
- Los comportamientos de las pilas y colas son faciles de comprender con analogias de la realidad.
- Se utilizo un ejemplo de hotcakes para demostrar las pilas.
- Seria importante evidenciar por que no alcanza el estructuras los datos de manera lineal en la computacion (preparar).
- Se menciono pero no explico a detalle los ordenes de complejidad en las operaciones de las estructuras de datos(preparar).
- Si se busca hablar de los grafos preparar el tema, no se hablo de las lineas que son conocidas como aristas.

##### Framework Collections

- Se explico como el framework de collection de Java es un conjunto de clases abstractas, interfaces y clases finales (se utilizo un recurso adicional).
- Se explico como las estructuras de datos siguen comportamientos y de acuerdo al tipo de estructura es como realiza las operaciones.
- Se comenzo un nuevo proyecto de Java para la implementacion de clases de collections.
- Se creo un ejemplo para crear playlists de canciones.
- Se le pidio a los participantes que identificaran en el problema en que parte utilizar una estructura de datos.
- Se hizo la utilizacion de una estrucutura de datos List.
- Se indico en que paquetes se encuentran las clases de collections.
- Se agrego como atributo de una clase una lista para almacenar objetos.
- Se hablo del operador o simbolo diamante que permite indicarle a una clase en Java que contendra o manipulara tipos de objetos de una clase (generics).
- Se les explico a los participantes que metodos tienen la lista.
- Se definio un metodo para hacer el uso del metodo para agregar elementos a la lista.
- Se crearon objetos con el objetivo de almacenarlos en la lista.

###### Notas:

- En la utilización de collections por cuestiones de tiempo se hizo la implementacion mas compleja que es almacenar objetos cuando pudieron ser numeros, strings.
- Para el ejemplo se olvido inicializar el objeto de la lista aunque esto sirvio para que los participantes lo pudieran resolver.

##### I/O Streams

- Se hablo que en la computacion se manejan datos.
- Se hablo que esos datos tienen la representacion de ser bytes conjuntos de 1s 0s.
- Se hablo de que son los flujos de entrada y salida.
- Se hablo de una represantacion de flujos desde un archivo.
- Se hablo que un archivo es la unidad mas basica de almacenamiento.
- Se les hizo reflexionar a los participantes en como guardarian sus datos de su programa para que siguieran existiendo.
- Se hablo del tema de persistencia de datos.
- Se hablo de las clases OutputStream and InputStream como los conceptos principales de streams en Java.
- Se hablo que hay tipos de entradas y salidas de los streams.
- Se explico que para el problema se utilizaria un almacenamiento de datos en archivos.
- Se hablo de que los archivos son un almacenamiento fisico de datos.
- Se hablo que los programas que utilizamos crean archivos donde se escriben y leen datos.
- Se creo un metodo para realizar las operacion de guardado de los datos del objeto.
- Se hablo de la clase File como la responsable de poder manipular un archivo desde mi aplicacion Java.
- Se explico de donde obtener las clases para los streams (java.io).
- Se creo una instancia de File.
- Se definio una ruta para el archivo y un nombre, para la practica fue el mismo proyecto de la aplicación.
- Se hizo memoria para recordar que son las rutas absolutas y relativas.
- Se definio una extension para el archivo .txt.
- Se definio un formato para poder crear la ruta con el nombre de archivo mas su extension.
- Se creo una instancia de la clase File para manipular un archivo.
- Se hablo de que una instancia de la clase File no significa que se haya creado el archivo.
- Se explico que cuando se tiene un archivo se tiene que definir el flujo de su stream ya sea de entrada o salida.
- Los participantes identificaron que los datos tenian que guardarse en un archivo y es una operacion de salida.
- Se hablo de la clase FileOutputStream para darle destino a los datos como una salida.
- Se importo la clase desde el paquete especifico.
- Se explico a los participantes que al ejecutar esa linea se crea un archivo vacio.
- Se identifico que al escribir la linea marcaba un error el IDE debido a que el metodo arrojaba una excepcion por lo cuale se utilizo un bloque try-catch
- Se explico a los participantes que los datos de un archivo se guardan en bytes.
- Se identifico un problema en guardar los datos como se tenian.
- Se explico a los participantes que antes de darle salida o entrada a los datos se puede definir un paso intermedio que es procesarlos para darles un trabajo final.
- Se hablo de que hay tipos de procesadores de datos antes de ser parte de un origen o destino.
- Se utilizo un procesador de datos de objetos para guardar los datos como objetos.
- La clase utilizada se llamo ObjectOutputStream a la cual los participantes identificaron la manera en la que se puede crear una instancia de esta clase.
- Se identifico el constructor correcto para crear una instancia de acuerdo a los datos que se tenian.
- Para guardar los datos se le pidio a los participantes que identificaran el metodo adecuado para guardar un objeto.
- Se hizo memoria a los participantes de cerrar los streams através del metodo close.
- Al querer guardar los datos se tuvieron excepciones las cuales fueron solucionadas por parte de los participantes.
- Se consiguio el resultado de escribir los datos en un archivo, la reaccion de los participantes fue buena.
- Se le pidio a los participantes que hicieran el metodo para leer los datos identificando que la operacion ahora es de entrada.

###### Notas:

- Es importante un tema como este antes de ver collections de Java.
- Trabajar la introduccion a estructura de datos abarcandolo como la solución para manipular cantidades de datos.
- Importante trabajar el tema de streams para explicar de manera sencilla las diferencias de los flujos de entrada y salidas.
- Se les explico el temas de los streams a los participantes a través de que identificaran tipos de dispositivos en la computadora.
- Se determino que un flujo de entrada tiene un origen y un flujo de salida tiene un destino cual sea este.
- Importante mencionar desde el principio que un archivo consta de un conjunto de propiedades importantes (ruta, nombre, extension, tipo).
- Para la instanciacion de los objetos se le dio a los participantes que observaran los constructures disponibles para poder crear un objeto de acuerdo a los datos que tuvieran para completar los argumentos.
- Se tuvieron problemas al experimentar el guardar los datos como objetos.
- Para solucionar los problemas se tuvo que recurrir a internet y observar la documentacion para un ejemplo de utilizacion.
- Al implementar el guardar los datos como objeto se presentaron dificultades al correr el programa arrojando excepciones. La excepcion tenia que ver con el poder encontrar una manera para procesar los datos de los objetos, esto se soluciono agregando la intarfaz Serializable.
- En el trabajo de los archivos es importante tener cuidado con indicar la ruta correcta.



## Recursos adicionales
https://www.draw.io/
https://docs.oracle.com/javase/7/docs/api/java/lang/Object.html
https://docs.oracle.com/javase/tutorial/java/javaOO/accesscontrol.html
https://medium.com/sudotoons/intro-to-oop-abstraction-encapsulation-6d2919e82370
https://www.geeksforgeeks.org/difference-between-abstract-class-and-interface-in-java/
https://docs.oracle.com/javase/tutorial/essential/io/streams.html
https://docs.oracle.com/javase/7/docs/api/java/io/ObjectOutputStream.html


## Notas
Preparar diapositivas sobre los temas:

- **Object Oriented Analysis** (OOA)
- **Object Oriented Design** (OOD)
- **UML** [recurso en linea](https://docs.oracle.com/javase/tutorial/java/package/index.html) 