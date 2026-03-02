# avoris-responsive-test
Prueba técnica de maquetación responsive (HTML, SCSS, JS)


Descripción

Esta prueba consiste en la maquetación responsive de la propuesta de diseño facilitada en Figma, implementada con HTML, SCSS y JavaScript.
El objetivo principal ha sido replicar el diseño respetando la estructura visual, pero también añadiendo mejoras a nivel de accesibilidad, organización de código y comportamiento dinámico.
Tecnologías utilizadas

- HTML5 semántico
- SCSS (organizado por parciales)
- JavaScript modular
- Vite como entorno de desarrollo y build
- GitHub Pages para publicación

He utilizado SCSS para estructurar mejor los estilos (partials por componentes, layout, variables y mixins), lo que permite mantener el código más limpio y escalable.


Responsive

La maquetación está adaptada a:

- Desktop
- Tablet
- Mobile

He utilizado media queries y medidas fluidas para garantizar una adaptación progresiva sin romper estructura ni jerarquía visual.


Accesibilidad

Se han añadido mejoras que no estaban explícitamente detalladas en el diseño:

- Uso de etiquetas semánticas (header, main, section, article, nav, etc.).
- aria-expanded, aria-hidden, aria-live donde es necesario.
- Navegación con teclado.
- focus-visible personalizado.
- Cierre del popover con tecla Escape.
- Respeto de prefers-reduced-motion.


Funcionalidad añadida

Aunque el diseño no incluía comportamiento dinámico detallado, he implementado:

- Filtros funcionales por destino, categoría, alojamiento y precio.
- Cálculo dinámico de precios.
- Cálculo automático según fechas seleccionadas.
- Desglose de precios en popover accesible.


Carrusel funcional en el hero.

La intención ha sido demostrar no solo maquetación visual, sino capacidad de interacción y lógica en frontend.


Sobre el “PENDING APPROVAL”

En el diseño de Figma aparecía un “PENDING APPROVAL” en algunos breakpoints. Tras analizarlo, entiendo que hace referencia a un posible estado dinámico o contenido aún no definido.
Dado que en esta prueba el contenido es estático y no existe backend real ni validación asociada, no lo he añadido para evitar introducir comportamiento ficticio que no este justificado.
No obstante, he tenido en cuenta su posible función en la estructura del layout.


Estructura del proyecto

El proyecto está organizado de la siguiente manera:

- src/ → código fuente
- public/ → assets estáticos
- dist/ → versión compilada para producción

La versión publicada en GitHub Pages corresponde al build final.


Cómo visualizar el proyecto

- Opción 1 – Directamente online:
https://tanyabocu.github.io/avoris-responsive-test/

- Opción 2 – En local:

Descargar el proyecto:

- Ejecutar:

npm install
npm run dev

- Para generar versión producción:

npm run build
Consideraciones finales

He intentado mantener un equilibrio entre fidelidad al diseño y buenas prácticas de frontend moderno.
Más allá de replicar la interfaz, me he centrado en:

- Estructura clara.
- Código mantenible.
- Comportamiento realista.
- Accesibilidad.
- Responsive coherente.
