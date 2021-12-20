# ScoreYourFood

Este proyecto fue realizado para el bootcamp de EGG Educación (https://eggeducacion.com/es-AR/) como proyecto final. El mismo consiste en un sitio web de calificación de comidas orientado exclusivamente al usuario. 
Allí mismo, el usuario registrandose, puede subir una foto del plato que ha comido, señalar en qué lugar, puntuarlo del 1 al 10 y dejar una breve reseña. Esta reseña se almanecerá en el historial del usuario y se visualizará para él y otros usuarios que deseen verla en forma de card. Por otra parte, el usuario puede editar y eliminar sus propias reseñas pero no asi las de otros, solo podrá visualizarlas. Las reseñas se mostrarán por filtros de comida y solo podrán ser vistas si uno se loguea en el sitio web.
## Construido con 🛠️

- [Maven](https://maven.apache.org/)
- [Spring Framework](https://spring.io/)
- [Thymeleaf](https://www.thymeleaf.org/)
- HTML5
- CSS3
- [ScrollReveal JS Library](https://scrollrevealjs.org/) 
- MySQL

El sitio cuenta con todas las funcionalidades seguridad que otorga la librería de Spring Security como el control de acceso de usuarios, registro e identificación de los mismos, recupero de contraseñas y encriptación de contraseñas para almacenarlas en la base de datos.

Se recomienda utilizar el IDE Apache NetBeans para ejecutarlo, y antes de hacerlo se debe crear una base de datos relacional MySQL y conectarla al proyecto. Al ejecutarse el programa creará todas las tablas necesarias para el correcto funcionamiento. 
El sitio web no es responsive y fue desarrollado en una resolucion de 1980x1020, con lo cual sugiero ejecutarlo en un medio de esa resolución. 
