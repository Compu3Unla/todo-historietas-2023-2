# Todo Historietas

Todo historietas es una página donde  podrás encontrar información y recursos relacionados con las historietas clásicas más populares. A continuación, se detalla lo que ha funcionado en la página y lo que aún está en desarrollo.

## Funcionalidades implementadas

- **Diseño Responsivo:** Se ha implementado un diseño responsivo utilizando técnicas de CSS y Media Queries para que la página se adapte correctamente a diferentes tamaños de pantalla como 1920px para desktop y 600px para mobile. Cabe destacar que toda la página junto con sus diferentes HTML están incluidos en este formato responsivo 

- **Navegación:** Se ha creado una barra de navegación en el encabezado que permite acceder fácilmente a diferentes secciones de la página, como las categorías de historietas, información sobre nosotros, novedades y formulario de contacto que solo funciona de esta manera en el Index. Por otro lado, en los distintos HTML, su header funciona de otra manera, esta misma solo tiene el logo de la página; y si se clickea vuelve a dirigirse al Index.

- **Categorías de Historietas:** Se ha creado una sección dedicada a las diferentes categorías de historietas clásicas, donde se muestra una carrusel con imágenes de cada personaje elegido para este trabajo; y al clickearlas se redirige a otro HTML con la información correspondiente de cada uno.

- **Galería de autores:** En esta sección se ve una introducción a la galería de cada autor que crearon a los personajes que se muestran en el carrusel anterior. Esta misma, fue creada a partir de fancybox y al clickearlas se pueden visualizar más grandes y se crea un scroll a partir de flechas direccionales. 

- **Información sobre nosotros:** Se ha agregado una sección donde se brinda información sobre el equipo detrás de la página web y su pasión por las historietas clásicas.

- **Formulario de contacto:** Se ha incorporado un formulario de contacto simple mediante el cual los visitantes pueden enviar consultas o comentarios directamente al equipo de la página.

- **Novedades:** Se ha creado una sección de novedades donde se muestran los últimos lanzamientos y noticias relacionadas con las historietas clásicas, y también las imágenes están vinculadas a los HTML con información de cada personaje.

## Cambios para el recuperatorio

- A partir de lo corregido en el trabajo anterior. 
- Se decidió eliminar el fondo cuadrille por uno liso, de manera que se destacaran las diferentes secciones de la página, en lugar de competir con un fondo complejo. 
- Se mejoró la versión mobile de 600px, ajustándose todos sus elementos para que no haya un scroll horizontal, y para lograr una versión de la página cómoda de visualizar desde un celular.
- En la sección del formulario, se aplicó la ley de proximidad entre el formulario y su imagen, que lo acompaña, generando que ambos elementos se puedan percibir de una misma sección, en lugar de percibirse "volando" por la página. Por otro lado, también se agregó un background al formulario, para que se separe del fondo del body y no quede volando cada input.
- También, en media, se achico la tipografía de este mismo, adaptándose, así, a una pantalla más chica.
- Se crearon distintas animaciones para que se distingan las imágenes y que el texto de galería resalte. Consideramos que estas animaciones le aportan vida y dinamismo a la página. 
- En esta instancia, ya se puede visualizar la tipografía elegida, ya que agregamos la etiqueta import en el inicio del CSS, cuestión que se nos había pasado en la instancia anterior del trabajo práctico, pero que sabemos que es necesaria para visualizar correctamente la tipografía en una página web. 
- Se decidió que el header en el index quede tal cual lo planeado originalmente, pero que en el resto de los HTML sea diferente. Decidimos que en estos solo quede el logo, y que este funcione como botón de inicio, cuestión que consideramos intuitiva para el usuario por la animación agregada. En media el logo está centrado, por una decisión de diseño. 
- Respecto a la sección de novedades, se eliminaron las position, ya que consideramos que no hicimos una buena utilización de estas en la anterior instancia. En su lugar, utilizamos Flexbox para la composición de la sección, y creemos haber logrado un mejor resultado en esta instancia. Por otro lado, se agregó una invitación para ver el video, a modo de justificar su aparición en la sección, y se destacó con un background de otro color. 
