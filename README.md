# Cattleyas-rup-culas-con-Pollinations
Cattleyas rupículas creadas con Pollinations vistas en un slider temporizado
# 🌺 Grupo Sophronitis · Cattleyas Rupícolas

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

&gt; Presentación interactiva de especies botánicas del grupo *Sophronitis* (ahora clasificadas como *Cattleya*), orquídeas rupícolas nativas de Brasil.

![Vista previa](preview.png)

## 📋 Descripción

Aplicación web tipo "presentador" (slideshow) que muestra información detallada sobre especies del **Grupo Sophronitis**, un conjunto de orquídeas miniatura brasileñas caracterizadas por sus flores de colores rojo-naranja intenso y su hábito de crecimiento en rocas (*rupícolas*).

Las especies presentadas incluyen:
- **Cattleya cernua** (Lindl.) Van den Berg 2008 — *Sophronitis cernua* [^5^]
- **Cattleya brevipedunculata** (Cogn.) Van den Berg 2008 — *Sophronitis brevipedunculata* [^1^]

&gt; 🔬 **Nota taxonómica**: El género *Sophronitis* fue sinonimizado con *Cattleya* en 2008 por Cássio van den Berg para mantener la estabilidad nomenclatural de los híbridos artificiales [^6^].

## ✨ Características

### 🎨 Diseño Visual
- **Estética cinematográfica** con transiciones suaves entre diapositivas
- **Paleta de colores** inspirada en las flores: rojo terracota, dorado antiguo y crema
- **Tipografía elegante**: Cinzel (serif decorativa) + EB Garamond (serif clásica)
- **Efectos visuales**: 
  - Zoom sutil en imágenes (Ken Burns effect)
  - Vignette texturizada tipo "roca"
  - Gradientes oscuros para legibilidad del texto

### 🖼️ Funcionalidades
| Característica | Descripción |
|----------------|-------------|
| **Navegación** | Flechas de teclado (← →), botones táctiles, dots indicadores |
| **Autoplay** | Transición automática cada 6 segundos con barra de progreso |
| **Pausa** | Botón de pausa/play en la barra superior |
| **Navegación por especies** | Pills laterales para saltar entre especies |
| **Imágenes base64** | Contenido embebido sin dependencias externas |
| **Responsive** | Diseño adaptativo para diferentes pantallas |

### 📊 Datos Botánicos Incluidos
Para cada especie se muestra:
- Nombre científico completo con autor y año
- Basónimo (nombre original en *Sophronitis*)
- Descripción morfológica detallada
- Distribución geográfica (estados brasileños)
- Hábitat (altitud, sustrato)
- Período de floración
- Características distintivas

## 🚀 Uso

### Instalación local
```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/grupo-sophronitis.git

# Entrar al directorio
cd grupo-sophronitis

# Abrir en navegador (o usar servidor local)
open index.html
# o
python -m http.server 8000
