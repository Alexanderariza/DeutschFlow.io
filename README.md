# DeutschFlow.io
Pedagogía Adaptativa A2–B1 

# DeutschFlow – Pedagogía Adaptativa A2–B1 (HTML · CSS · JS)

Aplicación web ligera para el aprendizaje de alemán (nivel A2–B1), diseñada con una **arquitectura estable basada en JSON** y una **capa pedagógica adaptativa** que mejora la experiencia de aprendizaje sin comprometer la lógica base.

---

## 🎯 Objetivo del proyecto

Proveer una app educativa:

- Offline-first  
- Extensible mediante JSON  
- Pedagógicamente clara  
- Técnicamente robusta y sin frameworks  

Ideal para aprendizaje autónomo, prototipos educativos y experimentación didáctica.

---

## 🧠 Enfoque pedagógico

El sistema está construido en **capas**, siguiendo principios de diseño cognitivo.

### Nivel 1 – Núcleo estable
- Lógica JavaScript original intacta  
- Flujo de teoría, ejercicios y progreso  
- Carga dinámica de temas mediante archivos JSON  

### Nivel 2 – Pedagogía visual
- Jerarquía clara: teoría → ejemplo → ejercicio → feedback  
- Reducción de carga cognitiva  
- Espaciado, contraste y ritmo optimizados para A2–B1  

### Nivel 3 – Pedagogía adaptativa (actual)
- Modo claro / oscuro  
- Refuerzo visual del ejercicio activo (foco cognitivo)  
- Adaptación de atención sin modificar datos ni estructura JSON  

> ⚠️ **Importante:**  
> No se modifica ni se exige ningún campo adicional en los archivos JSON.

---

## 📁 Estructura del proyecto

```text
/
├── APP_9.html                  # Versión original (baseline estable)
├── APP_9_PEDAGOGICO.html       # Mejora visual pedagógica
├── APP_9_ADAPTIVE.html         # Pedagogía adaptativa (recomendada)
├── *.json                      # Módulos / temas (teoría + ejercicios)
└── README.md

