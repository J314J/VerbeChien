<div align="center">

# 🥖 VerbeChien 🐶

**Entraîneur de conjugaison française**

[![Deployed](https://img.shields.io/badge/GitHub%20Pages-deployed-brightgreen?style=flat-square&logo=github)](https://j314j.github.io/VerbeChien/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://j314j.github.io/VerbeChien/)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://j314j.github.io/VerbeChien/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://j314j.github.io/VerbeChien/)
[![License](https://img.shields.io/badge/license-MIT-gold?style=flat-square)](LICENSE)
[![Verbes](https://img.shields.io/badge/verbes-246-c9a84c?style=flat-square)](https://j314j.github.io/VerbeChien/)
[![Temps](https://img.shields.io/badge/temps%20grammaticaux-24-4fb8c0?style=flat-square)](https://j314j.github.io/VerbeChien/)

*Entrenador de verbos franceses con audio · Sin frameworks · Sin servidores · Sin costo*

**[→ Pruébalo en vivo](https://j314j.github.io/VerbeChien/)**

</div>

---

## ¿Qué es?

Una herramienta de estudio para aprender la conjugación francesa de forma rápida e interactiva, inspirada en [Verbugata](https://verbugata.com/). Escribe las formas conjugadas, verifica tus respuestas y escucha la pronunciación — todo en el navegador, sin instalar nada.

Construido con HTML + CSS + JavaScript puro. Un solo archivo. Cero dependencias.

---

## Características

- 📚 **246 verbos** de los más usados en francés, con traducción en español
- ⏱ **24 tiempos y formas** gramaticales completos

| Modo | Tiempos |
|---|---|
| Indicatif | Présent · Imparfait · Passé composé · Plus-que-parfait · Passé simple ✦ · Passé antérieur ✦ · Futur simple · Futur antérieur |
| Subjonctif | Présent · Passé · Imparfait ✦ · Plus-que-parfait ✦ |
| Conditionnel | Présent · Passé 1ère forme · Passé 2ème forme ✦ |
| Impératif | Présent · Passé |
| Formes non personnelles | Infinitif présent · Infinitif passé · Participe présent · Participe passé · Gérondif |

> ✦ Tiempos literarios — aparecen en literatura clásica, desactivados por defecto

- 🎯 **Filtro por grupos gramaticales**
  - Groupe 1 — verbos en **-ER** regulares (187 verbos)
  - Groupe 2 — verbos en **-IR** regulares con *-issons* (15 verbos)
  - Groupe 3 — verbos irregulares (6 verbos)
  - ⭐ Irréguliers importants — être, avoir, faire, aller, venir, voir, pouvoir… (38 verbos)

- 🔊 **Audio de pronunciación** — Web Speech API, nativo en el navegador, completamente gratis
- ✅ **Verificación inteligente** — acepta respuestas sin tildes (`ecris` = `écris` ✓)
- 📊 **Puntuación, racha y total** en tiempo real
- 🌙 Diseño oscuro, tipografía elegante, cómodo para sesiones largas
- 📱 Responsive — funciona en móvil y escritorio

---

## Cómo usar

```
1. Selecciona los grupos de verbos que quieres practicar
2. Activa los tiempos gramaticales (o usa los presets)
3. Escribe las conjugaciones en los campos
4. Enter / Vérifier → para verificar tus respuestas
5. 🔊 → para escuchar la pronunciación
6. Suivant → siguiente verbo
```

---

## Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura |
| CSS3 | Diseño y animaciones |
| JavaScript Vanilla | Lógica completa de la app |
| Web Speech API | Pronunciación de audio en francés |
| Google Fonts | Playfair Display · IBM Plex Mono |
| GitHub Pages | Hosting gratuito |

> Sin frameworks. Sin dependencias. Sin backend. Un solo archivo `index.html`.

---

## Estructura del proyecto

```
VerbeChien/
├── index.html    # App completa — HTML + CSS + JS embebidos
└── README.md
```

---

## Desarrollo local

```bash
git clone https://github.com/j314j/VerbeChien.git
cd VerbeChien
# Abre index.html en Chrome o Edge
```

> **Nota:** la Web Speech API necesita un servidor para funcionar correctamente. En VS Code instala la extensión **Live Server** y abre con ella para que el audio funcione en local.

---

## Compatibilidad de audio

| Navegador | Soporte |
|---|---|
| Chrome | ✅ Excelente |
| Edge | ✅ Excelente |
| Safari | ✅ Bueno |
| Firefox | ⚠ Limitado |

Para mejor pronunciación instala el **paquete de idioma francés** en tu sistema operativo.

---

## Por qué este proyecto

Estoy aprendiendo francés y quería una herramienta gratuita con todos los tiempos gramaticales y pronunciación. Lo construí desde cero — es mi primer deployment en GitHub Pages.

---

## Licencia

MIT — úsalo, modifícalo, compártelo libremente.

---

<div align="center">
<em>Fait avec 🥖 et beaucoup de café</em>
</div>
