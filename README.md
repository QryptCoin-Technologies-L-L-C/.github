<div align="center">

<!-- Animated Merged QT Logo with Continuous Animations -->
<svg width="100%" height="280" viewBox="0 0 800 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Animated Gradient -->
    <linearGradient id="cyberGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00E5E5">
        <animate attributeName="stop-color" values="#00E5E5;#00FFFF;#00BFFF;#00E5E5" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#00FFFF">
        <animate attributeName="stop-color" values="#00FFFF;#00BFFF;#00E5E5;#00FFFF" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#00BFFF">
        <animate attributeName="stop-color" values="#00BFFF;#00E5E5;#00FFFF;#00BFFF" dur="3s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    
    <!-- Pulsing Glow Filter -->
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="coloredBlur">
        <animate attributeName="stdDeviation" values="3;6;3" dur="2s" repeatCount="indefinite"/>
      </feGaussianBlur>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    
    <!-- Secondary Glow for Tagline -->
    <filter id="textGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="2" result="coloredBlur">
        <animate attributeName="stdDeviation" values="1;3;1" dur="2.5s" repeatCount="indefinite"/>
      </feGaussianBlur>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Background Grid -->
  <pattern id="grid" width="30" height="30" patternUnits="userSpaceOnUse">
    <path d="M 30 0 L 0 0 0 30" fill="none" stroke="rgba(0,229,229,0.08)" stroke-width="1"/>
  </pattern>
  <rect width="100%" height="100%" fill="url(#grid)"/>
  
  <!-- Merged QT Logo with Pulsing Glow -->
  <g transform="translate(400, 100)" filter="url(#glow)">
    <!-- Q Circle -->
    <circle cx="-60" cy="0" r="58" fill="none" stroke="url(#cyberGrad)" stroke-width="28">
      <animate attributeName="stroke-width" values="28;30;28" dur="2s" repeatCount="indefinite"/>
    </circle>
    
    <!-- Q Tail -->
    <rect x="-25" y="20" width="70" height="28" fill="url(#cyberGrad)" transform="rotate(45 -25 20)">
      <animate attributeName="opacity" values="1;0.85;1" dur="2s" repeatCount="indefinite"/>
    </rect>
    
    <!-- T Horizontal Bar -->
    <rect x="-5" y="-58" width="130" height="28" fill="url(#cyberGrad)">
      <animate attributeName="opacity" values="1;0.85;1" dur="2s" repeatCount="indefinite"/>
    </rect>
    
    <!-- T Vertical Bar -->
    <rect x="47" y="-58" width="28" height="116" fill="url(#cyberGrad)">
      <animate attributeName="opacity" values="1;0.85;1" dur="2s" repeatCount="indefinite"/>
    </rect>
  </g>
  
  <!-- Tagline with Glow -->
  <text x="400" y="240" text-anchor="middle" fill="url(#cyberGrad)" font-family="monospace" font-size="14" letter-spacing="4" filter="url(#textGlow)">
    <animate attributeName="opacity" values="0.8;1;0.8" dur="2.5s" repeatCount="indefinite"/>
    SECURE SOFTWARE FOR AUDITABLE SYSTEMS
  </text>
</svg>

<br/>

# QryptCoin Technologies, L.L.C.

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3000&pause=1000&color=00E5E5&center=true&vCenter=true&width=450&lines=Cryptographic+Infrastructure;Compliance+Solutions;Building+Trust+Through+Code" alt="Typing SVG" />

<br/><br/>

[![Website](https://img.shields.io/badge/🌐_qryptcointechnologies.com-00E5E5?style=for-the-badge&labelColor=0d1117)](https://qryptcointechnologies.com)
[![Email](https://img.shields.io/badge/📧_Contact_Us-00E5E5?style=for-the-badge&labelColor=0d1117)](mailto:info@qryptcointechnologies.com)

</div>

---

<div align="center">

### 🔐 What We Do

</div>

We are a **U.S.-based software company** specializing in **cryptographic infrastructure** and **compliance solutions**.

Our mission is to build secure, auditable systems that organizations can trust.

<br/>

<div align="center">

| 🛡️ Security-First | ⚡ High Performance | 🔍 Fully Auditable |
|:---:|:---:|:---:|
| Built with cryptographic best practices | Optimized for enterprise scale | Transparent & verifiable systems |

</div>

---

<div align="center">

### 🔒 Security

Found a vulnerability? We take security seriously.

[![Report Security Issue](https://img.shields.io/badge/🛡️_Report_Vulnerability-FF4444?style=for-the-badge&labelColor=0d1117)](mailto:security@qryptcointechnologies.com)

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5E5,100:00FFFF&height=80&section=footer"/>

**© 2025 QryptCoin Technologies, L.L.C.**

<sub>All rights reserved.</sub>

</div>
