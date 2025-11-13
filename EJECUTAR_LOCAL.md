# 🖥️ Cómo Ejecutar el Sitio Localmente

## Opción 1: Abrir Directamente (Más Simple) ⚡

1. Navega a la carpeta del proyecto
2. Haz doble clic en `index.html`
3. Se abrirá en tu navegador predeterminado

**Nota:** Algunas funciones pueden no funcionar correctamente (como el scroll suave) si abres el archivo directamente.

---

## Opción 2: Servidor Local con Python 🐍

### Si tienes Python instalado:

1. Abre PowerShell o Terminal en la carpeta del proyecto
2. Ejecuta uno de estos comandos:

**Python 3:**
```powershell
python -m http.server 8000
```

**Python 2 (si no tienes Python 3):**
```powershell
python -m SimpleHTTPServer 8000
```

3. Abre tu navegador y ve a: `http://localhost:8000`

4. Para detener el servidor, presiona `Ctrl + C`

---

## Opción 3: Servidor Local con Node.js 📦

### Si tienes Node.js instalado:

1. Abre PowerShell en la carpeta del proyecto
2. Instala las dependencias (solo la primera vez):
```powershell
npm install
```

3. Inicia el servidor:
```powershell
npm start
```

4. Abre tu navegador y ve a la URL que aparece (generalmente `http://localhost:3000`)

5. Para detener el servidor, presiona `Ctrl + C`

---

## Opción 4: Extensión de VS Code 🔌

Si usas Visual Studio Code:

1. Instala la extensión "Live Server"
2. Haz clic derecho en `index.html`
3. Selecciona "Open with Live Server"
4. El sitio se abrirá automáticamente en tu navegador

---

## Opción 5: Servidor Simple con PowerShell 💻

Ejecuta este comando en PowerShell:

```powershell
Start-Process "http://localhost:8000"; python -m http.server 8000
```

---

## ✅ Verificar que Funciona

Una vez que el sitio esté abierto, deberías ver:
- ✅ Header con navegación
- ✅ Sección Hero con tu nombre
- ✅ Todas las secciones (Sobre Mí, Habilidades, etc.)
- ✅ Formulario de contacto

**Nota:** Las imágenes y el video aparecerán como rotas hasta que agregues los archivos reales.

---

## 🐛 Solución de Problemas

**Error: "python no se reconoce"**
- Instala Python desde python.org o usa otra opción

**Error: "npm no se reconoce"**
- Instala Node.js desde nodejs.org o usa otra opción

**Las imágenes no se ven:**
- Es normal si aún no has agregado las imágenes
- Agrega las imágenes en `assets/images/` según las instrucciones

**El video no se reproduce:**
- Es normal si aún no has agregado el video
- Agrega el video en `assets/videos/` según las instrucciones

---

## 💡 Recomendación

Para desarrollo y pruebas, usa la **Opción 2 (Python)** o **Opción 3 (Node.js)** ya que simulan mejor un servidor web real.

