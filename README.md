<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=4ec9b0&center=true&vCenter=true&width=640&lines=Portafolio+IDE+en+el+navegador;React+19+%C2%B7+TypeScript+%C2%B7+Vite;Tema+Monokai+%2B+ondas+PSP+%2B+terminal" alt="Typing SVG" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a18,100:1e3a5f&height=120&section=header&text=dev-joyrs&fontSize=32&fontColor=4ec9b0&animation=twinkling&fontAlignY=32&desc=Cristhian+Joy+Reis+Serr%C3%ADn+%C2%B7+Portafolio&descAlignY=55&descSize=12&fontColorDesc=c9d1d9" width="100%" alt="header" />

<br/>

[![Stack](https://img.shields.io/badge/⚡-Vite%20%2B%20React%2019-646CFF?style=for-the-badge&logo=vite)](https://github.com/JoyRS/dev-joyrs)
[![TS](https://img.shields.io/badge/IDE--style-1a1a18?style=for-the-badge&logo=typescript&logoColor=4ec9b0)](https://github.com/JoyRS/dev-joyrs)
[![Themes](https://img.shields.io/badge/🎨-Monokai%20%7C%20Mariana%20%7C%20Dracula%20%7C%20Nord-58A6FF?style=for-the-badge)](https://github.com/JoyRS/dev-joyrs)

</div>

---

### 🧩 Qué es este repo

**Portafolio interactivo** con estética de **editor / IDE** (barra de título, pestañas, sidebar de archivos, panel inferior tipo terminal) y **fondo con ondas al estilo PSP**. Los contenidos de CV, stack y proyectos se alimentan de archivos y datos del propio frontend; en **Proyectos** se integra la **API pública de GitHub** (con manejo de límite de tasa y fallback).

- **🖥️ UI**: ventana estilo IDE, `hash` para “rutas” internas, temas conmutables (**Monokai** por defecto, **Mariana**, **Dracula**, **Nord**).  
- **🌊 Ambiente**: canvas de ondas + paleta alineada con Monokai (`#1a1a18` · acento `#4ec9b0` · resaltado tipo código).  
- **⚙️ Build**: [Vite](https://vitejs.dev/) 5, [React](https://react.dev/) 19, [TypeScript](https://www.typescriptlang.org/), [react-icons](https://react-icons.github.io/react-icons/), ESLint.  
- **🔍 SEO**: `index.html` con metas, `theme-color` oscuro, JSON-LD `Person` y reemplazos de sitio vía `VITE_*` (ver `.env.example`).

<details>
<summary><b>🗂️ Estructura (resumen)</b></summary>

| Ruta (idea) | Rol |
|:---|:---|
| `src/components/ide/` · `editor/` | Ventana IDE, cuerpo del editor, vistas (perfil, experiencia, skills, proyectos, etc.) |
| `src/components/ambient/` | Fondo ondas (PSP-style) |
| `src/components/terminal/` | Panel tipo terminal simulada |
| `src/config/cvFiles.ts` · `src/content/` | “Árbol” de archivos y contenido |
| `src/hooks/` | Tema IDE, hash routing, repos de GitHub, etc. |
| `src/lib/github/` | Llamada y tipos a la API de repositorios |
| `src/styles/ide-themes.css` | Tokens por tema (Monokai, Mariana, Dracula, Nord) |

</details>

---

### 🛠️ Stack (este front)

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,react,vite&perline=6" alt="Frontend stack" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=222" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img href="#" src="https://img.shields.io/badge/Vite-5-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Hash%20routing-%23272822?style=flat-square&logo=javascript&logoColor=f7df1e" alt="Hash routing" />
  <img src="https://img.shields.io/badge/GitHub%20API-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub API" />
</p>

*Tu perfil backend (Node, NestJS, NATS, AWS, etc.) sigue siendo tuyo; este repositorio es el **frente** del portafolio.*

---

### 🚀 Cómo correrlo

```bash
git clone https://github.com/JoyRS/dev-joyrs.git
cd dev-joyrs
cp .env.example .env
npm install
npm run dev
