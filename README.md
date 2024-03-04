Proyecto de Autenticación y Autorización utilizando React
Este proyecto es una aplicación de gestión de usuarios que incluye funcionalidades de registro, inicio de sesión, página principal, perfil de usuario y tableros (boards) dependiendo del rol del usuario.

Gestión del Estado
La gestión del estado en este proyecto se realiza principalmente utilizando el contexto y los hooks de React. Se utiliza un contexto de autenticación para manejar el estado de inicio de sesión, y otro contexto para manejar la información del usuario y sus roles. Estos contextos se proporcionan a través de React.createContext y se consumen en los componentes relevantes utilizando el hook useContext.

Gestión de Rutas
Para la gestión de rutas, se utiliza React Router. Se implementan las siguientes rutas principales:

Ruta de Inicio de Sesión (/login): Esta ruta muestra el formulario de inicio de sesión.

Ruta de Registro (/register): Esta ruta muestra el formulario de registro para que los nuevos usuarios creen una cuenta.

Ruta de Página Principal (/home): Después de iniciar sesión correctamente, los usuarios son redirigidos a esta ruta, que representa la página principal o dashboard de la aplicación.

Ruta de Perfil (/profile): Esta ruta muestra la información del usuario y permite editarla.

Ruta de Tableros (/boards): Estas rutas muestran los tableros disponibles para el usuario, dependiendo de su rol.

Roles de Usuario
Se implementan diferentes roles de usuario para acceder a diferentes funcionalidades de la aplicación:

Usuario Registrado: Tiene acceso a la página de inicio, perfil y tableros.
Administrador: Además de las funcionalidades de usuario registrado, tiene acceso a la gestión de usuarios y tableros.
Visitante: Tiene acceso limitado, solo puede ver la página de inicio y registrar una nueva cuenta.
Instrucciones para Ejecutar el Proyecto
Clonar este repositorio en tu máquina local.
Navegar al directorio del proyecto en la terminal.
Ejecutar npm install para instalar las dependencias.
Ejecutar npm start para iniciar el servidor de desarrollo.
Abrir un navegador web y dirigirse a http://localhost:3000.
