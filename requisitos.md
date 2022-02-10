
# Catálogo de requisitos

| **R1**     | **Requisitos como incidencias**         |
| --------------: | :------------------- |
| **Descripción** | Requisitos perfectamente definidos y convertidos en incidencias (issues) de GitHub.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R2**     | **Código fuente**         |
| --------------: | :------------------- |
| **Descripción** | Código fuente publicado en GitHub.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R3**     | **Estilo del código**         |
| --------------: | :------------------- |
| **Descripción** | Estilo del código según las normas internas de Laravel para el código y para las plantillas de las vistas.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R4**     | **Tres lanzamientos**         |
| --------------: | :------------------- |
| **Descripción** | Tres lanzamientos (releases) etiquetados en el repositorio como v1, v2 y v3.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R5**     | **README.md**         |
| --------------: | :------------------- |
| **Descripción** | README.md en el directorio raíz con la descripción principal del proyecto.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R6**     | **Documentación**         |
| --------------: | :------------------- |
| **Descripción** | Documentación publicada en GitHub Pages a partir del contenido del directorio /docs:  - Contenido:   - Guía general.   - API. - Formato: GitHub flavored Markdown (fuente) y HTML (resultado). - Usar make docs para crear la documentación. - Opcional: conversión a PDF.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R7**     | **Incidencias en GitHub**         |
| --------------: | :------------------- |
| **Descripción** | Administración y resolución de todas las incidencias notificadas en GitHub.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R8**     | **Etiquetas e hitos**         |
| --------------: | :------------------- |
| **Descripción** | Usar etiquetas e hitos:  - Etiquetas: mínimo, importante, opcional (además de las ya existentes). - Hitos: v1, v2, v3 (con fechas de entrega aproximadas).             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Información                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R9**     | **Rama master**         |
| --------------: | :------------------- |
| **Descripción** | La rama master debe reflejar en todo momento el estado más estable de la aplicación, de manera que:  - La rama master no debe contener bugs conocidos. - El desarrollo deberá hacerse en otras ramas creadas a tal efecto (una distinta por cada funcionalidad) y se irán combinado con la master una vez que se haya implementado la funcionalidad correspondiente. - La release actual en Heroku corresponderá siempre con el último commit de la rama master (usar los deploys automáticos de Heroku conectando la aplicación de Heroku con la rama master de GitHub).              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R10**     | **Gestión del proyecto**         |
| --------------: | :------------------- |
| **Descripción** | Usar GitHub Projects o similar para la gestión general del proyecto.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R11**     | **Final de cada iteración**         |
| --------------: | :------------------- |
| **Descripción** | Al final de cada iteración:  - Se realiza el lanzamiento que toque (v1, v2 o v3), etiquetando el commit correspondiente con el hito adecuado. - Se actualiza y publica la documentación. - Al final del Proyecto, se tiene que cumplir lo siguiente:   - Todas las incidencias cerradas con su debida justificación.   - En el backlog sólo pueden quedar tarjetas con prioridad opcional.   - El lanzamiento v3 desplegado en la nube.   - La documentación correctamente actualizada y publicada.              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R12**     | **Validación de formularios**         |
| --------------: | :------------------- |
| **Descripción** | Validación de  los campos de los formularios.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R13**     | **Gestión de ventanas**         |
| --------------: | :------------------- |
| **Descripción** | Gestión de ventanas. Gestión de la apariencia de las ventanas. Creación de nuevas ventanas y comunicación entre ventanas. (Opcional)             |
| **Prioridad**   | Opcional           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R14**     | **Manejo de eventos**         |
| --------------: | :------------------- |
| **Descripción** | Interactividad  a través de mecanismos de manejo de eventos intuitivos y eficaces.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R15**     | **DOM**         |
| --------------: | :------------------- |
| **Descripción** | Uso y manipulación de las características del modelo de objetos del documento (DOM).             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R16**     | **Almacenamiento en el lado del cliente**         |
| --------------: | :------------------- |
| **Descripción** | Uso de mecanismos de almacenamiento en el lado del cliente.              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R17**     | **jQuery, jQuery UI**         |
| --------------: | :------------------- |
| **Descripción** | Uso de la librería jQuery, jQuery UI.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R18**     | **Plugin no trabajado en clase**         |
| --------------: | :------------------- |
| **Descripción** | Incluir al menos un plugin no trabajado en clase.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R19**     | **Utilización de AJAX**         |
| --------------: | :------------------- |
| **Descripción** | Utilización de mecanismos de comunicación asíncrona: AJAX.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R20**     | **ECMAScript2015 (ES6)**         |
| --------------: | :------------------- |
| **Descripción** | Uso de las nuevas incorporaciones del estándar ECMAScript2015 (ES6).             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R21**     | **PHP**         |
| --------------: | :------------------- |
| **Descripción** | Usar PHP 7.3 ó superior.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R22**     | **Laravel**         |
| --------------: | :------------------- |
| **Descripción** | Usar Laravel versión 8.0 ó superior.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R23**     | **PostgreSQL**         |
| --------------: | :------------------- |
| **Descripción** | Usar PostgreSQL versión 12 ó superior.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R24**     | **Heroku**         |
| --------------: | :------------------- |
| **Descripción** | Despliegue de la aplicación en la plataforma Heroku.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R25**     | **Aplicación escalable**         |
| --------------: | :------------------- |
| **Descripción** | La aplicación ha de ser escalable.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R26**     | **Tecnología AJAX**         |
| --------------: | :------------------- |
| **Descripción** | La aplicación debe hacer en algún momento un uso apropiado de la tecnología AJAX.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R27**     | **Etiquetas semánticas de HTML5**         |
| --------------: | :------------------- |
| **Descripción** | Para estructurar el contenido se utilizarán las etiquetas semánticas de HTML5.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R28**     | **Presentación mediante CSS**         |
| --------------: | :------------------- |
| **Descripción** | Todo lo relacionado con la presentación se trabajará mediante CSS.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R29**     | **Diseño flexible**         |
| --------------: | :------------------- |
| **Descripción** | El diseño será flexible.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R30**     | **Transiciones, transformaciones, animaciones y contenido multimedia**         |
| --------------: | :------------------- |
| **Descripción** | Existirán transiciones, transformaciones, animaciones y contenido multimedia.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R31**     | **Validación HTML5, CSS3 y accesibilidad**         |
| --------------: | :------------------- |
| **Descripción** | Se deberá comprobar que el código realizado supera:  - El validador para HTML5, CSS3. - Nivel de accesibilidad AA. - Prueba de Hassan Montero y Martín Fernández .              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R32**     | **Diseño para varias resoluciones**         |
| --------------: | :------------------- |
| **Descripción** | Implementar el diseño para resoluciones grandes y pequeñas.             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R33**     | **Varios navegadores**         |
| --------------: | :------------------- |
| **Descripción** | Comprobar que el diseño es correcto en los siguientes navegadores:  - Chrome. - Mozilla Firefox. - Opera.              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R34**     | **Despliegue en un Host**         |
| --------------: | :------------------- |
| **Descripción** | Realizar el despliegue en un Host:  - Utilizando algún servicio gratuito de hosting como los vistos en clase  - Instalar / configurar o solicitar el software necesario para desplegar el proyecto.              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R35**     | **Despliegue en un servidor local**         |
| --------------: | :------------------- |
| **Descripción** | Realizar un despliegue en un servidor local usando y configurando tres máquinas virtuales para:  - Crear un servicio de Nombres de dominio. - Gestionar y administrar el servidor Apache tanto en Windows como Linux:   - Instalar el servidor y configurarlo.   - Configurar directivas.   - Usar directorios virtuales y redireccionamientos.   - Usar diferentes módulos estáticos y dinámicos.   - Usar autenticaciones.   - Usar ficheros de configuración personalizada de directorios.   - Usar HTTPS y certificados Digitales.              |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Técnico                |
| **Complejidad** | Difícil         |
| **Entrega**     | v3             |


