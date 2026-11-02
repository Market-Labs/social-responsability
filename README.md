# Fundamentos de desarrollo web con HTML y CSS

Curso introductorio para crear una fanpage educativa no oficial de BTS,
pensado para estudiantes de secundaria sin experiencia en programación.
La práctica combina contenido, imágenes y enlaces con colores, espacios y
distribuciones sencillas que se pueden explicar paso a paso.

**Repositorio de código fuente:**
[Market-Labs/social-responsability](https://github.com/Market-Labs/social-responsability)

**Muestra del proyecto en un editor en línea:**
[Fanpage de BTS en CodePen](https://codepen.io/editor/LittleMichi/pen/01a18b3f-5c94-7ce6-8a2f-42be2d6d9be2)

Este enlace es una muestra del resultado. Las prácticas de cada lección
necesitarán sus propios enlaces precargados cuando se preparen los videos.

## Resumen del curso

| Aspecto | Descripción |
| --- | --- |
| Público | Estudiantes de secundaria de 12 a 17 años. |
| Experiencia previa | No se requiere experiencia en programación. |
| Duración planificada | Aproximadamente 60 minutos. |
| Modalidad | Seis lecciones cortas con demostraciones y pausas para practicar. |
| Lenguajes | HTML5 y CSS3. |
| Herramientas | Navegador, editor de código gratuito en línea, GitHub y YouTube. |
| Resultado | Fanpage con portada, integrantes, momentos y pie de página. |

El curso corresponde al trabajo complementario de responsabilidad social
de **1ASI0730 Aplicaciones Web**, ciclo **202620**, de la Universidad
Peruana de Ciencias Aplicadas.

## Qué aprenderás

- Reconocer la función de HTML y CSS en una página web.
- Utilizar etiquetas, elementos y atributos de HTML.
- Agregar encabezados, párrafos, listas, imágenes y enlaces.
- Aplicar selectores y propiedades de color, fuente, espacios y bordes.
- Organizar contenido y adaptar la página a pantallas pequeñas.
- Identificar errores comunes, como escribir mal el nombre del archivo CSS.

## Cómo empezar sin instalar herramientas

1. Abre un editor gratuito en línea, como CodePen, desde tu navegador.
2. Crea un proyecto de HTML y CSS con dos archivos: `index.html` y `styles.css`.
3. Copia el contenido de [starter-files/index.html](starter-files/index.html)
   y [starter-files/styles.css](starter-files/styles.css) en los archivos
   correspondientes del editor.
4. Comprueba que el HTML incluya el enlace al nombre exacto del archivo CSS:

   ```html
   <link rel="stylesheet" href="styles.css">
   ```

5. Si el editor creó un archivo llamado `style.css`, renómbralo a
   `styles.css` para que coincida con el enlace del HTML.
6. Usa la vista previa del editor para observar cada cambio durante la práctica.
7. Compara tu avance con los archivos de [completed-examples](completed-examples).

Necesitas conexión a Internet: las imágenes se cargan desde enlaces externos
y los videos se abren en YouTube al seleccionar sus vistas previas.
El proyecto no utiliza JavaScript, bibliotecas ni pasos de compilación.
Todas las demostraciones del curso deben realizarse en el editor en línea.

## Estructura del repositorio

```text
social-responsability/
├── README.md
├── .gitignore
├── starter-files/
│   ├── index.html
│   └── styles.css
├── completed-examples/
│   ├── index.html
│   └── styles.css
└── scripts/
    └── .gitkeep
```

- `starter-files`: base sencilla para comenzar las prácticas.
- `completed-examples`: fanpage terminada que sirve como referencia.
- `scripts`: carpeta reservada para los guiones de las lecciones;
  `.gitkeep` permite conservarla en Git mientras se preparan.
- `.gitignore`: excluye la configuración local de `.idea`.

Las carpetas inicial y final son proyectos separados: cada `index.html`
utiliza el `styles.css` de su propia carpeta.

## Proyecto de práctica: BTS Perú

La página terminada mantiene cuatro partes:

1. **Portada:** presentación del grupo y acceso a sus integrantes.
2. **Integrantes:** fotografías y descripciones breves de los siete miembros.
3. **Momentos:** tres vistas previas de videos, una por fecha en Lima.
4. **Pie de página:** aviso educativo no oficial y enlace al sitio de BTS.

El botón principal **Mirar ahora** dirige al canal oficial BANGTANTV.
Las tarjetas de Momentos abren los videos de sus respectivas fechas en
YouTube. Las imágenes se enlazan desde sus fuentes; no hay archivos de
imagen que deban subirse al editor.

Los nombres de las clases están en español. El CSS está organizado en
estilos generales, menú, portada, integrantes, momentos, pie de página,
adaptación a pantallas pequeñas y accesibilidad. Las propiedades se
escriben en líneas separadas para facilitar la lectura y la exposición.

## Secuencia propuesta de lecciones

Los tiempos incluyen explicaciones, demostraciones y pausas para practicar.
Los enlaces a las lecciones y a sus prácticas todavía están pendientes de
publicación; el enlace de muestra no los reemplaza.

| Lección | Duración | Contenido y práctica | Video no listado | Editor precargado |
| --- | --- | --- | --- | --- |
| 1. ¿Qué es una página web? | 5 min | Diferenciar contenido HTML y apariencia CSS; reconocer las partes de la fanpage. | Pendiente | Pendiente |
| 2. Mi primera estructura HTML | 10 min | Explicar etiquetas y atributos; crear un título, un párrafo y las secciones principales. | Pendiente | Pendiente |
| 3. Imágenes, listas y enlaces | 10 min | Presentar integrantes, agregar imágenes con texto alternativo y enlazar los videos. | Pendiente | Pendiente |
| 4. Primeros estilos con CSS | 10 min | Vincular el CSS y practicar selectores, colores, fuentes, espacios y bordes. | Pendiente | Pendiente |
| 5. Construimos la fanpage | 15 min | Organizar el menú y las tarjetas; completar la portada y adaptar el diseño al celular. | Pendiente | Pendiente |
| 6. Revisamos y compartimos | 10 min | Corregir nombres de archivos y enlaces, comprobar el diseño y revisar errores comunes. | Pendiente | Pendiente |
| **Total** | **60 min** | | | |

Para grabar cada lección:

- Mostrar el código únicamente en un editor gratuito en línea.
- Explicar con lenguaje sencillo y avanzar desde los conceptos básicos.
- Incluir narración, texto en pantalla y anotaciones que orienten la práctica.
- Dejar pausas para que los estudiantes realicen los ejercicios.
- Publicar los videos como **no listados** en YouTube.
- Añadir en cada descripción el enlace al editor precargado de esa práctica.
- Mantener el contenido y el código sin branding ni referencias a los autores.

## Elaboración en equipo

Los aportes se registran mediante commits en este repositorio público de la
organización Market-Labs. Se utiliza Conventional Commits para describir
los cambios, por ejemplo `feat(course): add starter materials` o
`docs(readme): describe online learning workflow`.

| Dato del equipo | Detalle |
| --- | --- |
| Nombre del equipo | MartLabs |
| NRC | 8130 |
| Líder | Pendiente de confirmar. |
| Responsabilidades | Pendiente de completar con los aportes reales. |

### Integrantes

| Código de estudiante | Estudiante |
| --- | --- |
| U201923820 | Cáceres Pizarro, Albino Florencio |
| U202410746 | Huaranga Romero, Matias Daniel |
| U20231B504 | Merino Ordinola, Winnie Lisbeth |
| u201815005 | Quispe Almonacid, Andre Sebastian |
| U20241G152 | Torres Huaman, Alexis Calin |

El reporte individual de participación se entrega por separado en Word y
PDF, según las indicaciones del curso. Los commits deben reflejar aportes
reales de cada integrante.

## Estado de preparación y entrega

- [x] Código de la fanpage terminada en HTML y CSS.
- [x] Archivos iniciales para las prácticas.
- [x] Instrucciones para trabajar sin instalaciones.
- [x] Enlace de muestra al proyecto en el editor en línea.
- [ ] Guiones de grabación en `scripts`.
- [ ] Enlaces a las seis lecciones no listadas en YouTube.
- [ ] Enlaces a editores precargados para cada lección.
- [x] NRC, nombre del equipo y relación de integrantes.
- [ ] Confirmación del líder, responsabilidades y resumen de aportes.
- [ ] Exportación del plan de curso a PDF para la entrega.
- [ ] Reporte de participación en Word y PDF.
- [ ] Revisión de la nomenclatura del repositorio antes de la entrega.

El statement indica el nombre `webdev-course-[nombre del equipo]`, que
para este equipo sería `webdev-course-MartLabs`. Este proyecto conserva el destino solicitado,
`Market-Labs/social-responsability`; queda pendiente confirmar la
nomenclatura con el docente o adecuarla antes de la entrega.

El nombre indicado para el PDF del plan de curso es
`upc-pre-202620-1asi0730-8130-MartLabs-course-plan.pdf`.
Este README centraliza el resumen, la secuencia de lecciones, el repositorio,
las prácticas y la elaboración en equipo para completar ese plan.

## Fuentes del contenido de la fanpage

- Integrantes y retratos: [BIGHIT MUSIC](https://bighitsmusic.com/bts/profile).
- Logotipo: [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:BTS_text_logo.svg).
- Fechas y recinto: [Ticketmaster Perú](https://help.ticketmaster.pe/hc/es-419/articles/45168456892433-BTS-World-Tour).
- Foto de portada: [RPP](https://rpp.pe/musica/conciertos/bts-comienza-concierto-en-estadio-san-marcos-y-hace-vibrar-a-fans-video-noticia-1711415).
- Primera fecha, 07/10/2026: [video en YouTube](https://www.youtube.com/watch?v=vRbizbNFhyU).
- Segunda fecha, 09/10/2026: [video en YouTube](https://www.youtube.com/watch?v=yjgpKqg5rXA).
- Tercera fecha, 10/10/2026: [video en YouTube](https://www.youtube.com/watch?v=68M0HwVK_0o).
- Canal del botón principal: [BANGTANTV](https://www.youtube.com/user/BANGTANTV).

BTS Perú es una fanpage educativa no oficial. No está afiliada a BTS,
BIGHIT MUSIC ni HYBE. Las imágenes y los videos pertenecen a sus
respectivos titulares; este repositorio no distribuye los archivos de esos
medios ni concede permisos para reutilizarlos.
