DeutschFlow - PWA para Aprender Alemán 🚀
https://icon-192.png

Una Progressive Web App (PWA) interactiva para dominar la gramática alemana con ejercicios dinámicos y sistema gamificado.

🌟 Características Principales
🎯 Aprendizaje Interactivo
Ruleta de Verbos: Selección visual interactiva de verbos alemanes

Sistema de Satzklammer: Ejercicios prácticos de estructura de oraciones

Tablas de Conjugación: Visualización completa de todos los tiempos verbales

Sistema XP Gamificado: Gana puntos y mantén rachas de aprendizaje

📱 PWA Completa
✅ Instalable en dispositivos móviles y desktop

✅ Funciona offline gracias al Service Worker

✅ Actualizaciones automáticas

✅ Notificaciones push (configurable)

✅ Pantalla splash y tema de app

🎨 Interfaz Moderna
Diseño responsive que funciona en móvil, tablet y desktop

Modo claro/oscuro automático

Animaciones fluidas y efectos visuales

Partículas interactivas en fondo

📁 Estructura del Proyecto
deutschflow-pwa/
├── index.html              # Aplicación principal
├── manifest.json          # Configuración PWA
├── service-worker.js      # Cache y funcionalidad offline
├── index.json            # Índice de módulos de aprendizaje
├── data/                 # Módulos de contenido
│   ├── emails.json
│   ├── modales.json
│   ├── reflexivos.json
│   └── ...
├── icons/                # Iconos PWA
│   ├── icon-64.png
│   ├── icon-128.png
│   ├── icon-192.png
│   └── icon-512.png
└── README.md             # Este archivo

🚀 Cómo Empezar
Instalación Local
# Clonar repositorio
git clone https://github.com/tuusuario/deutschflow-pwa.git

# Navegar al directorio
cd deutschflow-pwa

# Servir localmente (con Python)
python -m http.server 8000

# O con Node.js
npx serve .
📚 Módulos Disponibles
La aplicación incluye 11 módulos organizados por nivel:

Módulo	Nivel	Contenido	Verbos
Módulo 1	A1	Verbos básicos y fundamentos	10
Módulo 2	A2	Estructuras intermedias	8
Módulo 3	B1	Construcciones avanzadas	10
Modalverben	A1	Verbos modales esenciales	6
Reflexivos	A2	Verbos reflexivos	10
Separables	A2	Verbos separables	8
Subordinadas	B1	Oraciones complejas	12
Präpositionen	A2	Preposiciones con casos	15
Imperativo	A2	Formas de imperativo	8
Emails	A2	Comunicación escrita	12
Orientierung	A1	Vocabulario ciudad	8
Total: 118 verbos y estructuras para dominar

🔧 Tecnologías Utilizadas
HTML5 + CSS3 con Flexbox/Grid

JavaScript ES6+ (puro, sin frameworks)

Service Worker API para funcionalidad offline

Web App Manifest para instalación

LocalStorage para persistencia de datos

Fetch API para carga dinámica de contenido

📱 Instalación como App
En Android/Chrome:
Abre la app en Chrome

Toca el menú (3 puntos)

Selecciona "Instalar app" o "Añadir a pantalla de inicio"

En iOS/Safari:
Abre la app en Safari

Toca el icono de compartir

Desplaza y selecciona "Añadir a pantalla de inicio"

En Desktop:
Abre en Chrome/Edge

Busca el icono de instalación en la barra de direcciones

Haz clic en "Instalar DeutschFlow"

🛠️ Desarrollo
Personalizar Contenido
json
// Añadir nuevo módulo a data/
{
  "id": "nuevo_modulo",
  "title": "Nuevo Módulo",
  "verb": "verbo_infinitiv",
  "tenses": [
    {
      "tense": "Präsens",
      "translation": "Traducción",
      "words": ["palabra1", "palabra2"],
      "correctSentence": ["oración", "completa"]
    }
  ]
}
Modificar Estilos
css
/* Cambiar colores principales */
:root {
  --primary: #tu-color;
  --secondary: #tu-color;
  --success: #tu-color;
}
Actualizar Iconos
Reemplazar los archivos en la raíz:

icon-64.png (64x64)

icon-128.png (128x128)

icon-192.png (192x192) ← Recomendado para PWA

icon-512.png (512x512)

📈 Roadmap de Desarrollo
Próximas Funcionalidades
Sistema de usuarios con perfil

Modo multijugador para desafíos

Sincronización en la nube

Ejercicios de pronunciación (Web Speech API)

Exportación de progreso en PDF

Modo exámenes con temporizador

API pública para desarrolladores

Mejoras Técnicas
WebRTC para tutorías en vivo

IndexedDB para almacenamiento avanzado

WebAssembly para procesamiento rápido

GraphQL para consultas eficientes

🤝 Contribuir
Fork el repositorio

Crea una rama (git checkout -b feature/nueva-funcionalidad)

Commit tus cambios (git commit -am 'Añadir funcionalidad')

Push a la rama (git push origin feature/nueva-funcionalidad)

Abre un Pull Request

Directrices de Contribución
Sigue las convenciones de código existentes

Añade tests para nuevas funcionalidades

Actualiza la documentación cuando sea necesario

Usa commits semánticos

🐛 Reportar Problemas
Usa el sistema de issues para:

🐛 Reportar bugs

💡 Sugerir mejoras

❓ Hacer preguntas

🔧 Solicitar ayuda

📄 Licencia
Este proyecto está bajo la licencia MIT - ver el archivo LICENSE para más detalles.

🙏 Agradecimientos
Diseño inspirado en las mejores apps educativas

Iconos creados específicamente para la app

Comunidad de estudiantes de alemán por sus feedback

Contribuidores que hacen mejor esta app cada día
<div align="center">
🌍 Aprende Alemán 
https://img.shields.io/badge/PWA-Ready-brightgreen?style=for-the-badge&logo=pwa
https://img.shields.io/badge/100%2525-Offline-blue?style=for-the-badge
https://img.shields.io/badge/Open%2520Source-%E2%9D%A4%EF%B8%8F-red?style=for-the-badge

</div>
⭐ ¡Dale una Estrella!
Si este proyecto te ha ayudado en tu aprendizaje del alemán, considera darle una estrella en GitHub. ¡Significa mucho! ⭐