| **R36**     | **Diseño de la base de datos**         |
| --------------: | :------------------- |
| **Descripción** | Realizar un enunciado sobre la base de datos que se desea implementar así como un diagrama de flujo              |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R37**     | **Crear modelos**         |
| --------------: | :------------------- |
| **Descripción** | Desde el framework de Laravel, añadir los modelos creados previamente             |
| **Prioridad**   | Importante           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R38**     | **Documentar el diseño de la interfaz**         |
| --------------: | :------------------- |
| **Descripción** | Se debe realizar el wireframe, prototipo, mapa de navegación y guía de estilos (colores, tipografía e iconos usados).             |
| **Prioridad**   | Mínimo           |
| **Tipo**        | Información                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R39**     | **Buscador de cine**         |
| --------------: | :------------------- |
| **Descripción** | Crear un buscador en la página inicial para identificar el cine al que se quiere acceder en la cartelera según la provincia, localidad y nombre del cine             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R40**     | **Mostrar películas**         |
| --------------: | :------------------- |
| **Descripción** | Al seleccionar el cine, se debe mostrar las películas disponible con el horario de estas. Al pinchar en el título de la película se abrirá otra página que dará información sobre la película y la opción de comprar entradas.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R41**     | **Mostrar horario**         |
| --------------: | :------------------- |
| **Descripción** | En la página de la información de la película, se mostrarán las diferentes horas donde se puede ver la película de forma que al pinchar en una de las horas, se abrirá la página que dará la opción de reservar entradas para esa hora. Además se debe poder elegir los asientos disponibles.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R42**     | **Reservar**         |
| --------------: | :------------------- |
| **Descripción** | El usuario reserva los asientos seleccionados, estos asientos no deben poderse reservar por nadie más.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R43**     | **Registrar e iniciar sesión**         |
| --------------: | :------------------- |
| **Descripción** | El usuario debe poder iniciar sesión, por defecto, cuando un usuario se registre tendrá el rol de “cliente”, pero también existe el rol “administrador”.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R44**     | **Funcionalidad del administrador**         |
| --------------: | :------------------- |
| **Descripción** | El usuario administrador debe poder eliminar, editar y añadir películas y horarios de esas películas para cualquier cine             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R45**     | **Contacto**         |
| --------------: | :------------------- |
| **Descripción** | El usuario dispondrá de un apartado llamado “contacto” donde encontrará un formulario para enviar un email a la empresa             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R46**     | **Información de las películas**         |
| --------------: | :------------------- |
| **Descripción** | Cuando el usuario selecciona una película, verá una imagen de la película junto a una sinopsis y los diferentes horarios.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Información                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R47**     | **Controladores**         |
| --------------: | :------------------- |
| **Descripción** | Crear correctamente los diferentes controladores              |
| **Prioridad**   | Importante           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R48**     | **Subir imagen al servidor**         |
| --------------: | :------------------- |
| **Descripción** | El administrador podrá subir la imagen para especificar la portada de una película que quiera incluir             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R49**     | **Captcha**         |
| --------------: | :------------------- |
| **Descripción** | El formulario de registro se complementará con un captcha para asegurar que el usuario no sea un bot             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R50**     | **Películas de estreno**         |
| --------------: | :------------------- |
| **Descripción** | Cuando el administrador añada una nueva película, se enviará al usuario un email informando de que hay una nueva película disponible.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R51**     | **Relaciones**         |
| --------------: | :------------------- |
| **Descripción** | Crear las relaciones en los diferentes modelos de Laravel             |
| **Prioridad**   | Importante           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v1             |


