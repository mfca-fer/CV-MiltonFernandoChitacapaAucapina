# Portafolio Profesional - Milton Fernando Chitacapa Aucapiña

Este archivo contiene el resumen completo de todo el trabajo realizado en este proyecto, la estructura implementada y las instrucciones necesarias para que puedas continuar o publicar tu sitio web en el futuro con solo leer esta guía.

---

## 📋 Resumen del Trabajo Realizado

1.  **Extracción de Información y Estructura:**
    *   Leímos y analizamos el contenido de tu currículum original: [MILTON FERNANDO CHITACAPA AUCAPIÑA-CV.pdf](file:///d:/Proyectos/Hoja_VIda/MILTON%20FERNANDO%20CHITACAPA%20AUCAPI%C3%91A-CV.pdf).
    *   Estructuramos las secciones del sitio web de forma semántica y ordenada en base a ese contenido:
        *   **Hero Section:** Introducción con tu nombre, rol profesional y redes.
        *   **Sobre Mí:** Párrafos profesionales y datos generales de contacto.
        *   **Habilidades:** Clasificadas en Técnicas (Redes, Sistemas Operativos, Programación, Diseño y Hardware) y Blandas (Liderazgo, Gestión de Negocios, etc.).
        *   **Experiencia:** Línea de tiempo interactiva con tus prácticas en APC Tecnología, Vinculación en la U.E. Mary Corylé, Administración en "José José / La Leyenda" y roles de logística.
        *   **Educación:** Estudios en la Universidad de Cuenca/ITAS y el Instituto Francisco Febres Cordero.
        *   **Certificaciones:** Insignias de tus certificaciones Cisco Academy.
        *   **Referencias:** Contactos de José Cárdenas y Miguel Ángel Vizhco.
        *   **Intereses:** Hobbies relacionados con aprendizaje autodidacta y hardware.

2.  **Identificación y Uso de la Paleta de Colores de tu CV:**
    *   Extrajimos digitalmente los colores exactos de tu documento PDF original para que el diseño mantenga la misma estética que te gusta:
        *   🎨 **Fondo Claro (Crema):** `#ece9e5`
        *   🎨 **Texto Principal / Fondo Oscuro:** `#0f1419`
        *   🎨 **Acento (Azul Pizarra):** `#566c81`
        *   🎨 **Contenedores Secundarios (Blanco):** `#ffffff`

3.  **Construcción del Sitio Web (`index.html`):**
    *   Creamos un sitio web de una sola página (`Single-Page Application`) en [index.html](file:///d:/Proyectos/Hoja_VIda/index.html).
    *   Establecimos el **Modo Oscuro** como tema predeterminado del sitio web. También implementamos un interruptor manual en la cabecera para cambiar entre modo claro y modo oscuro de forma interactiva y fluida. En modo oscuro, el fondo crema cambia a un negro-azul profundo (`#0f1419`) y el texto cambia a crema (`#ece9e5`) para un contraste premium excelente.
    *   Agregamos un **SVG animado y reactivo de Redes/Servidores** en la cabecera para ilustrar visualmente tu especialización.

4.  **Integración de Redes Sociales y WhatsApp:**
    *   Integramos tus cuentas directas con íconos vectoriales modernos:
        *   **WhatsApp:** Enlace al chat directo (`https://wa.me/593987463951`).
        *   **Facebook:** `@fer.chitacapa` (`https://www.facebook.com/fer.chitacapa/`).
        *   **Twitter / X:** `@ferchitacapa` (`https://x.com/ferchitacapa`).
        *   **Instagram:** `@nando_mfca` (`https://www.instagram.com/nando_mfca?igsh=MTR0ZHVmaTJmOHl3bg==`).
    *   Los enlaces se colocaron en el Hero (debajo del título), en la Tarjeta de Contacto ("Sobre Mí") y en el pie de página.

5.  **Optimización de Impresión:**
    *   Desarrollamos una hoja de estilos de impresión especial (`@media print`). Si presionas `Ctrl + P` (Imprimir) en el navegador, el sitio web se convierte automáticamente en un currículum físico limpio de 2 páginas con formato ideal en blanco y negro, ocultando elementos innecesarios como botones, interactividades y fondos decorativos.

---

## 📂 Estructura de Archivos del Proyecto

El proyecto está diseñado para ser sumamente ligero y autónomo, reduciéndose a:

```text
d:\Proyectos\Hoja_VIda/
├── MILTON FERNANDO CHITACAPA AUCAPIÑA-CV.pdf  <-- Tu currículum original
├── index.html                                  <-- El portafolio web interactivo construido
└── README.md                                   <-- Esta guía de resumen y ayuda
```

---

## 💻 Cómo Ejecutar y Probar el Sitio Web

### Opción 1: Doble Clic (Directo)
Puedes ir a la carpeta `d:\Proyectos\Hoja_VIda\` y hacer doble clic sobre el archivo `index.html` para abrirlo en Chrome, Edge o Firefox. La mayoría de las funciones (incluyendo el cambio de tema) funcionarán de inmediato.

### Opción 2: Servidor Local (Python)
Para simular cómo se comportará en internet, puedes levantar un servidor local en la misma carpeta:
1. Abre tu terminal de PowerShell o CMD en la carpeta del proyecto.
2. Ejecuta el comando:
   ```bash
   python -m http.server 8000
   ```
3. Abre tu navegador e ingresa a: `http://localhost:8000/index.html`

---

## 🚀 Cómo Publicar en GitHub Pages (Gratis)

Para subir esta página a internet y compartir tu portafolio profesional en tus perfiles, sigue estos sencillos pasos:

1.  **Crea una Cuenta en GitHub:** Si no tienes una, regístrate en [github.com](https://github.com).
2.  **Crea un Repositorio Nuevo:**
    *   Haz clic en "New Repository".
    *   Dale un nombre (ej. `mi-portafolio` o tu nombre de usuario).
    *   Asegúrate de que sea **Público** (Public).
3.  **Sube el Archivo `index.html`:**
    *   Arrastra el archivo `index.html` directamente a la web del repositorio para subirlo.
    *   Guarda los cambios haciendo clic en **Commit changes**.
4.  **Activa GitHub Pages:**
    *   Entra a la pestaña **Settings** (Configuración) dentro de tu repositorio.
    *   En el menú de la izquierda, selecciona la opción **Pages**.
    *   Bajo la sección **Build and deployment**, en **Source** selecciona `Deploy from a branch`.
    *   En **Branch** selecciona `main` (o la rama correspondiente) y la carpeta `/root` (raíz).
    *   Haz clic en **Save** (Guardar).
5.  **¡Listo!** Tu portafolio web ya se encuentra publicado y accesible públicamente en:
    🔗 **[https://mfca-fer.github.io/CV-MiltonFernandoChitacapaAucapina/](https://mfca-fer.github.io/CV-MiltonFernandoChitacapaAucapina/)**

---

## 🛠️ Modificaciones Futuras

Si en el futuro deseas actualizar algún texto, añadir una habilidad o cambiar una experiencia:
1.  Abre el archivo [index.html](file:///d:/Proyectos/Hoja_VIda/index.html) en tu editor de código (como VS Code).
2.  Modifica el texto correspondiente dentro de las etiquetas HTML adecuadas (hemos dejado comentarios descriptivos para que te ubiques fácilmente, ej. `<!-- Habilidades Section -->` o `<!-- Experiencia Section -->`).
3.  Si deseas cambiar los colores, busca la sección `:root` en el bloque `<style>` al inicio del documento y actualiza los valores HEX de las variables de color.
