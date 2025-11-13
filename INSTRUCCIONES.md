# 🚀 Instrucciones Rápidas de Uso

## ✅ Checklist Antes de Desplegar

### 1. Agregar Imágenes (OBLIGATORIO)
Coloca estas imágenes en `assets/images/`:
- [ ] `profile.jpg` - Tu foto de perfil
- [ ] `about.jpg` - Imagen sobre ti
- [ ] `tech.jpg` - Imagen de tecnología
- [ ] `project1.jpg` - Proyecto web
- [ ] `project2.jpg` - Proyecto videojuegos
- [ ] `project3.jpg` - Proyecto IoT/Robótica

### 2. Agregar Video (OBLIGATORIO)
Coloca este video en `assets/videos/`:
- [ ] `presentation.mp4` - Video corto de presentación (1-3 min)

### 3. Personalizar Enlaces (RECOMENDADO)
Edita `index.html` línea 216-222 y actualiza:
- [ ] Tu perfil de LinkedIn
- [ ] Tu perfil de GitHub
- [ ] Tu email de contacto

### 4. Verificar Contenido
- [x] ✅ Texto completo incluido
- [x] ✅ 3+ imágenes configuradas (necesitas agregarlas)
- [x] ✅ 1 video configurado (necesitas agregarlo)
- [x] ✅ 3+ enlaces externos (LinkedIn, GitHub, Email)

## 📤 Desplegar en Render (3 Pasos)

### Paso 1: Subir a GitHub
```bash
git init
git add .
git commit -m "Portafolio inicial"
git remote add origin TU_REPOSITORIO
git push -u origin main
```

### Paso 2: Conectar con Render
1. Ve a https://render.com
2. Crea cuenta o inicia sesión
3. Click en "New +" → "Static Site"
4. Conecta tu repositorio de GitHub

### Paso 3: Configurar
- **Name:** portfolio-diego-gomez
- **Build Command:** (dejar vacío)
- **Publish Directory:** `.` (punto)
- Click "Create Static Site"

¡Listo! Tu sitio estará en línea en 2-3 minutos.

## 🎨 Personalización Rápida

### Cambiar Colores
Edita `styles.css` líneas 6-13:
```css
--primary-color: #2563eb;    /* Cambia este color */
```

### Cambiar Fuente
Edita `index.html` línea 11 para cambiar la fuente de Google Fonts.

## 📝 Notas Importantes

- Las imágenes deben tener formato JPG, PNG o WebP
- El video debe ser MP4 (H.264) para mejor compatibilidad
- El sitio es 100% responsive y funciona en todos los dispositivos
- No necesitas servidor backend, es un sitio estático

## 🆘 Problemas Comunes

**Las imágenes no se ven:**
- Verifica que los archivos estén en `assets/images/`
- Verifica que los nombres coincidan exactamente (case-sensitive)

**El video no se reproduce:**
- Verifica que el formato sea MP4
- Verifica que el archivo esté en `assets/videos/`

**Error al desplegar en Render:**
- Verifica que `render.yaml` esté en la raíz del proyecto
- Verifica que `index.html` esté en la raíz del proyecto

---

¿Necesitas ayuda? Revisa el `README.md` completo para más detalles.

