# Spotifiuby - Manual de usuario

- [¿Cómo utilizar el backoffice?](#como-utilizar)
- [Users](#users)
- [User profile](#user-profile)
- [Songs](#songs)
- [Metrics](#metrics)
- [Metricas de usuarios](#user-metrics)
- [Metricas de transacciones](#transaction-metrics)
- [Metricas de canciones](#song-metrics)

<a name="como-utilizar"/>

## ¿Cómo utilizar el backoffice?
Para poder loggearse y acceder al backoffice de administradores es necesario contar con una cuenta formada por email y contraseña. Notar que la cuenta tiene que tener permisos de administrador.

![login](/imagenes/login.png)

Una vez loggeado al backoffice se podrá navegar por tres secciones: 
- Users
- Songs
- Metrics

El backoffice cuenta con una barra de navegación en la parte supuerior para poder navegar libremente entre las secciones anteriores.

![navbar](/imagenes/navbar.PNG)

A continuación se detalla una explicación de las diferentes secciones.

<a name="users"/>

### Users
La seccion de usuarios lista a todos los usuarios del sistema y nos muestra la siguiente información acerca de ellos:
- ID de usuario
- Nombre de usuario
- Estado: indica si el usuario está bloqueado o no
- Acciones: permiten bloquear/desbloquear a un usuario o ir al perfil de los usuarios

Al bloquear a un usuario les negamos el acceso a la aplicación móvil.

<a name="users-profile"/>

### User profile
En la seccion del perfil de usuario se agrega como información adicional:
- Suscripcion: indica si el usuario está suscripto al contenido exclusivo o no.
- Géneros favoritos: los generos que el usuario marcó como sus favoritos.
- Artistas favoritos: los artistas que el usuario marcó como sus favoritos.

![user-profile](/imagenes/user-profile.png)

<a name="songs"/>

### Songs
En la seccion de canciones se listan todas las canciones del sistema. Mostramos la siguiente informacion de las canciones:
- ID de canción
- Nombre
- Autores
- Generos
- Duración (en segundos)

Además se agregan filtros para poder encontrar las canciones que uno desee, se puede filtrar por nombre, autor o genero. 
Los filtros de nombre y autor permiten escribir aquello que se necesite encontrar, mientras que el filtro de genero te permite elegir
entre alguno de los generos posibles de las canciones.

Notar que si alguna combinación de filtros no encuentra ninguna canción, entonces se notificará que no hay canciones que cumplan con los filtros pedidos. 

<a name="metrics"/>

### Metrics
En la seccion de métricas podemos encontrar algunas de las metricas mas relevantes y gráficos para analizarlos.
Se cuenta tanto con gráficos de torta como cón gráficos de barras. 

<a name="user-metrics"/>

### Métricas de usuarios
- Cantidad de logins
- Cantidad de logins con identidad federada
- Cantidad de usuarios registrados
- Cantidad de usuarios registrados con identidad federada
- Cantidad de usuarios bloqueados
- Recuperos de contraseña

![user-metrics](/imagenes/user-metrics.png)

<a name="transaction-metrics"/>

### Métricas de transacciones
- Cantidad de depósitos y de pagos
- Monto enviado por depósitos y por pagos

![transaction-metrics](/imagenes/transaction-metrics.png)

<a name="songs-metrics"/>

### Métricas de canciones
- Autores con más canciones
- Autores con más álbumes
- Géneros con más canciones
- Géneros con más albumes

![songs-metrics](/imagenes/songs-metrics.png)
