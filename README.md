<div align="center">

<!--
  ╔══════════════════════════════════════════════════════════╗
  ║   HARSHIT BADYAL — README.md                             ║
  ║   Encrypted love letter. Circuit-traced poetry.          ║
  ╚══════════════════════════════════════════════════════════╝
-->

<!-- HEADER SVG: Cyber-romantic title card -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 320" width="100%">
  <defs>
    <!-- Deep space background gradient -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#050508"/>
      <stop offset="40%" style="stop-color:#0D0818"/>
      <stop offset="70%" style="stop-color:#140825"/>
      <stop offset="100%" style="stop-color:#050508"/>
    </linearGradient>
    <!-- Violet glow -->
    <radialGradient id="violet-glow" cx="30%" cy="50%" r="55%">
      <stop offset="0%" style="stop-color:#9B30D9;stop-opacity:0.18"/>
      <stop offset="100%" style="stop-color:#9B30D9;stop-opacity:0"/>
    </radialGradient>
    <!-- Rose glow -->
    <radialGradient id="rose-glow" cx="75%" cy="45%" r="45%">
      <stop offset="0%" style="stop-color:#E8407A;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#E8407A;stop-opacity:0"/>
    </radialGradient>
    <!-- Cyan glow bottom -->
    <radialGradient id="cyan-glow" cx="50%" cy="90%" r="40%">
      <stop offset="0%" style="stop-color:#3DCFEF;stop-opacity:0.08"/>
      <stop offset="100%" style="stop-color:#3DCFEF;stop-opacity:0"/>
    </radialGradient>
    <!-- Name text filter: glow -->
    <filter id="text-glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Soft outer glow for lines -->
    <filter id="line-glow">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Base -->
  <rect width="900" height="320" fill="url(#bg)" rx="4"/>
  <rect width="900" height="320" fill="url(#violet-glow)"/>
  <rect width="900" height="320" fill="url(#rose-glow)"/>
  <rect width="900" height="320" fill="url(#cyan-glow)"/>

  <!-- Circuit trace — top left -->
  <g filter="url(#line-glow)" opacity="0.35">
    <polyline points="0,48 55,48 55,72 140,72" fill="none" stroke="#9B30D9" stroke-width="1"/>
    <circle cx="55" cy="48" r="2.5" fill="#9B30D9"/>
    <circle cx="140" cy="72" r="2" fill="#9B30D9"/>
    <polyline points="0,105 30,105 30,130 80,130 80,115 120,115" fill="none" stroke="#9B30D9" stroke-width="0.6" stroke-dasharray="4 3"/>
  </g>

  <!-- Circuit trace — right side -->
  <g filter="url(#line-glow)" opacity="0.3">
    <polyline points="900,80 840,80 840,55 760,55" fill="none" stroke="#E8407A" stroke-width="1"/>
    <circle cx="840" cy="80" r="2.5" fill="#E8407A"/>
    <circle cx="760" cy="55" r="2" fill="#E8407A"/>
    <polyline points="900,140 870,140 870,165 820,165 820,150 775,150" fill="none" stroke="#E8407A" stroke-width="0.6" stroke-dasharray="4 3"/>
  </g>

  <!-- Circuit trace — bottom -->
  <g filter="url(#line-glow)" opacity="0.25">
    <polyline points="150,320 150,285 220,285 220,295 310,295" fill="none" stroke="#3DCFEF" stroke-width="0.8"/>
    <circle cx="150" cy="285" r="2" fill="#3DCFEF"/>
    <polyline points="600,320 600,290 660,290 660,275 730,275" fill="none" stroke="#3DCFEF" stroke-width="0.8"/>
    <circle cx="600" cy="290" r="2" fill="#3DCFEF"/>
  </g>

  <!-- Dot grid — faint -->
  <g opacity="0.06">
    <pattern id="dots" x="0" y="0" width="28" height="28" patternUnits="userSpaceOnUse">
      <circle cx="14" cy="14" r="1" fill="#EDE8F5"/>
    </pattern>
    <rect width="900" height="320" fill="url(#dots)"/>
  </g>

  <!-- Thin horizontal rule - editorial -->
  <line x1="60" y1="90" x2="840" y2="90" stroke="#9B30D9" stroke-width="0.4" opacity="0.4"/>

  <!-- HARSHIT — serif display, classical weight -->
  <text x="450" y="168" 
    font-family="Georgia, 'Times New Roman', serif" 
    font-size="78" 
    font-weight="400"
    letter-spacing="18"
    text-anchor="middle" 
    fill="#EDE8F5"
    filter="url(#text-glow)"
    opacity="0.97">HARSHIT</text>

  <!-- BADYAL — lighter weight, spaced -->
  <text x="450" y="210" 
    font-family="Georgia, 'Times New Roman', serif" 
    font-size="28" 
    font-weight="400"
    letter-spacing="28"
    text-anchor="middle" 
    fill="#9B30D9"
    opacity="0.9">BADYAL</text>

  <!-- Thin rule under name -->
  <line x1="300" y1="228" x2="600" y2="228" stroke="#E8407A" stroke-width="0.5" opacity="0.5"/>

  <!-- Tagline — monospace, small -->
  <text x="450" y="254" 
    font-family="'Courier New', monospace" 
    font-size="11" 
    letter-spacing="4"
    text-anchor="middle" 
    fill="#6B6480"
    opacity="0.9">developer  ·  designer  ·  dreamer</text>

  <!-- Small top-left label -->
  <text x="62" y="75" font-family="'Courier New', monospace" font-size="9" letter-spacing="2" fill="#9B30D9" opacity="0.6">SIGNAL : ACTIVE</text>

  <!-- Small top-right label -->
  <text x="838" y="75" font-family="'Courier New', monospace" font-size="9" letter-spacing="2" fill="#E8407A" opacity="0.6" text-anchor="end">JAMMU, IN</text>

  <!-- Bottom status bar -->
  <rect x="0" y="300" width="900" height="20" fill="#050508" opacity="0.7"/>
  <text x="62" y="313" font-family="'Courier New', monospace" font-size="8" letter-spacing="2" fill="#3DCFEF" opacity="0.5">CS STUDENT</text>
  <text x="450" y="313" font-family="'Courier New', monospace" font-size="8" letter-spacing="2" fill="#6B6480" opacity="0.5" text-anchor="middle">[ GITHUB.COM/HARIII01 ]</text>
  <text x="838" y="313" font-family="'Courier New', monospace" font-size="8" letter-spacing="2" fill="#3DCFEF" opacity="0.5" text-anchor="end">CREATING &amp; LEARNING</text>