| **R52**     | **Comprobar asientos**         |
| --------------: | :------------------- |
| **Descripción** | Al reservar, se hará una comprobación no solo desde cliente (cuando se muestren los asientos disponibles) sino también desde servidor para asegurar que ese asiento en concreto no esté reservado.             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R53**     | **Logo**         |
| --------------: | :------------------- |
| **Descripción** | Crear e implementar un logo para el sitio web             |
| **Prioridad**   | Importante           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v3             |


| **R54**     | **Consultas**         |
| --------------: | :------------------- |
| **Descripción** | Elaborar las consultas para mostrar las películas según el cine seleccionado             |
| **Prioridad**   | Importante           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v1             |


| **R55**     | **Seeders**         |
| --------------: | :------------------- |
| **Descripción** | Crear los seeders para la base de datos             |
| **Prioridad**   | Importante           |
| **Tipo**        | Técnico                |
| **Complejidad** | Media         |
| **Entrega**     | v2             |


| **R56**     | **Rutas**         |
| --------------: | :------------------- |
| **Descripción** | Crear las rutas para los diferentes enlaces de la página             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R57**     | **Favorito**         |
| --------------: | :------------------- |
| **Descripción** | El usuario podrá elegir un cine como favorito para que cuando ingrese en la página inicial aparezca su cine favorito.              |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R58**     | **Carrusel**         |
| --------------: | :------------------- |
| **Descripción** | Implementar un carrusel de imágenes en la página principal             |
| **Prioridad**   | Importante           |
| **Tipo**        | Técnico                |
| **Complejidad** | Fácil         |
| **Entrega**     | v2             |


