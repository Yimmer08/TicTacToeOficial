## ¡Bienvenido al proyecto de 3 en raya en Eclipse con Dynamic Web Project!

Este proyecto tiene como objetivo crear una aplicación web que permita a los usuarios jugar el clásico juego de 3 en raya. Para ello, se utilizará Java como lenguaje de programación y se implementará un servidor Tomcat para ejecutar la aplicación en un navegador web.

La estructura de archivos del proyecto se muestra a continuación:
.
├── src
│   ├── main
│   │   ├── java
│   │   └── webapp
│   │       ├── css
│   │       ├── js
│   │       ├── WEB-INF
│   │       └── index.jsp
│   └── test
├── target
├── pom.xml
└── README.md

La carpeta src contiene el código fuente del proyecto. La carpeta main contiene dos subcarpetas: java, donde se encuentran las clases Java que implementan la lógica del juego, y webapp, donde se encuentra el código HTML, CSS y JavaScript que implementa la interfaz de usuario. La carpeta test se utiliza para almacenar pruebas unitarias.

La carpeta target contiene los archivos compilados del proyecto. El archivo pom.xml es el archivo de configuración de Maven, utilizado para construir y administrar el proyecto.

Para ejecutar el proyecto, abra Eclipse y seleccione File > Import > Maven > Existing Maven Projects. Seleccione la carpeta del proyecto y haga clic en Finish. Luego, haga clic derecho en el proyecto y seleccione Run As > Run on Server. Elija Tomcat como servidor y haga clic en Finish.

La aplicación se abrirá en su navegador predeterminado y podrá jugar al juego de 3 en raya. ¡Diviértete!

[![Tic Tac Toe](https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Tic_tac_toe.svg/522px-Tic_tac_toe.svg.png "Tic Tac Toe")](http://https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Tic_tac_toe.svg/522px-Tic_tac_toe.svg.png "Tic Tac Toe")
