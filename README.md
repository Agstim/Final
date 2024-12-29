# Proyecto "Tu Empresa" - Frontend con JavaScript

Este es un proyecto de estudio desarrollado como parte del curso Frontend con JavaScript de "Talento Tech". El objetivo es crear una página web funcional para un negocio ficticio de servicio técnico informático y móvil. 

## Descripción del proyecto

El proyecto consiste en una página web principal con información sobre los servicios y productos ofrecidos por "Tu Empresa", así como una página separada para gestionar un carrito de compras. Incluye navegación interna con enlaces entre secciones y entre páginas. Se aplicaron tecnologías modernas como HTML, CSS, Bootstrap y JavaScript para lograr un diseño responsivo e interactivo.

### Características principales:
- **Página principal (`index.html`)**: 
    - Navegación interna con un navbar fijo que se adapta a dispositivos móviles.
    - Secciones como Inicio, Servicios, Productos y Contacto.
    - Un diseño claro y profesional.
- **Página de Carrito (`pages/carrito.html`)**:
    - Gestión del carrito con estilos personalizados y redirección al inicio después de un tiempo.
    - Funcionalidad implementada con JavaScript.
- **Diseño responsivo**: Se utiliza Bootstrap para lograr compatibilidad con distintos dispositivos.

## Estructura del proyecto
```
proyecto/
│
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── carrito.css
│   ├── js/
│   │   ├── carrito.js
│   │   └── Funciones_index.js
│   └── media/
│       ├── images/
│       └── icons/
│
├── pages/
│   └── carrito.html
│
├── index.html
└── README.md
```

### Archivos principales

- **`index.html`**: Página principal del sitio.
- **`pages/carrito.html`**: Página dedicada al carrito de compras.
- **`assets/css/style.css`**: Contiene los estilos generales del sitio, aplicados a todas las páginas.
- **`assets/css/carrito.css`**: Archivo CSS específico para estilizar la página del carrito. Incluye reglas para mejorar la presentación de los elementos del carrito y la experiencia del usuario.
- **`assets/js/script1.js` y `assets/js/script2.js`**: Scripts que manejan la lógica y funcionalidad de la página web, incluyendo redirecciones y manejo del carrito.

## Cómo utilizar este proyecto

### Requisitos previos
- Tener un navegador web actualizado (Chrome, Firefox, Edge, etc.).
- Un servidor local para visualizar los archivos correctamente (recomendado: [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) si estás utilizando VS Code).

### Instrucciones

1. **Clonar el repositorio**: Descarga o clona el repositorio en tu máquina local:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```

2. **Abrir el proyecto**: Navega a la carpeta del proyecto y abre `index.html` en tu navegador o ejecuta un servidor local para visualizarlo correctamente.

3. **Navegación**: Explora las distintas secciones de la página y prueba la funcionalidad del carrito de compras en `pages/carrito.html`.

### Personalización

Si deseas personalizar el proyecto, puedes:
- Modificar los estilos globales en `assets/css/style.css`.
- Cambiar los estilos específicos del carrito en `assets/css/carrito.css`.
- Agregar funcionalidad adicional a los scripts en `assets/js/`.

## Créditos
Este proyecto fue desarrollado como parte del curso de "Talento Tech" en el módulo Frontend con JavaScript.

## Licencia
Este proyecto es solo con fines educativos y no tiene una licencia específica.

