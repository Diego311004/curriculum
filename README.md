# Portafolio Profesional - Diego Alonso Gómez Ramírez

Sitio web personal y profesional que muestra mis habilidades, experiencia y proyectos como Desarrollador de Software Multiplataforma.

## 🚀 Características

- ✅ Diseño moderno y responsive
- ✅ Secciones completas con toda la información profesional
- ✅ Imágenes y videos integrados
- ✅ Enlaces a redes sociales y contacto
- ✅ Formulario de contacto funcional
- ✅ Optimizado para SEO
- ✅ Compatible con Render para despliegue

## 📋 Requisitos

- Navegador web moderno
- Para desarrollo local: Node.js (opcional)

## 🛠️ Instalación Local

1. Clona o descarga este repositorio
2. Abre `index.html` en tu navegador o usa un servidor local:

```bash
# Con Python
python -m http.server 8000

# Con Node.js (si instalaste las dependencias)
npm install
npm start
```

## 📁 Estructura del Proyecto

```
Curriculum/
├── index.html          # Página principal
├── styles.css          # Estilos del sitio
├── script.js           # Funcionalidad JavaScript
├── package.json        # Configuración Node.js
├── render.yaml         # Configuración para Render
├── assets/
│   ├── images/         # Imágenes del sitio
│   │   ├── profile.jpg
│   │   ├── about.jpg
│   │   ├── tech.jpg
│   │   ├── project1.jpg
│   │   ├── project2.jpg
│   │   └── project3.jpg
│   └── videos/         # Videos del sitio
│       └── presentation.mp4
└── README.md           # Este archivo
```

## 🖼️ Agregar Imágenes

Antes de desplegar, asegúrate de agregar las siguientes imágenes en `assets/images/`:

1. **profile.jpg** - Tu foto de perfil (400x400px recomendado)
2. **about.jpg** - Imagen sobre ti (800x600px recomendado)
3. **tech.jpg** - Imagen de tecnología (1200x600px recomendado)
4. **project1.jpg** - Proyecto de desarrollo web (600x400px)
5. **project2.jpg** - Proyecto de videojuegos (600x400px)
6. **project3.jpg** - Proyecto de IoT/Robótica (600x400px)

Puedes usar imágenes de:
- [Unsplash](https://unsplash.com)
- [Pexels](https://www.pexels.com)
- [Pixabay](https://pixabay.com)

## 🎥 Agregar Video

Agrega un video corto (1-3 minutos) en `assets/videos/presentation.mp4`:
- Formato: MP4 (H.264)
- Resolución: 720p o 1080p
- Duración: 1-3 minutos

## 🔗 Personalizar Enlaces

Edita los enlaces en la sección de contacto (`index.html`):

```html
<a href="https://www.linkedin.com/in/tu-perfil" target="_blank">LinkedIn</a>
<a href="https://github.com/tu-usuario" target="_blank">GitHub</a>
<a href="mailto:tu-email@ejemplo.com">Email</a>
```

## 📤 Desplegar en Render

### Opción 1: Despliegue Automático desde GitHub

1. Sube tu proyecto a un repositorio de GitHub
2. Ve a [Render](https://render.com) y crea una cuenta
3. Haz clic en "New +" y selecciona "Static Site"
4. Conecta tu repositorio de GitHub
5. Render detectará automáticamente la configuración:
   - **Build Command:** (dejar vacío)
   - **Publish Directory:** `.` (punto)
6. Haz clic en "Create Static Site"
7. ¡Tu sitio estará en línea en unos minutos!

### Opción 2: Despliegue Manual

1. Crea una cuenta en [Render](https://render.com)
2. Haz clic en "New +" → "Static Site"
3. Conecta tu repositorio o sube los archivos manualmente
4. Configura:
   - **Name:** portfolio-diego-gomez
   - **Build Command:** (vacío)
   - **Publish Directory:** `.`
5. Haz clic en "Create Static Site"

### Configuración en Render

El archivo `render.yaml` ya está configurado. Render lo detectará automáticamente si despliegas desde GitHub.

## 🎨 Personalización

### Colores

Puedes cambiar los colores en `styles.css` modificando las variables CSS:

```css
:root {
    --primary-color: #2563eb;    /* Color principal */
    --secondary-color: #1e40af;  /* Color secundario */
    --accent-color: #3b82f6;     /* Color de acento */
}
```

### Contenido

Edita `index.html` para actualizar:
- Información personal
- Habilidades
- Experiencia
- Proyectos

## 📱 Responsive Design

El sitio está completamente optimizado para:
- 📱 Móviles
- 📱 Tablets
- 💻 Laptops
- 🖥️ Escritorio

## 🔧 Tecnologías Utilizadas

- HTML5
- CSS3 (con variables CSS y Grid/Flexbox)
- JavaScript (Vanilla JS)
- Google Fonts (Poppins)

## 📝 Licencia

Este proyecto es de uso personal.

## 👤 Autor

**Diego Alonso Gómez Ramírez**
- Técnico Superior Universitario en Desarrollo de Software Multiplataforma
- Especializado en desarrollo web, móvil y tecnologías emergentes

## 📧 Contacto

Para más información, visita el sitio web o contacta a través de los enlaces proporcionados en la sección de contacto.

---

⭐ Si te gusta este proyecto, ¡no olvides darle una estrella!

