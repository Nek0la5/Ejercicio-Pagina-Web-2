# Guía Explicativa de Gráficas en Dashboards Administrativos

Este proyecto es una interfaz educativa y de referencia maquetada en HTML5 y CSS3. Su propósito es guiar a administradores y analistas sobre cuándo y cómo utilizar los principales tipos de gráficas (Barras, Líneas, Anillo) dentro de un dashboard de gestión.

## Tecnologías y Técnicas Aplicadas

* **HTML5 Semántico**: Uso de `<aside>`, `<header>`, `<main>`, `<section>`, `<article>` y `<footer>`.
* **CSS Grid (`grid-template-areas`)**: Estructuración del layout principal con áreas nombradas (`sidebar`, `header`, `main`, `footer`).
* **Flexbox**: Alineación de los menúes de navegación, tarjetas explicativas y columnas internas.
* **Navegación Interactiva sin JS**: Anclas HTML (`#barras`, `#lineas`, etc.) combinadas con `scroll-behavior: smooth` en CSS para permitir navegación suave entre secciones.
* **Accesibilidad (a11y)**: Atributos `aria-label`, `role="navigation"`, descripciones `alt` para componentes visuales y estados `:focus` visibles para navegación por teclado.
* **Variables CSS**: Centralización de colores, tipografía y sombras.

## Responsividad

* **Escritorio (>900px)**: Sidebar completo con texto e íconos, disposición a dos columnas para texto e imágenes.
* **Tablet (600px - 900px)**: Sidebar colapsado solo a íconos para maximizar el área de lectura.
* **Móvil (<600px)**: Reorganización del layout a una sola columna mediante Media Queries, posicionando la navegación como una barra horizontal superior scrollable.