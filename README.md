# Beauty-Net
# Beauty - Red Social de Maquillaje

¡Bienvenido a Beauty Net! Una comunidad en línea donde los amantes del maquillaje pueden compartir sus experiencias, artículos de compra, ventas y reseñas. ¡Únete a la comunidad y conecta con otros apasionados del maquillaje!

## Características

- Iniciar sesión con Google para acceder a la red social.
- Publicar artículos sobre compra, venta y reseñas.
- Agregar imágenes a las publicaciones.
- Editar y eliminar tus propias publicaciones.
- Dar "Me gusta", "Me encanta" y "Me interesa" a las publicaciones.
- Comentar en las publicaciones de otros usuarios.
- Filtrar publicaciones por categoría: compra, venta y reseña.

## Tecnologías Utilizadas

- JavaScript
- Firebase (Authentication, Firestore, Storage)
- Bootstrap

## Funciones Principales

### Autenticación

- `AutenticarGoogle()`: Inicia sesión utilizando la autenticación de Google. Se abrirá una ventana emergente para permitir que el usuario inicie sesión con su cuenta de Google.

### Perfil de Usuario

- `Logout`: Permite cerrar sesión del usuario actual.
- Se muestra el nombre y la imagen de perfil del usuario autenticado.

### Publicaciones

- `publicar()`: Permite agregar una nueva publicación al muro.
- `setupPost(data)`: Muestra las publicaciones en el muro y permite interactuar con ellas.
- Interacción con las publicaciones: dar "Me gusta", "Me encanta" y "Me interesa", comentar, editar y eliminar publicaciones.

### Filtrar Publicaciones

- Los botones de navegación en la parte superior permiten filtrar las publicaciones según su categoría: compra, venta y reseña.

### Búsqueda

- `btn-buscar` y `search-input`: Permite realizar búsquedas de publicaciones por título y contenido.

## Contribuir

¡Siéntete libre de contribuir a Beauty Net! Puedes hacerlo abriendo un Pull Request con tus mejoras o correcciones.


