# LAS MOSQUETERAS


## La página de las mosqueteras ha sido creada con dos principales objetivos: darnos a conocer en el mundo digital y poner en práctica los conocimientos adquiridos en estas tres semanas de curso.

### Este proyecto ha sido maquetado con HTML y diseñado con CSS a través del procesador SASS.

#### Header
El header consta de dos elementos: el nombre de equipo y un "nav". Así hemos podido aplicar flex y ubicar dichos elementos como fuera necesario: el columna en versión móvil y fila para las otras dos. Al ubicarlo con position:fixed se ha conseguido que se mantenga en pantalla en todo momento, independientemente de la sección en que se esté.

#### Equipo
Para la disposición del lema y la sección de equipo, hemos trabajado con flexbox en las media queries y las propiedades de transform-translate y transform-rotate para incorporar un triángulo que aparece como una incisión en el margen superior del fondo gris que separa ambas partes.

#### Quienes somos
Para la version móvil hemos aplicado Flexbox column centrado en el eje secundario para que así todos los articulos quedasen centrados en la pantalla del dispositivo. En la version tablet los articulos se desplazan a izquierda y derecha posicionandose las fotos a los extremos, esto lo hemos conseguido aplicando de manera alterna flexbox row y row reverse. Para que el nombre, descripcion y los iconos quedasen en columna hemos tenido que envolverlos en otro contenedor y aplicar un flexbos colum. Al cambiar al dispositivo tablet vemos como el eje central donde antes se alineaban los articulos "se rompe" para irse definitivamente a izquierda y derecha de manera alterna. En este caso tuvimos que eliminar el eje principal de la sección para que los articulos quedase "libres" y se adaptasen automaticamente a los extremos de la pantall.


#### Footer
En todas las versiones hemos utilizado un display flex para distribuir los tres bloques en los que hemos dividido el footer. Para la versión móvil en columna y para la versión tablet y desktop hemos cambiado la dirección del conjunto a fila, para disponer los elementos de la manera que queríamos, a los lados. A su vez, en la versión tablet y desktop hemos añadido, al menú que te mueve por la pagina y a la pagina del contacto, otro display flex para que se coloquen uno debajo de otro.

#### Página de contacto
Para la página de contacto hemos decidido dividirlo en dos partes, la primera seria la parte del título y de un breve texto y en la segunda tendriamos ya la parte del formulario, el cual se divide en cuatro divisiones y un botón. Esta parte hemos decidido darle estilos con flex; en la parte de movil y tablet le hemos dado una dirección column, para así poder conseguir el efecto de cada elemento encima del otro, en cambio en la versión ordenador, nos encontramos con un pequeño inconveniente ya que  la división del teléfono tenía que estar al lado del email, para poder solventar este problema le dimos un flex pero en este caso row y asi conseguimos el diseño deseado.




