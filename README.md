<div align="center">

<!-- Paleta alineada con tema Monokai del sitio: bg ~#1a1a18, acento #4ec9b0 -->

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3500&pause=900&color=4ec9b0&center=true&vCenter=true&width=680&lines=dev-joyrs+%7C+portafolio+estilo+IDE;React+19+%C2%B7+TypeScript+%C2%B7+Vite;Monokai+%2B+ondas+PSP+%2B+terminal" alt="Typing" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a18,100:1e2a2e&height=130&section=header&text=dev-joyrs&fontSize=34&fontColor=4ec9b0&animation=twinkling&fontAlignY=30&desc=Cristhian+Joy+Reis+Serr%C3%ADn+%C2%B7+Backend+Lead+%2F+Cloud+Engineer&descAlignY=56&descSize=12&fontColorDesc=c8c8c8" width="100%" alt="header" />

<br/>

<a href="https://github.com/JoyRS/dev-joyrs"><img src="https://img.shields.io/badge/📍-Arequipa%2C%20Perú-272822?style=for-the-badge&labelColor=1a1a18&color=2d2d2d" alt="Location" /></a>
<a href="https://github.com/JoyRS"><img src="https://img.shields.io/badge/🏠-Remote-272822?style=for-the-badge&labelColor=1a1a18&color=4ec9b0" alt="Remote" /></a>
<a href="https://github.com/JoyRS/dev-joyrs"><img src="https://img.shields.io/badge/🖥️-Editor+en+el+navegador-272822?style=for-the-badge&labelColor=1a1a18&color=66d9ef" alt="IDE" /></a>

</div>

---

### `// Portafolio · Backend, cloud & sistemas distribuidos`

> *Fuente de verdad del texto y del stack en el sitio:*  
> [`src/content/cv.content.json`](https://github.com/JoyRS/dev-joyrs/blob/main/src/content/cv.content.json) · [`src/content/stack.preference.json`](https://github.com/JoyRS/dev-joyrs/blob/main/src/content/stack.preference.json)

Soy **Cristhian Joy Reis Serrín** — **Backend Lead / Cloud Engineer** · Arequipa, Perú.

Backend Lead / Cloud Engineer especializado en sistemas distribuidos de alta concurrencia. Diseño arquitecturas que procesan miles de eventos diarios y escalan a cientos de miles de usuarios en producción.

Experiencia liderando plataformas Ecommerce y sistemas empresariales, combinando Node.js, TypeScript y NestJS con arquitecturas event-driven usando NATS y WebSockets.

Me enfoco en performance, resiliencia y simplicidad: transformar sistemas complejos en soluciones mantenibles, eficientes y listas para escalar.

### `## Enfoque`

> `/* Lo que busco en cada sistema que diseño o lidero. */`

- Diseño de sistemas distribuidos  
- Optimización de performance  
- Arquitecturas resilientes  
- Simplicidad sobre complejidad  

---

### `## Qué hace este repo` · UI

La app es un **portafolio con ventana estilo IDE** (barra de título, pestañas, sidebar de “archivos”, panel tipo **terminal**), **ondas al estilo PSP** al fondo y **temas** Monokai (por defecto), Mariana, Dracula y Nord. El explorador y las secciones leen de los JSON de `content/`; la vista *Proyectos* combina esos datos con la **API pública de GitHub** (límite de tasa; opcional `VITE_GITHUB_TOKEN` de solo lectura en `.env`).

---

### `## Stack` · *desde* `stack.preference.json`

> `/* Agrupado por capas — arquitectura, no solo herramientas. */`

| Capa | Tecnologías |
|:---|:---|
| **Lenguajes** | TypeScript, JavaScript, Python |
| **Backend & frameworks** | Node.js, NestJS, Django |
| **Arquitectura** | Microservicios, Sistemas event-driven, APIs de alto rendimiento |
| **Mensajería & tiempo real** | NATS, WebSockets |
| **Datos** | PostgreSQL, Redis, MongoDB, MySQL |
| **Empresa & ERP** | Integración SAP, Sistemas legados |
| **Cloud** | AWS, DigitalOcean, Oracle Cloud, GCP, Cloudflare — mejora y configuración |
| **DevOps & tooling** | Docker, Kubernetes, CI/CD, Git |

**En este repositorio (frontend del portafolio):** React 19, TypeScript, Vite, react-icons.

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,react,vite&perline=6" alt="Build stack" />
  </a>
</p>

---

### `// package.json` — dependencias del *sitio* (no del CV backend)

```bash
# Clonar, variables y desarrollo
git clone https://github.com/JoyRS/dev-joyrs.git
cd dev-joyrs
cp .env.example .env
# Edita .env: VITE_SITE_URL=https://tu-dominio.com (sin / final)
# Opcional: VITE_GITHUB_TOKEN=… (solo lectura, público) para más cupo a la API
npm install
npm run dev
