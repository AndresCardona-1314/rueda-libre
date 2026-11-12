## Rueda Libre

### Descripción del proyecto

Rueda Libre es un sitio para conocer los servicios de alquiler de bicicletas y recorridos guiados por Medellín. Incluye información de tarifas, un formulario de reservas y una landing independiente para las rutas nocturnas, con inscripción y planes.

### Enlaces publicados

- [Sitio principal](https://andrescardona-1314.github.io/rueda-libre/)
- [Tarifas](https://andrescardona-1314.github.io/rueda-libre/paginas/tarifas.html)
- [Reservas](https://andrescardona-1314.github.io/rueda-libre/paginas/reservas.html)
- [Landing Rueda Nocturna](https://andrescardona-1314.github.io/rueda-libre/nocturna/)
- [Repositorio en GitHub](https://github.com/AndresCardona-1314/rueda-libre)

### Páginas

- [`index.html`](index.html): página principal, servicios, promociones y navegación.
- [`paginas/tarifas.html`](paginas/tarifas.html): tarifas de alquiler y recorridos.
- [`paginas/reservas.html`](paginas/reservas.html): formulario de reserva de bicicletas.
- [`nocturna/index.html`](nocturna/index.html): rutas nocturnas, planes e inscripción.
- [`nocturna/componentes.html`](nocturna/componentes.html): muestra de componentes y estilos del kit Nocturna.

### Tecnologías

- HTML5 semántico.
- Bootstrap 5.3.8 y Bootstrap Icons 1.13.2 en las páginas principales.
- CSS propio para la paleta, los componentes y los ajustes de marca de Bootstrap.
- Tailwind CSS 4.3.5 con CLI para Nocturna; el tema define colores y tipografías del proyecto.
- Google Fonts: Montserrat y Open Sans como tipografías de títulos y texto.
- GitHub Pages para publicar el sitio.

### Recomendación de framework — MiniReto 8

Se recomienda conservar Bootstrap en el sitio principal: ya resuelve la cuadrícula, la navegación, el carrusel y componentes de las páginas existentes, lo que facilita mantenerlas y ampliarlas. Tailwind resulta adecuado para la landing Nocturna, que tiene una identidad visual propia y estilos específicos compilados desde las utilidades que utiliza. La experiencia del proyecto mostró que Bootstrap agiliza interfaces convencionales, mientras que Tailwind ofrece control más directo del diseño. Para evitar conflictos de estilos, conviene no cargar ambos frameworks en una misma página.

### Capturas



- Escritorio: `img/capturas/captura_rueda_libre_escritorio.png`.
`img/capturas/captura_rueda_nocturna_escritorio.png`.
- Celular: `img/capturas/captura_rueda_libre_cel.png`.
`img/capturas/captura_rueda_nocturna_cel.png`.




### Aprendizajes

- Estructurar páginas con HTML semántico y asociar etiquetas, controles y mensajes de validación en formularios.
- Aplicar Grid para distribuir tarjetas y campos, y Flexbox para alinear contenido y mantener acciones al final de las tarjetas.
- Usar el box model de forma consistente con bordes, rellenos y espacios responsivos.
- Comparar un framework de componentes como Bootstrap con un enfoque de utilidades como Tailwind, incluyendo la generación de CSS con la CLI.
- Validar accesibilidad y estructura con el W3C, y revisar la presentación en distintos anchos de pantalla y en modo oscuro.

### Autor

- **Nombre:** Andrés Cardona.
- **Programa:** Coder de Riwi.
- **GitHub:** [AndresCardona-1314](https://github.com/AndresCardona-1314).









