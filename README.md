# Portafolio personal

Proyecto de portafolio web del Sprint 4. Presenta un perfil profesional, habilidades, proyectos y formas de contacto en una página adaptable a distintos tamaños de pantalla.

## Sitio publicado

[Visitar el portafolio](https://murphym90.github.io/web_project_portfolio_es/)

## Contenido y funcionalidades

- **Perfil profesional:** fotografía, presentación, experiencia y tecnologías principales.
- **Descargar CV:** descarga el [archivo PDF](assets/documents/CV_Jonathan_Paul_Medina_Gamino.pdf) incluido en `assets/documents/`.
- **Enlace a GitHub:** abre el [perfil de GitHub](https://github.com/MurphyM90) en una pestaña nueva.
- **Hablemos:** abre un nuevo mensaje de correo dirigido a [murphy.m90.jw@gmail.com](mailto:murphy.m90.jw@gmail.com).
- **Habilidades y herramientas:** muestra iconos de HTML5, CSS3, JavaScript, Git, GitHub y ChatGPT.
- **Proyectos destacados:** presenta una vista previa, tecnologías utilizadas, descripción y enlaces para cada proyecto.
- **Demo en vivo:** la tarjeta de la cafetería abre el [proyecto publicado en GitHub Pages](https://murphym90.github.io/web_project_coffeeshop_es/); la tarjeta “Mi proyecto” abre este [portafolio publicado](https://murphym90.github.io/web_project_portfolio_es/).
- **GitHub de los proyectos:** la tarjeta de la cafetería enlaza a su [repositorio](https://github.com/MurphyM90/web_project_coffeeshop_es); la tarjeta “Mi proyecto” enlaza al [repositorio de este portafolio](https://github.com/MurphyM90/web_project_portfolio_es).
- **Contacto:** el correo [student@tripleten.com](mailto:student@tripleten.com) abre el cliente de correo. Los iconos sociales enlazan a [LinkedIn](https://www.linkedin.com/in/jonathan-paul-medina-gami%C3%B1o-370a92207/), [Facebook](https://www.facebook.com/jonathan.medigam/), [Instagram](https://www.instagram.com/somniator_wolf/) y [X](https://x.com).
- **Estados interactivos:** los enlaces muestran un cambio de opacidad al pasar el cursor o recibir foco con el teclado.
- **Diseño adaptable:** la distribución se ajusta a escritorio, tablet y móvil; las tarjetas cambian de columnas según el espacio disponible.
- **Fondos decorativos y velo:** los brillos radiales y el degradado sobre las imágenes están hechos con CSS.

## Tecnologías

- HTML5 semántico
- CSS3, Flexbox y CSS Grid
- Media queries y container queries
- Degradados CSS y `aspect-ratio` para las vistas previas de proyectos
- SVG para los iconos y WOFF/WOFF2 para las fuentes
- Git, GitHub y GitHub Pages
- Figma como referencia de diseño

La página es estática y no requiere instalar dependencias ni ejecutar un proceso de compilación.

## Abrir el proyecto localmente

1. Clona el repositorio:

   ```bash
   git clone https://github.com/MurphyM90/web_project_portfolio_es.git
   ```

2. Abre la carpeta del proyecto.
3. Abre `index.html` en un navegador, o sírvelo con la extensión Live Server de Visual Studio Code.

## Estructura del proyecto

```text
assets/
├── documents/   # CV en PDF
├── fonts/       # Fuentes Open Sans y Archivo Black
├── icons/       # Iconos SVG
└── images/      # Fotografía y vistas previas de proyectos
styles/          # Estilos generales, header, main, footer y fuentes
index.html       # Estructura de la página
README.md        # Información del proyecto
```
