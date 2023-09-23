![Cabecera](img/img-readme/cabecera-proyecto.png)

---

#  Katana Sushi - Restaurante Japonés
🏯 [Katana Sushi - Restaurante Japonés](https://ladronbx.github.io/katanasushi/) 🏯

**Primer proyecto del Bootcamp Full Stack Developer Presencial en la academia GeeksHubs en Valencia**


Durante este proyecto, he aplicado los conocimientos adquiridos en la primera semana del Bootcamp, para crear una página web que representa a un restaurante japonés llamado **Katana Sushi**.



![Logo GeeksHubs](img/img-readme/geekhubs.png)

---




## Índice

- 🛠️ [Tecnologías utilizadas](#tecnologías-utilizadas) 
- 📊 [Bootstrap](#bootstrap)
- 📱 [Media Query](#media-query)
- 🧩 [Código Fuente](#código-fuente)
- 🏠 [Home - Página Principal](#home---página-principal)
- 🍣🍷 [Carta Sushi y Carta Vino](#carta-sushi-y-carta-vino)
- 📅 [Página de Reserva](#página-de-reserva)
- 😎 [Sobre Nosotros](#sobre-nosotros)
- 📋 [Instrucciones de Uso](#instrucciones-de-uso)
- 🤝 [Contribuciones](#contribuciones)
- 📧 [Contacto](#contacto)
- 🌐 [Enlace Github Pages](#enlace-github-pages)




## Tecnologías utilizadas:

- [HTML5](https://lenguajehtml.com/html/)
- [CSS3](https://desarrolloweb.com/manuales/css3.html)
- [Bootstrap](https://getbootstrap.com/)

## Bootstrap

**El proyecto de Katana Sushi se ha desarrollado utilizando el framework de diseño web Bootstrap.**
 Bootstrap es una herramienta de código abierto que ha facilitado la creación de una página web receptiva y estilizada. A continuación, se destacan algunas de las formas en que Bootstrap ha sido utilizado en el proyecto:

- **Dependencias de Bootstrap**: El proyecto utiliza las dependencias de Bootstrap, incluyendo la hoja de estilos CSS y las bibliotecas de JavaScript, que se vinculan directamente desde la CDN de Bootstrap para asegurar un rendimiento óptimo y una experiencia de usuario fluida.
    
    ![Imagen Dependencias](img/img-readme/dependencias.png)
    
- **Navbar personalizada**: Se ha creado una barra de navegación personalizada que incluye enlaces a diferentes secciones del sitio web. Esta barra de navegación se adapta automáticamente a diferentes tamaños de pantalla gracias a las clases proporcionadas por Bootstrap.
    
    *Vista menú pantalla PC*
    ![Imagen MenuNav](img/img-readme/navbar.png)

    *Vista menú en forma de burger para pantalla tablet o inferior*
    ![Imagen MenuNav](img/img-readme/menu-burger.png)
    
- **Tarjetas de producto**: Las tarjetas que se utilizan para presentar los diferentes platos de sushi son componentes de Bootstrap que permiten mostrar de manera atractiva la información del producto, incluyendo una imagen, título, descripción y precio.
    
    ![Imagen Carta Sushi](img/img-readme/carta-sushi1.png)

    
- **Diseño responsivo**: Bootstrap ha sido fundamental para garantizar que el sitio web sea completamente responsivo. Esto significa que la página se ajusta de manera óptima a diferentes dispositivos, tanto a pc, como tablets o smartphones.
- **Estilos personalizados**: Aunque Bootstrap proporciona una serie de estilos predeterminados, también se han aplicado estilos personalizados para adaptar la apariencia general del sitio web al tema y la identidad de Katana Sushi.


### **Media Query**

El proyecto incluye media queries para garantizar que la página web se vea y funcione correctamente en pantallas de diferentes tamaños. A continuación, se describen las modificaciones realizadas para pantallas de 1100px o menos:

- El tamaño de fuente se ajusta para una mejor legibilidad en pantallas más pequeñas.
- La imagen se redimensiona automáticamente para ocupar todo el ancho de la pantalla.
- El texto se centra y se ajusta para mantener un diseño atractivo en dispositivos móviles.

    ![Imagen responsive 1](img/img-readme/pc.png)
    ![Imagen responsive 2](img/img-readme/ipad.png)
    

## Código Fuente

El código fuente del proyecto se encuentra organizado en varias páginas HTML y archivos CSS. A continuación, se enumeran las páginas principales y los archivos asociados:

- `index.html`: Página principal del sitio web que incluye la información general del restaurante.
- `sushi.html`: Página que muestra la carta de sushi disponible.
- `vinos.html`: Página que presenta la carta de vinos.
- `reserva.html`: Página donde los usuarios pueden realizar reservas.
- `about.html`: Página que proporciona información sobre el restaurante y su equipo.
---
#¿Cómo se compone la web?
## Home - Página Principal

![Imagen menú](img/img-readme/menu-home.png)

- La página principal muestra **información general** del restaurante japonés **Katana Sushi.**
    
    ![Imagen Home 1](img/img-readme/home1.png)
    
- Un video en blanco y negro de una mujer japonesa se reproduce automáticamente en la página principal.
    
    ![Gif Video Home](img/img-readme/video-home.gif)
    

- Se presentan secciones informativas sobre la filosofía del restaurante, el ambiente acogedor y la variedad de platos que se ofrecen.

    ![Imagen Home 2](img/img-readme/home2.png)

## Carta Sushi y Carta Vino

El proyecto Katana Sushi ha sido desarrollado utilizando el framework de diseño web Bootstrap, y uno de los componentes destacados que he utilizado son las tarjetas (cards) proporcionadas por Bootstrap. Las tarjetas son elementos versátiles que me han permitido mostrar los platos de sushi de manera atractiva y organizada. A continuación proporciono más detalles sobre cómo se he integrado:

- **Tarjetas de Producto**: Cada plato de sushi se presenta en su propia tarjeta. Las tarjetas incluyen una imagen representativa del plato, un título descriptivo, información detallada sobre el plato y su precio. Esta presentación ayuda a los usuarios a obtener rápidamente la información que necesitan sobre nuestros platos.
    
    ![Imagen Carta Sushi](img/img-readme/carta-vino1.png)
    
- **Diseño Responsivo**: Las tarjetas se adaptan automáticamente a diferentes tamaños de pantalla. Esto significa que se verán igual de bien tanto en pc, como en una tablet como en un smartphone. La estructura flexible de las tarjetas de Bootstrap garantiza una experiencia de usuario coherente en todos los dispositivos.
    
    ![Gif nexus 5](img/img-readme/responsive.gif)
    
- **Estilos Personalizados**: Aunque he utilizado las tarjetas de Bootstrap como punto de partida, he aplicado estilos personalizados para alinearlas con la identidad y el tema de **Katana Sushi**. Esto ha permitido que se logre un diseño único y atractivo para cada tarjeta de producto.
- **Facilidad de Mantenimiento**: Las tarjetas de Bootstrap son fáciles de personalizar y mantener. Esto permitiría agregar nuevos platos de sushi o actualizar información existente de manera eficiente a medida que el menú cambia o evoluciona.

### **Página de Reserva**

La página de reserva de Katana Sushi permite a los clientes realizar reservas para disfrutar de una experiencia culinaria única. 

**Mapa de Ubicación**
Se encuentra incluido un mapa que te permite ver la ubicación exacta del restaurante. Puedes encontrar el mapa a continuación:

<iframe id="map"
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3079.944035110422!2d-0.3601145241204721!3d39.47059301268056!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd6048bddd00115b%3A0xb2c3d48844a1cd9f!2sC.%20Chile%2C%203%2C%2046021%20Valencia!5e0!3m2!1ses!2ses!4v1694977541134!5m2!1ses!2ses"
    style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

<div id="mapa"><a
        href="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3079.944035110422!2d-0.3601145241204721!3d39.47059301268056!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd6048bddd00115b%3A0xb2c3d48844a1cd9f!2sC.%20Chile%2C%203%2C%2046021%20Valencia!5e0!3m2!1ses!2ses!4v1694977541134!5m2!1ses!2ses"
        target="_blank">
        Ver en Google Maps
    </a></div>


**Formulario** 
También encontrarás un formulario sencillo que te permite seleccionar la fecha y la hora de tu reserva.
![Imagen Reserva 1](img/img-readme/reserva1.png)
![Imagen Reserva 2](img/img-readme/reserva2.png)
![Imagen Reserva 3](img/img-readme/form.png)

![Imagen Reserva 4](img/img-readme/form-responsive.png)

Puedes acceder a esta página de reserva haciendo clic en el enlace "Reserva" en la barra de navegación del sitio web.

**Instrucciones para Reservar:**

1. Ingresa tu nombre y apellidos en los campos correspondientes.
2. Proporciona tu dirección de correo electrónico para que podamos confirmar tu reserva.
3. Selecciona la fecha deseada para tu reserva utilizando el campo de fecha.
4. Elije la hora de tu reserva utilizando el campo de hora.
5. Haz clic en el botón "Reserva" para completar el proceso.




## Sobre Nosotros 

![Imagen about](img/img-readme/about.png)

- La página 'Sobre Nosotros' muestra **información general** del restaurante japonés **Katana Sushi.**
    
    ![Imagen About 2](img/img-readme/about2.png)
    
- Un video en blanco y negro de un cocinero preparando Sushi se reproduce automáticamente en la página principal.
    
    ![Gif Video About](img/img-readme/video-about.gif)

- Se puede observar un carrusel creado con Bootstrap y estilos adaptados con css.

    ![Imagen About 4](img/img-readme/carrusel.png)


- Se presentan secciones informativas sobre la filosofía del restaurante.

    ![Imagen About 3](img/img-readme/about3.png)

---

## Instrucciones de Uso

Para ver el proyecto en acción, puedes acceder a la página web en línea visitando el siguiente enlace: [Katana Sushi - Restaurante Japonés](https://ladronbx.github.io/katanasushi/)

Si deseas ejecutar el proyecto localmente, sigue estos pasos:

1. Descarga todas las carpetas y archivos del repositorio.
2. Abre el archivo `index.html` en tu navegador web.

---

## Mejoras que me hubiese gustado integrar
Lo primero es que habría que rectificar y reorganizar las páginas sushi.html, vinos.html, reserva.html y guardarlas en un directorio nuevo llamado pages. 
También me hubiese gustado insertar un mapa con Bootstrap. Además no he conseguido que en vista móvil se cree un espacio entre cards por lo que en un futuro cuando aprenda lo integraré.

---

## Contribuciones

Este proyecto es público y las contribuciones son bienvenidas. Si deseas contribuir, sigue estos pasos:

1. Realiza un fork del repositorio.
2. Crea una nueva rama para tu contribución.
3. Realiza tus cambios y mejoras.
4. Envía una solicitud de extracción (pull request) para revisar y fusionar tus cambios.

---

## Contacto

Si tienes preguntas, comentarios o sugerencias, no dudes en ponerte en contacto conmigo a través de [ladronbravovlc@gmail.com](mailto:ladronbravovlc@gmail.com).

---

## Enlace Github Pages

- [Página Web del Restaurante](https://ladronbx.github.io/katanasushi/)
---
