# Repositorio Educativo Digital

Aplicación web estática en HTML, CSS y JavaScript sin backend. La interfaz incluye navegación multipantalla mediante hash routes, catálogo de herramientas, métodos de estudio, tres minijuegos editables, planificador de clases, biblioteca de planificaciones y soporte.

## Ejecutar
1. Descomprimí `repositorio_educativo_digital.zip`.
2. Abrí `index.html` en un navegador moderno. No necesita instalar dependencias.
3. Para una experiencia más consistente con impresión y portapapeles, también podés servir la carpeta con cualquier servidor estático local.

## Estructura
- `index.html`: carcasa de la aplicación y navegación persistente.
- `css/styles.css`: identidad visual responsive y estilos de impresión.
- `js/main.js`: rutas, catálogo, métodos, juegos, planificación y almacenamiento.

## Funciones implementadas
- Navegación independiente por hash, enlaces de atrás/adelante y menú móvil.
- Catálogo con búsqueda y filtros.
- Fichas de métodos de estudio con enlaces a recursos externos.
- Tarjetas de memoria, cuestionarios de selección múltiple y unir conceptos; crear, editar, duplicar, eliminar y guardar conjuntos.
- Planificador de 9 pasos, borradores/completadas, duplicación, edición, impresión/Guardar como PDF desde el diálogo del navegador.
- Biblioteca de planificaciones con búsqueda y filtros.
- Adjuntos temporales de hasta 5 MB por archivo y formatos comunes de documentos e imágenes. Se conserva el nombre/tamaño durante la sesión; el contenido de los archivos no se guarda ni se sube a un servidor.
- Soporte con enlace `wa.me` normalizado y formulario que prepara/copia texto; no envía consultas a un servidor.
- Persistencia de actividades y planificaciones en `localStorage`.

## Limitaciones y datos pendientes
- **Instalación oficial:** el enlace no aparece confirmado en los documentos revisados; el botón informa esta limitación y no simula una descarga.
- **Identificador de soporte:** `digitalrepository.support` se muestra como fue proporcionado, sin asumir que sea una dirección de correo.
- **Novedades:** no se encontró un historial oficial de versiones; se presenta una sección pendiente de documentación.
- **Especialidad y materias:** la documentación proporcionada indica Informática y Construcciones Civiles (esta última en desarrollo), con organización por especialidad, curso y materia. El catálogo de esta versión contiene ejemplos de herramientas externas y debe ser revisado por el responsable antes de publicar.
- **Almacenamiento:** `localStorage` guarda datos estructurados pequeños solo en este navegador/dispositivo. No hay cuentas, nube, sincronización ni copias remotas. Si el navegador bloquea el almacenamiento o se borra, los datos pueden perderse.
- **Adjuntos:** no persisten al cerrar o recargar la página; solo se valida nombre/extensión y tamaño, y no se ejecutan ni se suben.
- **Métodos y enlaces externos:** se incluyeron referencias educativas conocidas; la disponibilidad y el contenido de terceros pueden cambiar y deben verificarse nuevamente antes de una publicación formal.
- **Accesibilidad:** incluye etiquetas, foco visible, enlace para saltar al contenido y adaptación móvil; se recomienda realizar una auditoría formal con teclado y lector de pantalla antes del despliegue.

## Publicación
Antes de publicar, confirmar con la persona responsable: nombre/identidad oficial, URL oficial de instalación (si existe), identificador de soporte, vigencia de los enlaces, catálogo curricular por curso/materia y cualquier historial real de versiones. No se implementó backend ni se simula envío remoto.
