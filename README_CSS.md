# DOCUMENTACIÓN PRÁCTICA 3 - CSS

## Fuentes
- Se ha conseguido las fuentes necesarias a través de una página, ya que en Google Fonts, no he encontrado Source Sans Pro. Las he implementado y les he dado un nombre para luego poder usarlas en todo el `body`.

## Maquetación & Responsive

- Se ha utilizado `Flexbox` para la maquetación ya que `Grid` según he visto, es más potente, pero más complicado, y para unas páginas sin una necesidad muy grande de maquetación, con `Flexbox` sobraba. 
  
- Para hacer el responsive, se ha utilizado los `@media screen` con diferentes tamaños de pantalla. Se ha utilizado como ejemplo iPad, iPad Pro, iPhone 12 Pro, y iPhone SE. También se ha creado algún `@media screen` intermedio ya que así, sea cual sea el tamaño, se vería bien en todos los dispositivos.

## Cabecera

- Se ha realizado la cabecera tal como se indica en el enunciado.
- Al hacer el `position: sticky` se desplaza al hacer scroll todo el header, ya que visualmente, pienso que es más bonito.
- Para hacer la barra de navegación, se ha utilizado también `Flexbox` para poder meter espacios entre los items. También, da mucha más posibilidad a manejar la barra de navegación como deseas.
- Se ha quitado el margen para poder dejarlo a la izquierda sin espacios y que cuadre con el resto de la página.
- He realizado 2 cabeceras distintas, ya que una cabecera llamada ***header_index*** la utilizo solamente para ***index.html***, porque al tener justo abajo el texto encima del fondo, lo he tenido que hacer de esa forma. La otra cabecera llamada ***navbar*** es utilizada para el resto de páginas ya que todas tienen la misma estructura.

## Footer

- En el footer final, se ha realizado con `flexbox` ya que ha sido más cómodo para luego ordenarlo todo. También se habría podido hacer sin `flexbox` pero hubiera sido un poco más dificil.
- Dentro del footer, en el apartado de política de privacidad, se ha hecho con `flexbox` también. Cuando la página estaba en la versión del smartphone, se ponía `display: inline` ya que iba todo encima de otro elemento, por lo tanto, era mucho más sencillo.
- Para insertar las imágenes de las redes sociales, he usado un `div` ya que usar `picture` me resultaba más defectuoso, y me añadía espacios y saltos de líneas que no me funcionaba bien.

## Main

- Se ha puesto un borde superior con una pequeña sombra como en las fotos.
- Se ha puesto en `position: relative` porque es necesario si queremos poner le texto encima del fondo ya que de esa forma, nos permitiría mover el texto. Todo esto, en la página ***index.html***
- Se ha ajustado el ancho de la pantalla a un 80% para las pantallas de escritorio, llevando todos los contenidos más al centro.
- Cuando las pantallas son más pequeñas, se ha expandido hasta un 90% el ancho de las páginas web.

## Index.html
- El fondo es una imagen que hay en la carpeta de imagenes, dentro de materiales. Cuando se hace la pantalla más pequeña, se va ajustando para que quede lo mejor posible a los mockups.
- Para el texto encima del fondo en ***index.html***, se ha tenido que poner en `position: absolute` y dependiendo de cada tamaño de pantalla, se han ido ajustando los valores para subir el texto, tamaño letras, y ajustar a los lados.
- Para los párrafos de la página, se ha añadido un espaciado entre líneas, para que sea más cómoda la legibilidad.
- Para la sección de ***Al día***, se ha usado `flexbox` para poder organizar de una forma correcta los articulos, con sus respectivas imagenes, titulos, y párrafos. Se ha añadido también un espaciado entre ellos para que no se junten.
- Dentro de los articulos de la sección ***Al día***, se ha indicado que tendrá `position: relative`, ya que es necesario para poder ajustar al mismo nivel todos los enlaces de ***> Leer más***. Si no se hace de esa forma, cada uno, estaría a un nivel distinto, por lo que no quedaría simétrico.

## Aplicaciones.html

- Dentro de esta página web, he vuelto a usar `flexbox` para poder estructurar correctamente todos los article.
- En los article de esta página web, he usado como en ***index.html*** `position: relative` para poder luego ajustar el footer de cada article, y que todos sean simétricos y queden mejor para la vista, como en la página web.

## En-el-cine.html

- Como en todas las páginas web, hemos utilizado `flexbox` para ordenar los articles, y ajustar los videos para que queden de una forma similar a los mockups.
- Se ha usado `justify-content: space-between` para que se extiendan lo máximo en la pantalla, y ajustando el ancho de cada article, se ha conseguido que se queden 2 iframe por fila.

## Despacho-42.html

- En esta página web, se ha usado un 80% de ancho, y se ha usado también `flexbox` para dividir las 2 secciones (la principal del documentos, y artículos recientes).
- En la sección principal, se ha usado el 70% del ancho, siendo claramente mucho más ancho que la otra sección.
- Dentro del articulo ***¿ Qué es Despacho 42 ?*** , también he usado `flexbox`.
- En el formulario, he tenido que quitar los márgenes tanto al textarea, como a los input.
- En la sección de artículos recientes, tuve que utilizar nuevamente `flexbox`.
- Dentro del div, tuve que utilizar `flex: 1` para que así el div, ocupara todo el espacio posible, y se pudiera alinear todo a la derecha.
- En el div anterior, también se usó `flexbox` para poder ponerlo en columna y que se quedara la fecha justo debajo.