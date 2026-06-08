# Proyecto Web Personal - Portafolio de Aprendizaje

## Acerca del proyecto

Este trabajo práctico fue elaborado en el marco de la asignatura **Fundamentos de Programación**, con el objetivo de aplicar los conceptos clave relacionados con **HTML5, hojas de estilo CSS, organización semántica del contenido, manejo de formularios, integración de recursos multimedia y adaptación visual a distintos dispositivos**.

El sitio se compone de varias páginas interconectadas mediante un sistema de navegación basado en rutas relativas, e incorpora distintos elementos como formularios de envío, tablas comparativas, galería de imágenes, contenido de audio/video y una estructura adaptable mediante **consultas de medios (media queries)**.

Como parte de la evolución del proyecto, se añadió una nueva sección denominada **portafolio.html**, creada con el fin de exponer las competencias técnicas adquiridas, los proyectos desarrollados durante el curso, el nivel de progreso alcanzado y las aspiraciones profesionales a futuro, todo ello manteniendo una línea gráfica consistente con el resto del sitio.

---

## Finalidad del trabajo

Poner en práctica los temas tratados durante la segunda unidad, entre los cuales se incluyen:

- Uso correcto de etiquetas semánticas HTML
- Aplicación de sintaxis y reglas CSS
- Manejo de selectores de tipo, clase, ID y pseudo-clases
- Ajustes visuales mediante propiedades de color, tipografía y espaciado
- Comprensión del modelo de caja (padding, margin, border)
- Implementación de layouts con Flexbox
- Uso de CSS Grid para disposición de elementos
- Adaptación de interfaces a diferentes tamaños de pantalla
- Implementación de media queries para diseño responsivo

---

## Páginas que componen el sitio

### index.html
Pantalla principal donde se muestra una presentación personal, áreas de interés, contenido multimedia (audio, video local e iframe de YouTube), formularios de consulta y una tabla con el plan de estudio semanal.

### buscar.html
Espacio destinado a la simulación del envío de datos desde formularios utilizando el método **GET**, permitiendo visualizar los parámetros transmitidos directamente en la barra de direcciones del navegador.

### contacto.html
Página enfocada en la validación de formularios mediante atributos nativos de HTML como:

- required (campos obligatorios)
- minlength y maxlength (longitud de texto)
- pattern (expresiones regulares para contraseñas)
- type="email" y type="date"

### portafolio.html
Sección nueva integrada al proyecto original, que incluye:

- Tarjetas descriptivas de los trabajos realizados
- Tabla con habilidades técnicas y su nivel de dominio
- Imagen ilustrativa por cada proyecto
- Organización semántica con etiquetas modernas
- Adaptación visual para móviles y tablets
- Listado de metas profesionales organizadas por plazos
- Uso combinado de Grid y Flexbox para la maquetación

---

##  Organización de archivos

 
PracticaP2/
│
├── audio/ # Archivos de sonido (.mp3)
│
├── css/
│ ├── buscar.css # Estilos específicos para la página de búsqueda
│ ├── contacto.css # Estilos específicos para el formulario de contacto
│ ├── general.css # Estilos comunes a todas las páginas
│ ├── index.css # Estilos propios de la página principal
│ └── portafolio.css # Estilos exclusivos de la sección portafolio
│
├── img/ # Imágenes de respaldo, logos y recursos visuales
│
├── pages/
│ ├── buscar.html
│ ├── portafolio.html
│ └── cto/
│ └── contacto.html
│
├── video/ # Videos de muestra (.mp4)
│
└── index.html # Página de inicio
