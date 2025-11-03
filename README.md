# 👋 Hi, I'm [Your Name]

<p align="center">
  <!-- Neon Glowing Text -->
  <svg width="600" height="100">
    <defs>
      <filter id="glow">
        <feGaussianBlur stdDeviation="4.5" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
          font-family="monospace" font-size="50" fill="#0ff" filter="url(#glow)">
      NEON CODER
      <animate attributeName="fill" values="#0ff;#f0f;#0ff" dur="2s" repeatCount="indefinite"/>
    </text>
  </svg>
</p>

---

## 🌐 About Me
I’m a **Neon Coder & Animator** who loves futuristic designs and glowing interactive effects.  

---

## 🛠️ Skills
- **HTML5**
- **CSS3**
- **JavaScript**
- **Three.js** (for advanced neon 3D effects)
- **SVG Animations**
- **Vanta.js / Particles.js**

---

## ✨ Neon Text Example
<p align="center">
  <svg width="500" height="80">
    <defs>
      <linearGradient id="neonGradient" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#0ff">
          <animate attributeName="stop-color" values="#0ff;#f0f;#0ff" dur="2s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#f0f">
          <animate attributeName="stop-color" values="#f0f;#0ff;#f0f" dur="2s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>
      <filter id="glow2" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="4" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
          font-family="monospace" font-size="40" fill="url(#neonGradient)" filter="url(#glow2)">
      CODE IN NEON
    </text>
  </svg>
</p>
