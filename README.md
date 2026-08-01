# Página de Presentación Personal — Pablo Mauricio López Carrillo

## Objetivo

Página web de presentación personal desarrollada con Bootstrap 5, aplicando HTML5 semántico,
diseño responsive y personalización mediante CSS propio, como proyecto de la asignatura.

## Cómo ejecutar la página

1. Se clona este repositorio o descarga el ZIP.
2. Abre el archivo `index.html` directamente en tu navegador (doble clic). No requiere
   servidor ni instalación de dependencias, ya que Bootstrap se carga mediante CDN.

## Componentes de Bootstrap utilizados

- **Navbar** (`navbar-expand-lg`) — barra de navegación responsive con menú colapsable
  (hamburguesa) en pantallas pequeñas y medianas.
- **Grid System** (`container`, `row`, `col-*`) — estructura responsive en encabezado,
  proyectos y footer.
- **List Group** — listado de habilidades.
- **Badges / Rounded Pills** — etiquetas de categoría junto a cada habilidad.
- **Cards** — presentación de los 3 proyectos destacados, con imagen, título, descripción
  y botón/enlace.
- **Bootstrap Icons** — íconos de GitHub e Instagram en el footer.

## Elementos personalizados con CSS

- Paleta de colores propia mediante variables CSS (`:root`), en tono morado.
- Tipografía personalizada (Google Fonts — Poppins) en reemplazo de la fuente por defecto.
- Sombras (`box-shadow`) en navbar, foto de perfil y cards de proyectos.
- Animaciones/transiciones en hover: escala en la foto de perfil, elevación en cards de
  proyectos, cambio de color en íconos del footer.
- Línea decorativa debajo de cada título de sección (`::after`).
- Sin uso de `!important` en ninguna regla del CSS.

## Decisiones de diseño

- Se priorizó un diseño limpio y minimalista, evitando saturar cada sección con demasiados
  elementos o colores.
- Se usó una sola paleta de color (morado) como acento, sobre una base neutra blanco/gris,
  para mantener coherencia visual en toda la página.
- El navbar se configuró como `sticky-top` para mantener la navegación accesible durante
  el scroll.
- Las cards de proyectos usan `h-100` y `flex-column` para mantener altura uniforme
  independientemente del largo del texto de cada proyecto.
- De los 3 proyectos mostrados, uno (TraduCode) cuenta con repositorio público en GitHub,
  por lo que su tarjeta enlaza directamente a él. Los otros dos (OwnCloud y Monitoreo de
  Red) fueron proyectos académicos sin repositorio público, por lo que su botón dirige de
  vuelta a la sección de proyectos en lugar de simular un enlace inexistente.

## Responsive

Verificado en los siguientes anchos, sin generar desplazamiento horizontal:
- 320px (móvil)
- 768px (tablet)
- 1280px (escritorio)
-320
<img width="968" height="902" alt="Captura de pantalla 2026-07-31 213432" src="https://github.com/user-attachments/assets/b58e7562-a83e-47e1-8975-fad74dbe86ef" />
-768
  <img width="1202" height="923" alt="Captura de pantalla 2026-07-31 213909" src="https://github.com/user-attachments/assets/33db3a66-28b8-4255-a801-1e815983040b" />
-1280
  <img width="1396" height="902" alt="Captura de pantalla 2026-07-31 214008" src="https://github.com/user-attachments/assets/8f79d7c7-8b2e-4295-aac4-b421c5507e45" />


## Autor

Pablo Mauricio López Carrillo — Estudiante de Ingeniería en Sistemas, UMG Jutiapa 0905-23-14811
