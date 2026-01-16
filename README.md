# DeutschFlow - PWA para Aprender Alemán 🚀

![Icon](https://icon-192.png)

DeutschFlow es una **Progressive Web App (PWA)** interactiva diseñada para dominar la gramática alemana a través de ejercicios dinámicos y un sistema gamificado.

---

## 🌟 Características Principales

### 🎯 Aprendizaje Interactivo
- **Ruleta de Verbos:** Selección visual interactiva de verbos alemanes.  
- **Sistema de Satzklammer:** Ejercicios prácticos de estructura de oraciones.  
- **Tablas de Conjugación:** Visualización completa de todos los tiempos verbales.  
- **Sistema XP Gamificado:** Gana puntos y mantén rachas de aprendizaje.

### 📱 PWA Completa
- ✅ Instalación en dispositivos móviles y desktop.  
- ✅ Funciona offline gracias al Service Worker.  
- ✅ Actualizaciones automáticas.  
- ✅ Notificaciones push configurables.  
- ✅ Pantalla splash y tema de app.

### 🎨 Interfaz Moderna
- Diseño responsive (móvil, tablet y desktop).  
- Modo claro/oscuro automático.  
- Animaciones fluidas y efectos visuales.  
- Partículas interactivas en el fondo.

---

## 📁 Estructura del Proyecto
```
deutschflow-pwa/
├── index.html             # Aplicación principal
├── manifest.json          # Configuración PWA
├── service-worker.js      # Cache y funcionalidad offline
├── index.json             # Índice de módulos de aprendizaje
├── data/                  # Módulos de contenido
│   ├── emails.json
│   ├── modales.json
│   ├── reflexivos.json
│   └── ...
├── icons/                 # Iconos PWA
│   ├── icon-64.png
│   ├── icon-128.png
│   ├── icon-192.png
│   └── icon-512.png
└── README.md              # Este archivo
```

---

## 🚀 Cómo Empezar

### Instalación Local
```bash
# Clonar repositorio
git clone https://github.com/tuusuario/deutschflow-pwa.git

# Navegar al directorio
cd deutschflow-pwa

# Servir localmente con Python
python -m http.server 8000

# O con Node.js
npx serve .
```

---

## 📚 Módulos Disponibles

| Módulo        | Nivel | Contenido                        | Verbos |
|---------------|-------|---------------------------------|--------|
| Módulo 1      | A1    | Verbos básicos y fundamentos     | 10     |
| Módulo 2      | A2    | Estructuras intermedias          | 8      |
| Módulo 3      | B1    | Construcciones avanzadas         | 10     |
| Modalverben   | A1    | Verbos modales esenciales        | 6      |
| Reflexivos    | A2    | Verbos reflexivos                | 10     |
| Separables    | A2    | Verbos separables                | 8      |
| Subordinadas  | B1    | Oraciones complejas              | 12     |
| Präpositionen | A2    | Preposiciones con casos          | 15     |
| Imperativo    | A2    | Formas de imperativo             | 8      |
| Emails        | A2    | Comunicación escrita             | 12     |
| Orientierung  | A1    | Vocabulario ciudad               | 8      |

**Total:** 118 verbos y estructuras para dominar.

---

## 🔧 Tecnologías Utilizadas
- HTML5 + CSS3 (Flexbox/Grid)  
- JavaScript ES6+ (puro, sin frameworks)  
- Service Worker API para funcionalidad offline  
- Web App Manifest para instalación  
- LocalStorage para persistencia de datos  
- Fetch API para carga dinámica de contenido  

---

## 📱 Instalación como App

**Android / Chrome:**  
1. Abre la app en Chrome  
2. Toca el menú (3 puntos)  
3. Selecciona "Instalar app" o "Añadir a pantalla de inicio"

**iOS / Safari:**  
1. Abre la app en Safari  
2. Toca el icono de compartir  
3. Selecciona "Añadir a pantalla de inicio"

**Desktop (Chrome / Edge):**  
1. Abre la app en el navegador  
2. Haz clic en el icono de instalación en la barra de direcciones  
3. Selecciona "Instalar DeutschFlow"

---

## 🛠️ Desarrollo

### Personalizar Contenido
Agregar un nuevo módulo en `data/`:
```json
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
```

### Modificar Estilos
```css
:root {
  --primary: #tu-color;
  --secondary: #tu-color;
  --success: #tu-color;
}
```

### Actualizar Iconos
Reemplaza los archivos en `icons/`:
- `icon-64.png`  
- `icon-128.png`  
- `icon-192.png` ← recomendado para PWA  
- `icon-512.png`

---

## 📈 Roadmap de Desarrollo

### Próximas Funcionalidades
- Sistema de usuarios con perfil  
- Modo multijugador para desafíos  
- Sincronización en la nube  
- Ejercicios de pronunciación (Web Speech API)  
- Exportación de progreso en PDF  
- Modo exámenes con temporizador  
- API pública para desarrolladores  

### Mejoras Técnicas
- WebRTC para tutorías en vivo  
- IndexedDB para almacenamiento avanzado  
- WebAssembly para procesamiento rápido  
- GraphQL para consultas eficientes  

---

## 🤝 Contribuir
1. Fork el repositorio  
2. Crea una rama: `git checkout -b feature/nueva-funcionalidad`  
3. Commit tus cambios: `git commit -am 'Añadir funcionalidad'`  
4. Push a la rama: `git push origin feature/nueva-funcionalidad`  
5. Abre un Pull Request  

**Directrices:**  
- Sigue las convenciones de código existentes  
- Añade tests para nuevas funcionalidades  
- Actualiza la documentación  
- Usa commits semánticos  

---

## 🐛 Reportar Problemas
Usa el sistema de issues para:  
- Reportar bugs  
- Sugerir mejoras  
- Hacer preguntas  
- Solicitar ayuda  

---

## 📄 Licencia
Este proyecto está bajo la licencia **MIT**. Ver `LICENSE` para más detalles.

---

## 🙏 Agradecimientos
- Diseño inspirado en las mejores apps educativas  
- Iconos creados específicamente para la app  
- Comunidad de estudiantes de alemán por su feedback  
- Contribuidores que mejoran esta app cada día  

<div align="center">
🌍 Aprende Alemán  
![PWA Ready](https://img.shields.io/badge/PWA-Ready-brightgreen?style=for-the-badge&logo=pwa)  
![Offline](https://img.shields.io/badge/100%25-Offline-blue?style=for-the-badge)  
![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9D%A4%EF%B8%8F-red?style=for-the-badge)  
</div>

---

⭐ **¡Dale una Estrella!**  
Si este proyecto te ha ayudado en tu aprendizaje del alemán, considera darle una estrella en GitHub. Significa mucho.


