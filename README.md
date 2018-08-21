# Obtener y visualizar datos del perfil de usuario

## Tarea 1

Como punto de partida vamos a utilizar este endpoint de la API de GitHub https://api.github.com/search/users?q=tony. Esta llamada recibe un parámetro de consulta `q` con un nombre y pasa la cadena de consulta al servidor. El servidor devuelve un listado de usuarios.

Crea un cuadro de texto para escribir un nombre en el cuadro de búsqueda y pulsar el botón para recuperar los datos utilizando la API dada. Al recuperar los datos, muestra la cuenta total (`total_count`) y los primeros 10 usuarios en el resultado de la búsqueda. 

## Tarea 2

Convierte cada perfil de usuario en un link de forma que al hacer click en ellos se navegue a una URL que contenda el nombre de usuario (*login*) como parte de la ruta. Pasa `user.login` como parámetro a la ruta. Crea un componente que leyendo el parámetro de la ruta obtenga los datos del usuario utilizando el endpoint de la API `https://api.github.com/users/<user.login>`, por ejemplo, https://api.github.com/users/tonybolanyo. Por último, muestra la imagen del perfil de usuario y alguna otra información relevante en el componente.

## Tarea 3

Utiliza cualquier framework de generación de gráficas que conozcas para crear un gráfico de barras simple que muestre el número de seguidores de los 10 primeros usuarios que devuelva la búsqueda.

## Opcional

Crea algunos tests unitarios

# Observaciones generales

1. Haz un fork de este repositorio.
2. Antes empezar a codificar crea una rama con tu nombre completo.
3. Cuando hayas terminado haz un *pull request* al proyecto original.

- Puedes usar cualquier framework o tema que conozcas para *estilizar* la aplicación.
- Se recomienda utilizar @angular/cli
- Debes utilizar Angular 4 o superior
