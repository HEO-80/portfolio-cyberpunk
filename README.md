<div align="center">

# ⬡ NETWATCH OS v2.077

<img src="https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white"/>
<img src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=black"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/xterm.js-000000?style=for-the-badge&logo=gnometerminal&logoColor=white"/>
<img src="https://img.shields.io/badge/Cyberpunk_2077-FFCC00?style=for-the-badge&logoColor=black"/>

**Portfolio personal con identidad de sistema operativo Cyberpunk.**

*Boot screen · Terminal real interactiva · HUD · Glitch effects · Grid animado*

**🌍 [English](#-english-version) · 🇪🇸 [Español](#-versión-en-español)**

</div>

---

## 📸 Preview

| Hero + Terminal simulada | Navegación HUD |
|:---:|:---:|
| ![Hero](src/assets/img/page1.png) | ![Nav](src/assets/img/page2.png) |

---

## 🇪🇸 Versión en Español

### ✨ Características

- **Boot screen** — secuencia de arranque con logs del sistema y barra de progreso. Cualquier tecla para inicializar
- **HUD bar** — navegación fija con reloj en tiempo real y estado del sistema
- **Terminal simulada** — en el hero, reproduce automáticamente comandos reales (`forge test`, `git push`, `[PASS]`)
- **Terminal real** (xterm.js) — abierta con el botón TERMINAL, acepta comandos: `whoami`, `projects`, `skills`, `contact`, `status`, `clear`
- **Glitch effects** — en títulos, nav links y botones
- **Grid animado** — fondo con rejilla en movimiento continuo
- **Scanlines** — overlay de líneas de TV sobre toda la interfaz
- **Typing effect** — roles rotativos en el hero
- **Skill bars** — animadas al cargar con CSS puro

---

### 🗂️ Estructura

```
portfolio-cyberpunk/
├── src/
│   ├── assets/img/
│   │   ├── page1.png
│   │   └── page2.png
│   ├── layouts/
│   │   └── Layout.astro     ← HTML base + fuentes + estilos globales
│   └── pages/
│       └── index.astro      ← Todo el portfolio en un único archivo
├── astro.config.mjs
└── package.json
```

---

### 🚀 Instalación

```bash
git clone https://github.com/HEO-80/portfolio-cyberpunk.git
cd portfolio-cyberpunk
npm install
npm run dev
```

Abre `http://localhost:4321`

---

### ⌨️ Comandos de la terminal

Pulsa el botón **TERMINAL** en la nav:

| Comando | Descripción |
|:---|:---|
| `help` | Listar comandos disponibles |
| `whoami` | Perfil del operativo |
| `projects` | Repositorios activos |
| `skills` | Módulos instalados |
| `contact` | Canales de comunicación |
| `status` | Estado del sistema |
| `clear` | Limpiar pantalla |

---

### 🗺️ Roadmap

- [x] Boot screen con secuencia de arranque
- [x] HUD bar con reloj en tiempo real
- [x] Hero con typing effect y glitch
- [x] Terminal simulada con comandos reales
- [x] Terminal real interactiva (xterm.js)
- [x] Secciones: Proyectos · Skills · About · Contacto
- [ ] GSAP ScrollTrigger en secciones
- [ ] Animaciones de entrada con stagger
- [ ] Versión móvil responsive
- [ ] Modo filesystem — navegar proyectos como directorios
- [ ] Deploy en Vercel

---

### 🧑‍💻 Autor

**Héctor Oviedo** — Full Stack Dev & DeFi Researcher

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hectorob/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HEO-80)
[![Portfolio](https://img.shields.io/badge/Portfolio-FFCC00?style=for-the-badge&logo=vercel&logoColor=black)](https://landing-page-react-hector.vercel.app)

---
---

## 🇬🇧 English Version

### ✨ Features

- **Boot screen** — system startup sequence with logs and progress bar. Press any key to initialize
- **HUD bar** — fixed navigation with real-time clock and system status
- **Simulated terminal** — hero auto-plays real commands (`forge test`, `git push`, `[PASS]`)
- **Real terminal** (xterm.js) — opened via the TERMINAL button, accepts: `whoami`, `projects`, `skills`, `contact`, `status`, `clear`
- **Glitch effects** — on titles, nav links and buttons
- **Animated grid** — continuously moving background grid
- **Scanlines** — TV scanline overlay across the entire interface
- **Typing effect** — rotating roles in the hero
- **Skill bars** — CSS-only animated on load

---

### 🗂️ Structure

```
portfolio-cyberpunk/
├── src/
│   ├── assets/img/
│   │   ├── page1.png
│   │   └── page2.png
│   ├── layouts/
│   │   └── Layout.astro     ← Base HTML + fonts + global styles
│   └── pages/
│       └── index.astro      ← Entire portfolio in a single file
├── astro.config.mjs
└── package.json
```

---

### 🚀 Installation

```bash
git clone https://github.com/HEO-80/portfolio-cyberpunk.git
cd portfolio-cyberpunk
npm install
npm run dev
```

Open `http://localhost:4321`

---

### ⌨️ Terminal Commands

Click the **TERMINAL** button in the nav:

| Command | Description |
|:---|:---|
| `help` | List available commands |
| `whoami` | Operative profile |
| `projects` | Active repositories |
| `skills` | Installed modules |
| `contact` | Communication channels |
| `status` | System status |
| `clear` | Clear screen |

---

### 🗺️ Roadmap

- [x] Boot screen with startup sequence
- [x] HUD bar with real-time clock
- [x] Hero with typing effect and glitch
- [x] Simulated terminal with real commands
- [x] Real interactive terminal (xterm.js)
- [x] Sections: Projects · Skills · About · Contact
- [ ] GSAP ScrollTrigger on sections
- [ ] Staggered entrance animations
- [ ] Mobile responsive version
- [ ] Filesystem mode — browse projects as directories
- [ ] Deploy to Vercel

---

### 🧑‍💻 Author

**Héctor Oviedo** — Full Stack Dev & DeFi Researcher

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hectorob/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HEO-80)
[![Portfolio](https://img.shields.io/badge/Portfolio-FFCC00?style=for-the-badge&logo=vercel&logoColor=black)](https://landing-page-react-hector.vercel.app)

---

<div align="center">
  <sub>⬡ NETWATCH OS v2.077 · Built with Astro · <strong>Héctor Oviedo</strong> · Zaragoza, España</sub>
</div>
