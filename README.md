# Prisma · Aprende desde todos los ángulos

Sitio web de demostración de **Prisma**, una escuela ficticia de cursos en línea, talleres presenciales y programas. Hecho en HTML, CSS y JavaScript, sin dependencias ni proceso de compilación.

> **Todo el contenido es ficticio:** la marca, los cursos, los instructores, las sedes, los precios, las opiniones y los datos de contacto son inventados para mostrar el diseño.

## Qué incluye

**45 páginas** con header y footer compartidos, versión para computadora y para celular.

- **Inicio**: portada, áreas, cursos por iniciar, talleres presenciales, opiniones, programas, sobre nosotros, preguntas frecuentes y contacto.
- **Cursos**: catálogo con búsqueda y filtros por área, modalidad y certificado, más 18 fichas de curso con pestañas (descripción, temario, fechas, horarios, capacitador y requerimientos).
- **Talleres presenciales**: calendario con filtros por mes, área y sede; página de Cursos de Fotografía; y 8 páginas de taller con mapa, fechas, temario, qué llevar, instructor y preguntas frecuentes. Las sedes del taller de retrato se enlazan entre sí.
- **Programas**: listado comparativo y 3 programas con plan de estudios por módulo, calendario, docentes, formas de pago, evaluación y preguntas frecuentes.
- **Certificados**: página del certificado profesional, verificación por folio y año, y pantalla de certificado válido.
- **Institucional**: Conócenos, Preguntas frecuentes (con buscador y temas), Prisma para equipos, Mentorías de proyecto, Redes sociales, Políticas de compra, Aviso legal y Mapa del sitio.

## Funciones de muestra

- Menús desplegables en el header y menú completo en celular.
- Búsqueda desde el header hacia el catálogo (`cursos.html?q=...`), y filtros que se pueden enlazar (`cursos.html?area=foto`, `cursos.html?cert=1`).
- Carrito de muestra: «Comprar ahora» y «Agregar al carrito» guardan los cursos en el navegador; el pago no está habilitado.
- Verificación de certificados de prueba: folio `PRS-FOT1026-01` o `PRS-UXD0826-07`, año `2026`.
- Las imágenes son espacios reservados (recuadro con ícono de cámara).

## Identidad

| Uso | Color |
|---|---|
| Terracota (principal) | `#D9572B` · texto y botones `#C24A20` |
| Tinta café (oscuro) | `#1F1A17` |
| Mostaza (acento) | `#E8B04A` |
| Verde salvia (apoyo) | `#6F8F72` |
| Crema (fondo) | `#F6EFE6` |

Tipografías: **Fraunces** para títulos y **DM Sans** para el resto (Google Fonts).

## Cómo verlo

Abre `index.html` en el navegador. No necesita servidor.


## Estructura

```
index.html                 Inicio
cursos.html                Catálogo
curso-*.html               Fichas de curso
talleres-presenciales.html Calendario de talleres
fotografia.html            Cursos de Fotografía
taller-*.html              Talleres presenciales
programas.html             Listado de programas
programa-*.html            Programas
certificado*.html, verificar-certificado.html
conocenos.html, preguntas-frecuentes.html, empresas.html, mentorias.html,
redes.html, politicas-de-compra.html, aviso-legal.html, mapa-del-sitio.html
assets/site.css            Header, footer y carrito
assets/site.js             Menús, carrito y avisos
assets/favicon.svg
```
