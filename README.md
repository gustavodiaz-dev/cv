# CV Interactivo Profesional — Gustavo David Diaz Maldonado

Este repositorio aloja la versión interactiva y optimizada para impresión de mi currículum profesional, desarrollado con las mejores prácticas web y enfocado en mi perfil de **Administrador de Sistemas TI** en transición activa hacia roles de **Cloud / DevOps / SRE**.

🔗 **Versión en Vivo:** [[gustavodiaz-gif.github.io/cv](https://gustavodiaz-dev.github.io/cv/)/]

---

## Características del Proyecto

* **Diseño Responsivo e Interactivo**: Contenedor estilo *glassmorphism* adaptado para dispositivos móviles y de escritorio.
* **Modo Claro / Oscuro**: Selector de temas integrado que persiste la preferencia del usuario en el navegador utilizando `localStorage`.
* **Copiado con un Clic**: Botones interactivos en la sección de contacto que permiten copiar el correo, teléfono y enlaces a redes directamente al portapapeles con confirmación visual de `¡Copiado!`.
* **PDF Impecable (1 Página)**: Hoja de estilos `@media print` optimizada que reestructura el documento automáticamente para generar un PDF de dos columnas de **exactamente una página Carta/A4**, eliminando controles interactivos y utilizando un tema de alto contraste apto para impresión física.
* **Optimización SEO y Accesibilidad**: 
  - Datos estructurados **JSON-LD (Person schema)** para un óptimo rastreo en buscadores.
  - Atributos de accesibilidad (`aria-hidden="true"`) en iconos SVG decorativos.
  - Indicadores visuales claros de enfoque (`:focus-visible`) para navegación por teclado.

---

## Tecnologías Utilizadas

* **HTML5**: Marcado semántico y estructurado.
* **Vanilla CSS3**: Estilos customizados con variables nativas, Flexbox, Grid y animaciones de entrada.
* **JavaScript**: Interactividad de tema (claro/oscuro), lógica de copiado rápido al portapapeles y activación del cuadro de impresión nativo del navegador.

---

## Estructura del Repositorio

* `index.html`: Estructura del currículum y metadatos (SEO/OG/JSON-LD).
* `style.css`: Estilos visuales del sitio y media query de impresión.
* `script.js`: Lógica interactiva en JavaScript.
* `CV_Gustavo_Diaz.pdf`: Archivo del currículum en PDF listo para descargar.
