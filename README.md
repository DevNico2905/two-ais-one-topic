# 🤖 IA Generativa — Infografía Comparativa
### *Un mismo tema. Dos inteligencias artificiales. Dos perspectivas.*

> Trabajo académico realizado **100% con herramientas de inteligencia artificial generativa**,
> como exploración práctica de los conceptos que el propio trabajo explica.

---

## 👤 Autor

**Nicolás Bernal Rodriguez**

---

## 🎯 ¿De qué trata este proyecto?

Este proyecto es una **infografía interactiva sobre Inteligencia Artificial Generativa**, construida con un giro particular: fue elaborada utilizando dos herramientas de IA distintas para el mismo encargo, permitiendo comparar en tiempo real cómo cada una interpreta, diseña y presenta la misma información.

El resultado es una **landing page** que presenta las dos versiones lado a lado, invitando al visitante a explorar ambas y sacar sus propias conclusiones.

---

## 📋 Aspectos clave del trabajo

Los contenidos cubiertos en ambas versiones incluyen:

| # | Tema |
|---|------|
| 1 | **Conceptos clave** — LLMs, tokens, embeddings, transformers, prompt engineering, RAG |
| 2 | **Funcionamiento** — Del dato de entrenamiento a la generación, paso a paso |
| 3 | **Ejemplos prácticos** — Asistentes, código, imágenes, medicina, atención al cliente |
| 4 | **Servicios AWS** — Bedrock, SageMaker, Amazon Q, Kendra, Titan, Trainium |

---

## 🗂️ Estructura del proyecto

```
📁 /
├── index.html       ← Landing principal (punto de entrada)
├── claude.html      ← Versión 1: Infografía visual estática (Claude · Anthropic)
├── gemini.html     ← Versión 2: App interactiva con pestañas (Gemini - Google)
└── README.md        ← Este archivo
```

---

## 🆚 Las dos versiones

### Versión 01 — Claude (Anthropic)
**Archivo:** `claude.html`

Infografía visual de página única con:
- Hero con fondo de color y gráfico geométrico decorativo
- KPIs numéricos destacados (175B parámetros, 100M usuarios, etc.)
- Diagrama de flujo SVG del funcionamiento
- Línea de tiempo histórica dibujada con SVG
- Tarjetas de tipos de modelos con ejemplos
- Grid de servicios AWS con chips de color
- Paleta cromática semántica por categoría
- Tecnologías: **HTML · CSS · SVG inline**

---

### Versión 02 — Gemini (Google)
**Archivo:** `gemini.html`

Aplicación interactiva con navegación por pestañas:
- Navegación sticky entre 5 secciones
- Contenido dinámico con animación de transición
- Diseño basado en componentes estilo React
- Footer con notas técnicas y tips de AWS
- Tecnologías: **React → HTML · Tailwind CSS**

---

## 🚀 Ver en vivo

🌐 **[Ver proyecto desplegado →](#)**
*(enlace disponible tras el despliegue en Vercel)*

---

## 🛠️ Cómo correrlo localmente

No requiere instalación ni servidor. Solo descarga los archivos y abre `index.html` en tu navegador:

```bash
git clone https://github.com/DevNico2905/two-ais-one-topic.git
cd two-ais-one-topic
# Abre index.html en tu navegador
```

---

## ☁️ Despliegue en Vercel

Este proyecto es un sitio estático puro. Para desplegarlo:

1. Importa este repositorio en [vercel.com](https://vercel.com)
2. Vercel detecta `index.html` como punto de entrada automáticamente
3. Dale a **Deploy** — sin configuración adicional
4. Conecta tu dominio en **Settings → Domains**

---

## 💡 Reflexión final

> *"Le pedí a dos IAs que hicieran el mismo trabajo. Ninguna lo hizo igual.
> Una eligió la estructura visual; la otra, la interactividad.
> Ambas cubrieron el tema. Ninguna se copió de la otra.
> Eso, en sí mismo, ya dice mucho sobre la IA generativa."*
>
> — Nicolás Bernal Rodriguez

---

## 📚 Fuentes y materiales base

- Introducción a la IA Generativa — presentación interactiva
- Historia de la IA — línea de tiempo
- Amazon Web Services Iberia. (2024). *Amazon Bedrock: aplicaciones de IA generativa a escala* [Video]. YouTube.

---

<div align="center">

**Hecho 100% con IA · 2025**

*Claude (Anthropic) · Herramienta IA #2*

</div>
