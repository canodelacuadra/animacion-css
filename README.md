# Actividad: Crear animación con CSS o Javascript
Incorporar una animación a tu sitio web puede agregar un toque interactivo y atractivo para los visitantes. Aquí hay un enfoque paso a paso para lograrlo:

## Planificación:
 Decide qué tipo de animación deseas agregar y dónde encajará mejor en tu sitio web. Puede ser un banner animado en la página de inicio, una transición de página, un elemento que se mueve al hacer scroll, entre otros.
### Tecnología

Elige una biblioteca o herramienta: Hay varias bibliotecas y herramientas disponibles para crear animaciones en la web de manera más fácil y efectiva. Algunas de las más populares incluyen:

* CSS Animations: Puedes utilizar animaciones CSS para aplicar transiciones y transformaciones a elementos HTML. Esto se puede hacer directamente en tu archivo de hoja de estilo CSS.

* CSS Frameworks: Frameworks como Bootstrap incluyen clases predefinidas para animaciones, lo que facilita la implementación de efectos animados.

* JavaScript Libraries: Bibliotecas como jQuery y GreenSock Animation Platform (GSAP) ofrecen poderosas capacidades de animación utilizando JavaScript.
* [Javascript Vanilla](https://www.ardepizando.com/que-es-vanilla-js/)

## Crea la animación:

*  CSS3: Si deseas usar CSS3 para animar elementos, puedes definir las animaciones en tu archivo CSS. Aquí hay un ejemplo de cómo animar una imagen giratoria:

````css

.animacion {
    animation: girar 2s linear infinite;
}

@keyframes girar {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}
````
[Ejemplo CSS ](https://canodelacuadra.github.io/animacion-css/)
* JavaScript: Si prefieres utilizar JavaScript para crear animaciones más avanzadas, puedes usar bibliotecas como jQuery o animaciones nativas.
[Ejemplo JS ](https://canodelacuadra.github.io/animacion-css/animacion-js.html)
*  O también puedes hacerlo con JQuery. Aquí hay un ejemplo simple con jQuery:

````html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script>
    $(document).ready(function() {
        $(".elemento").animate({ left: "200px" }, "slow");
    });
</script>
````
### Integración en tu sitio web:

* Si estás utilizando HTML y CSS directamente, agrega el código CSS a tu archivo de estilos y asegúrate de aplicar las clases o identificadores adecuados a los elementos que deseas animar.

* Si estás utilizando un CMS como WordPress, es posible que puedas agregar el código CSS o JavaScript en el área de personalización o mediante un complemento específico para animaciones.

### Estilo y diseño: 
Asegúrate de que la animación se integre bien con el diseño general de tu sitio web. Esto incluye la elección de colores, tamaños y posiciones que sean coherentes con la estética de tu sitio.

### Pruebas y ajustes:
 Realiza pruebas en diferentes navegadores y dispositivos para asegurarte de que la animación se vea y funcione como esperas. Realiza ajustes según sea necesario.

### Accesibilidad: 
Al agregar animaciones, ten en cuenta la accesibilidad. Proporciona alternativas o ajustes para usuarios que puedan tener dificultades para interactuar con la animación.

### Optimización:
 Asegúrate de que la animación no afecte negativamente el rendimiento de tu sitio web. Optimiza el código y utiliza técnicas de carga diferida si es necesario para garantizar una experiencia de usuario fluida.

### Documentación:
Si estás trabajando en un equipo o planeas mantener el sitio web a lo largo del tiempo, documenta la animación y su implementación para futuras referencias.

