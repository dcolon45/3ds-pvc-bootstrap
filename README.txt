========================================
  3D's PVC Innovative - Sitio Web Responsivo con Bootstrap
  WADE 1000L - Tarea de Assessment 5.1
  Estudiante: David
  Fecha: 20 de junio de 2026
========================================

DESCRIPCIÓN DEL PROYECTO
-------------------------
Sitio web responsivo de 4 páginas interconectadas para el negocio
"3D's PVC Innovative", construido con HTML5, CSS personalizado y
el framework Bootstrap 5. El sitio presenta el negocio, una galería
de proyectos tipo portafolio y un formulario de contacto validado.

ARCHIVOS INCLUIDOS
------------------
- index.html             : Página de inicio
- proyectos.html         : Página de portafolio/blog con tarjetas Bootstrap
- proyecto-detalle.html  : Página de detalle dinámica para cada proyecto
- contacto.html          : Página de contacto con formulario validado
- styles.css             : CSS personalizado sobre Bootstrap
- images/                : Carpeta de imágenes del proyecto
- README.txt             : Este archivo

PÁGINAS DEL SITIO
-----------------
1. INICIO (index.html)
   - Barra de navegación Bootstrap con 3 enlaces (Inicio, Proyectos, Contacto)
   - Encabezado con imagen de fondo y título
   - Sección "Acerca de mí" con información del propietario
   - Sección de servicios
   - Llamado a la acción que dirige a la página de Contacto

2. PROYECTOS (proyectos.html)
   - Galería tipo portafolio con 6 proyectos
   - Tarjetas de Bootstrap (card) para cada proyecto
   - Botón "Leer más" que lleva a la página de detalle correspondiente

3. DETALLE DE PROYECTO (proyecto-detalle.html)
   - Página de detalle dinámica: el contenido cambia según el
     parámetro "id" en la URL (ejemplo: proyecto-detalle.html?id=2)
   - Migas de pan (breadcrumb) para regresar fácilmente

4. CONTACTO (contacto.html)
   - Formulario de contacto ficticio (nombre, correo, teléfono, mensaje)
   - Validación de campos con las clases de Bootstrap (needs-validation)
   - Información de contacto adicional (correo y teléfono ficticios)

TECNOLOGÍAS UTILIZADAS
-----------------------
- HTML5 semántico (header, nav, main, section, footer)
- Bootstrap 5.3.3 (vía CDN) para el sistema de grid y componentes
- CSS personalizado para colores, tipografía y detalles de marca
- JavaScript básico para la validación del formulario y el
  contenido dinámico de la página de detalle

DISEÑO RESPONSIVO
------------------
El sitio utiliza el sistema de grid de Bootstrap (col-md-, col-lg-)
para adaptarse automáticamente a tablets y dispositivos móviles.
Se añadieron media queries adicionales en styles.css para ajustar
tamaños de texto en pantallas pequeñas.

ENLACE DE GITHUB
----------------
Repositorio:     https://github.com/dcolon45/3ds-pvc-bootstrap
Página en vivo:  https://dcolon45.github.io/3ds-pvc-bootstrap/

========================================
