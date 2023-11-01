# Hito 1: Concretando y definiendo el proyecto

Durante esta semana he ido madurando la idea comentada en el hito anterior ([enlace](../Hito0/descripcionDelProyecto.md)). 

Para ayudarme a imaginar el sistema he creado un par de imágenes:

La primera imagen mostraría el uso que cada usuario de esta aplicación debería poder hacer.

![uso](./images/sistema.drawio.png)

Y la segunda imagen muestra un supuesto esquema de base de datos sobre la que nuestra aplicación funcionaría.

![bbdd](./images/bbdd.drawio.png)

Gracias a las relaciones entre clases que hemos visto en las imágenes anteriores, ahora podemos crear historias de usuario más fácilmente.


## Historias de usuario

- **[HU1] Usuario no registrado**: No se quien es el artista de la canción que estaba sonando hace un momento, voy a buscar una estrofa de la canción en la aplicación a ver si tengo suerte.
- **[HU2] Usuario no registrado**: Me interesaría hacer un ranking sobre canciones que hablen sobre "tal" tema.
- **[HU3] Usuario registrado**: La letra de esta canción esta mal, la voy a corregir en un momento.
- **[HU4] Usuario registrado**: Mi artista favorito acaba de sacar una nueva canción y no esta la letra en la aplicación, voy a crearla.
- **[HU5] Usuario registrado**: Voy a darle a "me gusta" a esta canción para que me salga en esa lista, así no tendré que buscarla otra vez.
- **[HU6] ADMIN**: Quiero que la gente use mi aplicación, y para ello necesito tener una base de datos de canciones disponible. Necesito poder cargar grandes cantidades de datos en un momento y no ir de uno en uno. Así actualizo de golpe mi base de datos y gano mucho tiempo.
- **[HU7] ADMIN**: Tengo que controlar que los datos (en este caso las letras de las canciones) sean correctos. Los usuarios que se registren pueden cambiar la letra de una canción y es conveniente revisar si esos cambios "eran necesarios".
  