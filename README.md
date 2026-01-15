# scanner-ia
# 📱 Scanner IA - Digitalizador de Cuadernos

Una aplicación web progresiva (PWA) que usa Inteligencia Artificial de Google Gemini para digitalizar tus apuntes, cuadernos y documentos en formato Markdown.

## ✨ Características

- 📸 **Captura desde cámara o galería** - Escanea páginas directamente desde tu móvil
- 🤖 **Análisis con IA** - Extrae texto y convierte diagramas a código Mermaid
- 📓 **Organización en cuadernos** - Crea y gestiona múltiples cuadernos
- 💾 **Almacenamiento local** - Todos tus datos se guardan en tu dispositivo
- 🎨 **Diseño iOS-style** - Interfaz moderna y familiar
- 📤 **Compartir fácilmente** - Exporta tu contenido digitalizado

## 🚀 Instalación en GitHub Pages

### Paso 1: Crear repositorio

1. Ve a [github.com](https://github.com) e inicia sesión
1. Click en el botón verde “New” para crear un nuevo repositorio
1. Nombre sugerido: `scanner-ia`
1. Marca como **Public** (público)
1. Click en “Create repository”

### Paso 2: Subir archivos

Sube estos archivos a tu repositorio:

- `index.html` - La aplicación principal
- `README.md` - Este archivo

Puedes hacerlo de dos formas:

**Opción A: Desde la web**

1. Click en “uploading an existing file”
1. Arrastra los archivos o usa “choose your files”
1. Click en “Commit changes”

**Opción B: Con Git (si lo tienes instalado)**

```bash
git clone https://github.com/TU-USUARIO/scanner-ia.git
cd scanner-ia
# Copia los archivos aquí
git add .
git commit -m "Initial commit"
git push
```

### Paso 3: Activar GitHub Pages

1. Ve a **Settings** (Configuración) del repositorio
1. En el menú lateral, click en **Pages**
1. En “Source”, selecciona **main** branch
1. Click en **Save**
1. Espera 1-2 minutos

¡Listo! Tu app estará disponible en:

```
https://TU-USUARIO.github.io/scanner-ia/
```

## 🔑 Configuración de API Key

Para usar la IA de Gemini necesitas una API Key:

1. Ve a [Google AI Studio](https://makersuite.google.com/app/apikey)
1. Inicia sesión con tu cuenta de Google
1. Click en “Create API Key”
1. Copia la clave (formato: `AIzaSy...`)
1. Pégala en la app cuando te la pida

**La API Key es GRATIS** con límites generosos:

- 15 peticiones por minuto
- 1,500 peticiones por día
- Suficiente para uso personal

## 📱 Instalar en iPhone

1. Abre la URL en **Safari**
1. Toca el botón de compartir 📤 (abajo en el centro)
1. Scroll y selecciona **“Añadir a pantalla de inicio”**
1. Dale un nombre como “Scanner IA”
1. ¡Listo! Aparecerá como una app nativa

## 🔒 Privacidad y Seguridad

- ✅ Todos los datos se almacenan **localmente** en tu dispositivo
- ✅ Las imágenes se procesan directamente con la API de Google
- ✅ No hay servidor intermedio
- ✅ Tu API Key se guarda solo en tu navegador
- ⚠️ **Importante:** No compartas tu API Key con nadie

## 🛠️ Tecnologías utilizadas

- **HTML5** - Estructura
- **Tailwind CSS** - Estilos
- **JavaScript Vanilla** - Lógica
- **Google Gemini API** - Inteligencia Artificial
- **Mermaid.js** - Diagramas
- **Marked.js** - Renderizado Markdown

## 📝 Uso

1. **Crear un cuaderno** - Toca el botón “+” en la pantalla principal
1. **Abrir cuaderno** - Toca cualquier cuaderno para abrirlo
1. **Escanear página** - Usa los botones de “Cámara” o “Galería”
1. **Ver resultados** - La IA procesará y mostrará el texto extraído
1. **Compartir** - Toca “Compartir” en cualquier página

## 🐛 Solución de problemas

**La IA no funciona:**

- Verifica que tu API Key sea válida
- Revisa que tengas conexión a internet
- Comprueba los límites de uso en Google AI Studio

**Las imágenes no se cargan:**

- Asegúrate de dar permisos de cámara/galería en tu navegador
- En iOS, usa Safari (no Chrome)

**La app no se instala:**

- Usa Safari en iOS (no otros navegadores)
- Verifica que estés usando HTTPS

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 🤝 Contribuciones

¿Tienes ideas para mejorar la app? ¡Las contribuciones son bienvenidas!

1. Haz un Fork del proyecto
1. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
1. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
1. Push a la rama (`git push origin feature/AmazingFeature`)
1. Abre un Pull Request

## 📧 Contacto

¿Preguntas o sugerencias? Abre un Issue en GitHub.

-----

**Hecho con ❤️ usando Claude AI**
