<!-- HERO con título animado (neón + flicker) -->
<p align="center">
  <svg width="100%" height="180" viewBox="0 0 1200 180" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="g" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#00E5FF"/>
        <stop offset="50%" stop-color="#9D4EDD"/>
        <stop offset="100%" stop-color="#00E5FF"/>
        <animate attributeName="x1" values="0%;100%;0%" dur="8s" repeatCount="indefinite"/>
        <animate attributeName="x2" values="100%;0%;100%" dur="8s" repeatCount="indefinite"/>
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="3.5" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <text x="50%" y="55%" text-anchor="middle"
          font-family="JetBrains Mono, Consolas, monospace"
          font-size="44" fill="url(#g)" filter="url(#glow)" letter-spacing="2">
      DAVID VELARDE
      <!-- flicker suave -->
      <animate attributeName="opacity" values="0.85;1;0.85" dur="3.6s" repeatCount="indefinite"/>
    </text>

    <!-- línea base con “escáner” -->
    <rect x="150" y="120" width="900" height="2" rx="1" fill="url(#g)" opacity="0.6"/>
    <rect x="150" y="120" width="120" height="2" rx="1" fill="#00E5FF">
      <animate attributeName="x" values="150;930;150" dur="5s" repeatCount="indefinite"/>
    </rect>
  </svg>
</p>

<!-- Subtítulo con typing (dinámico) -->
<p align="center">
  <a href="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&pause=1200&color=00E5FF&center=true&vCenter=true&random=false&width=700&lines=Full-Stack+Developer+%7C+React+%7C+TypeScript;UI+rápidas+%2B+accesibles;Construyendo+productos+con+impacto">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&pause=1200&color=00E5FF&center=true&vCenter=true&random=false&width=700&lines=Full-Stack+Developer+%7C+React+%7C+TypeScript;UI+rápidas+%2B+accesibles;Construyendo+productos+con+impacto" alt="Typing SVG" />
  </a>
</p>

<!-- Separador animado (onda) -->
<p align="center">
  <svg width="760" height="32" viewBox="0 0 600 32" xmlns="http://www.w3.org/2000/svg">
    <path id="wave" d="M0,16 C80,0 120,32 200,16 C280,0 320,32 400,16 C480,0 520,32 600,16"
          fill="none" stroke="#0ea5e9" stroke-width="2" opacity="0.8"/>
    <circle r="3" fill="#9d4edd">
      <animateMotion dur="4s" repeatCount="indefinite" path="M0,16 C80,0 120,32 200,16 C280,0 320,32 400,16 C480,0 520,32 600,16"/>
    </circle>
  </svg>
</p>

## 🚀 Hey!

Soy **David**, desarrollador web peruano (Ing. de Sistemas). Pasé por proyectos de tecnología minera y volví para crear **apps Full-Stack** enfocadas en rendimiento y DX.  
Busco roles donde pueda **aplicar** y **aprender** construyendo software de calidad.

### 🧰 Tech stack (core)
<p align="center">
  <img src="https://img.shields.io/badge/React-0A0A0A?logo=react&logoColor=61DAFB&style=for-the-badge" />
  <img src="https://img.shields.io/badge/TypeScript-0A0A0A?logo=typescript&logoColor=3178C6&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Redux_Toolkit-0A0A0A?logo=redux&logoColor=764ABC&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tailwind-0A0A0A?logo=tailwindcss&logoColor=38BDF8&style=for-the-badge" />
  <img src="https://img.shields.io/badge/React_Query-0A0A0A?logo=reactquery&logoColor=FF4154&style=for-the-badge" />
  <img src="https://img.shields.io/badge/PostgreSQL-0A0A0A?logo=postgresql&logoColor=4169E1&style=for-the-badge" />
</p>

<!-- Separador glow simple -->
<p align="center">
  <img src="https://img.shields.io/badge/-%20-0A0A0A?style=for-the-badge&labelColor=0A0A0A&color=0A0A0A">
</p>

## 🧪 Proyectos
- **IndividualProject: VideoGames** — proyecto individual aprobado (Henry).
- **PI-Food** — objetivos técnicos ok, pendientes de estilo (aprendizajes UI/UX).
- **PFVideojuegos-Front** — proyecto final grupal (7), aprobado.

> *Demos y repos disponibles al contacto.*

### 📡 Ahora mismo
- Accesibilidad, Zustand/Redux Toolkit, normalización de fechas en PostgreSQL.
- Abierto a Frontend / Full-Stack (React + TS).

<!-- Tarjetas con efecto “neón” (tema oscuro/sci-fi) -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=TU_USUARIO&show_icons=true&theme=tokyonight&hide_title=true" height="140" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TU_USUARIO&layout=compact&theme=tokyonight" height="140" />
</p>

<!-- Footer con orbe animado -->
<p align="center">
  <svg width="200" height="60" viewBox="0 0 200 60" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <radialGradient id="rg" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#00E5FF" stop-opacity="1"/>
        <stop offset="60%" stop-color="#00E5FF" stop-opacity="0.15"/>
        <stop offset="100%" stop-color="#00E5FF" stop-opacity="0"/>
      </radialGradient>
    </defs>
    <circle cx="30" cy="30" r="10" fill="#9D4EDD">
      <animate attributeName="cx" values="30;170;30" dur="5.5s" repeatCount="indefinite"/>
      <animate attributeName="r" values="10;6;10" dur="2.2s" repeatCount="indefinite"/>
    </circle>
    <ellipse cx="30" cy="30" rx="36" ry="18" fill="url(#rg)" opacity="0.8">
      <animate attributeName="cx" values="30;170;30" dur="5.5s" repeatCount="indefinite"/>
    </ellipse>
    <text x="200" y="36" text-anchor="end" font-family="JetBrains Mono, monospace" font-size="12" fill="#9CA3AF">
      BUILD THE FUTURE
    </text>
  </svg>
</p>

## 📬 Contacto
- 📞 +51 959 396 384  
- ✉️ [Davicova84@gmail.com](mailto:Davicova84@gmail.com)  
- 🔗 [LinkedIn](https://www.linkedin.com/in/david-hebert-velarde-alvarado-196a4023a/)