| **R59**     | **Mostrar asientos**         |
| --------------: | :------------------- |
| **Descripción** | Mostrar los asientos tal como estarían en la sala del cine              |
| **Prioridad**   | Opcional           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |


| **R60**     | **descarga PDF**         |
| --------------: | :------------------- |
| **Descripción** | El usuario tendrá la opción de descargar un pdf con su entrada una vez la haya comprado             |
| **Prioridad**   | Importante           |
| **Tipo**        | Funcional                |
| **Complejidad** | Media         |
| **Entrega**     | v3             |



## Cuadro resumen

| **Requisito** | **Prioridad** | **Tipo** | **Complejidad** | **Entrega** |
| :------------ | :-----------: | :------: | :-------------: | :---------: |
| (**R1**) Requisitos como incidencias | Mínimo | Información | Fácil | v1 | 
| (**R2**) Código fuente | Mínimo | Información | Fácil | v1 | 
| (**R3**) Estilo del código | Mínimo | Técnico | Fácil | v3 | 
| (**R4**) Tres lanzamientos | Mínimo | Técnico | Fácil | v3 | 
| (**R5**) README.md | Mínimo | Información | Fácil | v1 | 
| (**R6**) Documentación | Mínimo | Información | Fácil | v3 | 
| (**R7**) Incidencias en GitHub | Mínimo | Información | Fácil | v3 | 
| (**R8**) Etiquetas e hitos | Mínimo | Información | Fácil | v1 | 
| (**R9**) Rama master | Mínimo | Técnico | Media | v1 | 
| (**R10**) Gestión del proyecto | Mínimo | Técnico | Fácil | v1 | 
| (**R11**) Final de cada iteración | Mínimo | Técnico | Media | v1 | 
| (**R12**) Validación de formularios | Mínimo | Técnico | Fácil | v3 | 
| (**R13**) Gestión de ventanas | Opcional | Técnico | Media | v3 | 
| (**R14**) Manejo de eventos | Mínimo | Técnico | Fácil | v3 | 
| (**R15**) DOM | Mínimo | Técnico | Fácil | v2 | 
| (**R16**) Almacenamiento en el lado del cliente | Mínimo | Técnico | Fácil | v3 | 
| (**R17**) jQuery, jQuery UI | Mínimo | Técnico | Fácil | v3 | 
| (**R18**) Plugin no trabajado en clase | Mínimo | Técnico | Media | v3 | 
| (**R19**) Utilización de AJAX | Mínimo | Técnico | Fácil | v3 | 
| (**R20**) ECMAScript2015 (ES6) | Mínimo | Técnico | Fácil | v3 | 
| (**R21**) PHP | Mínimo | Técnico | Fácil | v1 | 
| (**R22**) Laravel | Mínimo | Técnico | Fácil | v1 | 
| (**R23**) PostgreSQL | Mínimo | Técnico | Fácil | v1 | 
| (**R24**) Heroku | Mínimo | Técnico | Fácil | v3 | 
| (**R25**) Aplicación escalable | Mínimo | Técnico | Fácil | v1 | 
| (**R26**) Tecnología AJAX | Mínimo | Técnico | Fácil | v1 | 
| (**R27**) Etiquetas semánticas de HTML5 | Mínimo | Técnico | Fácil | v1 | 
| (**R28**) Presentación mediante CSS | Mínimo | Técnico | Fácil | v1 | 
| (**R29**) Diseño flexible | Mínimo | Técnico | Fácil | v3 | 
| (**R30**) Transiciones, transformaciones, animaciones y contenido multimedia | Mínimo | Funcional | Media | v3 | 
| (**R31**) Validación HTML5, CSS3 y accesibilidad | Mínimo | Técnico | Difícil | v3 | 
| (**R32**) Diseño para varias resoluciones | Mínimo | Técnico | Media | v3 | 
| (**R33**) Varios navegadores | Mínimo | Técnico | Media | v3 | 
| (**R34**) Despliegue en un Host | Mínimo | Técnico | Difícil | v3 | 
| (**R35**) Despliegue en un servidor local | Mínimo | Técnico | Difícil | v3 | 
| (**R36**) Diseño de la base de datos | Importante | Información | Media | v1 | 
| (**R37**) Crear modelos | Importante | Técnico | Fácil | v1 | 
| (**R38**) Documentar el diseño de la interfaz | Mínimo | Información | Media | v1 | 
| (**R39**) Buscador de cine | Importante | Funcional | Fácil | v1 | 
| (**R40**) Mostrar películas | Importante | Funcional | Media | v1 | 
| (**R41**) Mostrar horario | Importante | Funcional | Media | v2 | 
| (**R42**) Reservar | Importante | Funcional | Media | v3 | 
| (**R43**) Registrar e iniciar sesión | Importante | Funcional | Fácil | v1 | 
| (**R44**) Funcionalidad del administrador | Importante | Funcional | Media | v2 | 
| (**R45**) Contacto | Importante | Funcional | Fácil | v2 | 
| (**R46**) Información de las películas | Importante | Información | Media | v1 | 
| (**R47**) Controladores | Importante | Técnico | Fácil | v1 | 
| (**R48**) Subir imagen al servidor | Importante | Funcional | Media | v3 | 
| (**R49**) Captcha | Importante | Funcional | Media | v2 | 
| (**R50**) Películas de estreno | Importante | Funcional | Media | v3 | 
| (**R51**) Relaciones | Importante | Técnico | Fácil | v1 | 
| (**R52**) Comprobar asientos | Importante | Funcional | Fácil | v2 | 
| (**R53**) Logo | Importante | Técnico | Fácil | v3 | 
| (**R54**) Consultas | Importante | Técnico | Media | v1 | 
| (**R55**) Seeders | Importante | Técnico | Media | v2 | 
| (**R56**) Rutas | Importante | Funcional | Fácil | v2 | 
| (**R57**) Favorito | Importante | Funcional | Media | v3 | 
| (**R58**) Carrusel | Importante | Técnico | Fácil | v2 | 
| (**R59**) Mostrar asientos | Opcional | Funcional | Media | v3 | 
| (**R60**) descarga PDF | Importante | Funcional | Media | v3 | 