</svg>

</div>

<br/>

<!-- TYPING SVG: emotional, minimal -->
<div align="center">

[![Typing](https://readme-typing-svg.demolab.com?font=Cormorant+Garamond&weight=400&size=22&duration=3200&pause=1200&color=9B30D9&center=true&vCenter=true&width=680&lines=I+turn+ideas+into+experiences.;Python+is+my+language%2C+design+is+my+voice.;Logic+builds+it.+Emotion+makes+it+matter.;Some+create+with+colour.+Some+with+code.+I+use+both.)](https://git.io/typing-svg)

</div>

<br/>

---

<br/>

<!-- CONNECTIONS: editorial style, left-aligned feel -->
<div align="center">

[![Portfolio](https://img.shields.io/badge/badyal.netlify.app-portfolio-9B30D9?style=flat-square&labelColor=0B0A12&logoColor=white&logo=googlechrome)](https://badyal.netlify.app)&nbsp;&nbsp;
[![Project](https://img.shields.io/badge/harshya.in-creation-E8407A?style=flat-square&labelColor=0B0A12&logo=googlechrome&logoColor=white)](https://harshya.in)&nbsp;&nbsp;
[![GitHub](https://img.shields.io/badge/Hariii01-github-3DCFEF?style=flat-square&labelColor=0B0A12&logo=github&logoColor=white)](https://github.com/Hariii01)&nbsp;&nbsp;
[![Instagram](https://img.shields.io/badge/dear__harshit__01-instagram-E8407A?style=flat-square&labelColor=0B0A12&logo=instagram&logoColor=white)](https://instagram.com/dear_harshit_01)

</div>

<br/>
<br/>

---

&nbsp;

<!-- THE PERSON -->
<!-- No section heading. Just the voice. -->

```
  I write code that thinks.    I design things that feel.
  Somewhere between the two, there is something worth making.
```

&nbsp;

I'm **Hari** — a CS student from Jammu, India. I live between logic and aesthetics, spending my time building things that actually work and designing things people want to look at twice.

**Two sides, one mind:**

&emsp;`logic.exe` &nbsp;→&nbsp; Python · Java · DSA · Automation · Security  
&emsp;`design.exe` &nbsp;→&nbsp; Figma · UI/UX · Typography · Visual identity

&nbsp;

---

&nbsp;

<!-- WORKBENCH -->
<div align="center">

### the developer's workbench

</div>

&nbsp;

**Python** is where I think out loud.

| Area | Tools |
|------|-------|
| GUI Development | Tkinter |
| Automation | Selenium |
| Data | Pandas · NumPy |
| Web Scraping | BeautifulSoup |
| Concepts | OOP · Functions · Exception Handling |

<br/>

<div align="center">

![Python](https://img.shields.io/badge/Python-050508?style=flat-square&logo=python&logoColor=9B30D9)
![Selenium](https://img.shields.io/badge/Selenium-050508?style=flat-square&logo=selenium&logoColor=43B02A)
![Pandas](https://img.shields.io/badge/Pandas-050508?style=flat-square&logo=pandas&logoColor=E8407A)
![NumPy](https://img.shields.io/badge/NumPy-050508?style=flat-square&logo=numpy&logoColor=3DCFEF)
![Java](https://img.shields.io/badge/Java-050508?style=flat-square&logo=openjdk&logoColor=9B30D9)
![HTML](https://img.shields.io/badge/HTML-050508?style=flat-square&logo=html5&logoColor=E34F26)
![CSS](https://img.shields.io/badge/CSS-050508?style=flat-square&logo=css3&logoColor=3DCFEF)
![JavaScript](https://img.shields.io/badge/JS-050508?style=flat-square&logo=javascript&logoColor=F7DF1E)
![C](https://img.shields.io/badge/C-050508?style=flat-square&logo=c&logoColor=9B30D9)

</div>

&nbsp;

**Current focus:** Data Structures & Algorithms in Java. Think better. Write cleaner.

&nbsp;

---

&nbsp;

<!-- SECURITY -->
<div align="center">

### the security underground

</div>

&nbsp;

Curiosity is the first step toward understanding anything.

<div align="center">

![Kali](https://img.shields.io/badge/Kali_Linux-050508?style=flat-square&logo=kalilinux&logoColor=557C94)
![Nmap](https://img.shields.io/badge/Nmap-050508?style=flat-square&logoColor=4682B4)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-050508?style=flat-square&logo=burpsuite&logoColor=FF6633)
![OWASP](https://img.shields.io/badge/OWASP_Top_10-050508?style=flat-square&logo=owasp&logoColor=E8407A)

</div>

Network scanning · Web application security · Linux environments · Ethical hacking fundamentals

*Understand the system. Find the weakness. Learn how to protect it.*

&nbsp;

---

&nbsp;

<!-- DESIGN STUDIO -->
<div align="center">

### the creative studio

</div>

&nbsp;

Code can build a website. Design makes someone want to stay.

<div align="center">

![Figma](https://img.shields.io/badge/Figma-050508?style=flat-square&logo=figma&logoColor=9B30D9)
![Canva](https://img.shields.io/badge/Canva-050508?style=flat-square&logo=canva&logoColor=00C4CC)
![GIMP](https://img.shields.io/badge/GIMP-050508?style=flat-square&logo=gimp&logoColor=E8407A)

</div>

| Area | Craft |
|------|-------|
| UI/UX | Flows · Wireframes · Interaction design |
| Visual | Poster design · Typography · Colour theory |
| Web | Layouts · Visual identity · Digital experiences |

&nbsp;

> *Design isn't decoration. It's the art of making something understandable, memorable, and enjoyable.*

&nbsp;

---

&nbsp;

<!-- PROJECTS -->
<div align="center">

### experiments & creations

</div>

&nbsp;

**harshya.in**
&emsp;Independent web project — exploring modern development, professional design, and digital identity.
&emsp;[→ harshya.in](https://harshya.in)

**badyal portfolio**
&emsp;Personal space on the internet — representing work, creativity, and the developer journey.
&emsp;[→ badyal.netlify.app](https://badyal.netlify.app)

**python playground**
&emsp;Quiz app · Turtle graphics · Sweet shop management · Experiments and practical projects.
&emsp;[→ github.com/Hariii01](https://github.com/Hariii01?tab=repositories)

**security experiments**
&emsp;Linux environments · Network scanning · Web application security research.

&nbsp;

---

&nbsp;

<!-- PROBLEM SOLVING -->
<div align="center">

### the problem-solving arena

&nbsp;

[![LeetCode](https://img.shields.io/badge/LeetCode-dear__harshit__01-FFA116?style=flat-square&logo=leetcode&logoColor=black&labelColor=0B0A12)](https://leetcode.com/u/dear_harshit_01/)
&nbsp;
[![GFG](https://img.shields.io/badge/GeeksforGeeks-harshit1eeyd-2F8D46?style=flat-square&logo=geeksforgeeks&logoColor=white&labelColor=0B0A12)](https://www.geeksforgeeks.org/user/harshit1eeyd/)

&nbsp;

<a href="https://leetcode.com/u/dear_harshit_01/">
  <img src="https://leetcard.jacoblin.cool/dear_harshit_01?theme=dark&font=JetBrains%20Mono&ext=heatmap&border=0&radius=8" width="90%"/>
</a>

</div>

&nbsp;

---

&nbsp;

<!-- GITHUB STATS -->
<div align="center">

### the digital footprint

&nbsp;

<img width="47%" src="https://github-readme-stats.vercel.app/api?username=Hariii01&show_icons=true&theme=tokyonight&bg_color=050508&title_color=9B30D9&icon_color=E8407A&text_color=EDE8F5&border_color=1A1428&border_radius=6&hide_border=false&rank_icon=github"/>
&nbsp;
<img width="47%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hariii01&layout=compact&theme=tokyonight&bg_color=050508&title_color=9B30D9&text_color=EDE8F5&border_color=1A1428&border_radius=6"/>

&nbsp;

<img width="96%" src="https://streak-stats.demolab.com?user=Hariii01&theme=tokyonight&background=050508&ring=9B30D9&fire=E8407A&currStreakLabel=3DCFEF&sideLabels=9B30D9&border=1A1428&border_radius=6"/>

</div>

&nbsp;

---

&nbsp;

<!-- CURRENT STATE: code block as poetry -->
<div align="center">

### right now

</div>

&nbsp;

```python
hari = {
    "learning"  : ["Data Structures & Algorithms", "Java", "Advanced Python"],
    "building"  : ["Meaningful projects", "Creative interfaces", "harshya.in"],
    "exploring" : ["Cybersecurity", "Automation", "UI/UX depth"],
    "mission"   : "Never stop creating.",
}
```

&nbsp;

---

&nbsp;

<!-- FOOTER: love letter in monospace -->

<div align="center">

```
  ╔──────────────────────────────────────────────────────────╗
  │                                                          │
  │   I don't want to simply use technology.                 │
  │   I want to understand it, challenge it,                 │
  │   and create something of my own with it.                │
  │                                                          │
  │   Code written with logic.                               │
  │   Design approached with emotion.                        │
  │   Because why should technology be functional only       │
  │   when it can be beautiful too?                          │
  │                                                          │
  │                              — Harshit Badyal  ♡         │
  ╚──────────────────────────────────────────────────────────╝
```

&nbsp;

<img src="https://komarev.com/ghpvc/?username=Hariii01&label=visitors&color=9B30D9&style=flat-square"/>

</div>

<!-- FOOTER WAVE -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 60" width="100%">
  <defs>
    <linearGradient id="footer-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#050508"/>
      <stop offset="30%" style="stop-color:#9B30D9;stop-opacity:0.6"/>
      <stop offset="60%" style="stop-color:#E8407A;stop-opacity:0.4"/>
      <stop offset="100%" style="stop-color:#050508"/>
    </linearGradient>
    <filter id="footer-glow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="900" height="60" fill="#050508"/>
  <!-- Heartbeat line — the signature of a romantic-cyber soul -->
  <polyline 
    points="0,30 80,30 100,30 115,10 130,50 145,30 160,30 180,30 200,30 215,18 225,42 235,30 260,30 350,30 365,8 375,52 385,30 410,30 500,30 515,20 525,40 535,30 560,30 650,30 665,12 677,48 689,30 710,30 800,30 820,30" 
    fill="none" stroke="url(#footer-grad)" stroke-width="1.5" filter="url(#footer-glow)"
    opacity="0.8"
  />
  <!-- Circuit dots at key nodes -->
  <circle cx="115" cy="10" r="2" fill="#9B30D9" opacity="0.7"/>
  <circle cx="130" cy="50" r="2" fill="#9B30D9" opacity="0.7"/>
  <circle cx="365" cy="8" r="2" fill="#E8407A" opacity="0.7"/>
  <circle cx="375" cy="52" r="2" fill="#E8407A" opacity="0.7"/>
  <circle cx="665" cy="12" r="2" fill="#3DCFEF" opacity="0.6"/>
  <circle cx="677" cy="48" r="2" fill="#3DCFEF" opacity="0.6"/>
</svg>
