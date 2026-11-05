<div align="center">

<!--
╔═══════════════════════════════════════════════════════════════════╗
║   HARSHIT BADYAL · README.md · Cyber-Romantic · Legendary         ║
╚═══════════════════════════════════════════════════════════════════╝
-->

<!-- ═══════ HERO BANNER — custom SVG, zero external dependency ═══════ -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 300" width="100%">
  <defs>
    <!-- Deep space void -->
    <linearGradient id="bg-main" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%"   stop-color="#050508"/>
      <stop offset="35%"  stop-color="#0E061C"/>
      <stop offset="65%"  stop-color="#150828"/>
      <stop offset="100%" stop-color="#050508"/>
    </linearGradient>
    <!-- Violet nebula bloom — left -->
    <radialGradient id="nebula-v" cx="28%" cy="52%" r="42%">
      <stop offset="0%"   stop-color="#7B2FBE" stop-opacity="0.22"/>
      <stop offset="60%"  stop-color="#5B1FA0" stop-opacity="0.08"/>
      <stop offset="100%" stop-color="#5B1FA0" stop-opacity="0"/>
    </radialGradient>
    <!-- Rose nebula bloom — right -->
    <radialGradient id="nebula-r" cx="74%" cy="45%" r="38%">
      <stop offset="0%"   stop-color="#E8407A" stop-opacity="0.18"/>
      <stop offset="60%"  stop-color="#C02860" stop-opacity="0.06"/>
      <stop offset="100%" stop-color="#C02860" stop-opacity="0"/>
    </radialGradient>
    <!-- Cyan bloom — bottom center -->
    <radialGradient id="nebula-c" cx="50%" cy="92%" r="35%">
      <stop offset="0%"   stop-color="#2BCFD8" stop-opacity="0.10"/>
      <stop offset="100%" stop-color="#2BCFD8" stop-opacity="0"/>
    </radialGradient>
    <!-- Name glow filter -->
    <filter id="glow-name" x="-15%" y="-40%" width="130%" height="180%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Soft line glow -->
    <filter id="glow-line" x="-10%" y="-200%" width="120%" height="500%">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Star twinkle animation -->
    <style>
      @keyframes twinkle-a { 0%,100%{opacity:.7} 50%{opacity:.15} }
      @keyframes twinkle-b { 0%,100%{opacity:.4} 50%{opacity:.9} }
      @keyframes twinkle-c { 0%,100%{opacity:.5} 60%{opacity:.1} }
      @keyframes pulse-line { 0%,100%{opacity:.5} 50%{opacity:1} }
      .st-a { animation: twinkle-a 2.8s ease-in-out infinite; }
      .st-b { animation: twinkle-b 1.9s ease-in-out infinite; }
      .st-c { animation: twinkle-c 3.4s ease-in-out infinite; }
      .cline { animation: pulse-line 3s ease-in-out infinite; }
    </style>
  </defs>

  <!-- ── Background layers ── -->
  <rect width="900" height="300" fill="url(#bg-main)"/>
  <rect width="900" height="300" fill="url(#nebula-v)"/>
  <rect width="900" height="300" fill="url(#nebula-r)"/>
  <rect width="900" height="300" fill="url(#nebula-c)"/>

  <!-- ── Star field ── -->
  <!-- Row 1 -->
  <circle class="st-a" cx="45"  cy="22"  r="1.1" fill="#FCE7F3" opacity=".6"/>
  <circle class="st-b" cx="130" cy="38"  r="0.8" fill="#BB8CFF" opacity=".5"/>
  <circle class="st-c" cx="210" cy="15"  r="1"   fill="#FCE7F3" opacity=".4"/>
  <circle class="st-a" cx="310" cy="30"  r="0.7" fill="#F57799" opacity=".6"/>
  <circle class="st-b" cx="420" cy="12"  r="1.2" fill="#FCE7F3" opacity=".5"/>
  <circle class="st-c" cx="530" cy="28"  r="0.9" fill="#BB8CFF" opacity=".4"/>
  <circle class="st-a" cx="640" cy="18"  r="1"   fill="#F57799" opacity=".5"/>
  <circle class="st-b" cx="730" cy="35"  r="0.8" fill="#FCE7F3" opacity=".6"/>
  <circle class="st-c" cx="840" cy="20"  r="1.1" fill="#BB8CFF" opacity=".4"/>
  <circle class="st-a" cx="880" cy="42"  r="0.7" fill="#F57799" opacity=".5"/>
  <!-- Row 2 -->
  <circle class="st-c" cx="78"  cy="68"  r="0.9" fill="#BB8CFF" opacity=".4"/>
  <circle class="st-b" cx="175" cy="58"  r="1.1" fill="#FCE7F3" opacity=".5"/>
  <circle class="st-a" cx="260" cy="75"  r="0.7" fill="#F57799" opacity=".6"/>
  <circle class="st-c" cx="370" cy="55"  r="1"   fill="#FCE7F3" opacity=".4"/>
  <circle class="st-b" cx="490" cy="65"  r="0.8" fill="#BB8CFF" opacity=".5"/>
  <circle class="st-a" cx="590" cy="52"  r="1.2" fill="#F57799" opacity=".4"/>
  <circle class="st-c" cx="700" cy="72"  r="0.9" fill="#FCE7F3" opacity=".5"/>
  <circle class="st-b" cx="800" cy="58"  r="1"   fill="#BB8CFF" opacity=".4"/>
  <circle class="st-a" cx="860" cy="80"  r="0.7" fill="#F57799" opacity=".6"/>
  <!-- Sparse bottom -->
  <circle class="st-b" cx="60"  cy="260" r="0.8" fill="#FCE7F3" opacity=".3"/>
  <circle class="st-a" cx="200" cy="275" r="0.7" fill="#BB8CFF" opacity=".3"/>
  <circle class="st-c" cx="700" cy="265" r="1"   fill="#F57799" opacity=".3"/>
  <circle class="st-b" cx="850" cy="258" r="0.8" fill="#FCE7F3" opacity=".3"/>

  <!-- ── Circuit traces — left ── -->
  <g filter="url(#glow-line)" opacity="0.45">
    <polyline points="0,54 42,54 42,82 108,82" fill="none" stroke="#BB8CFF" stroke-width="0.9"/>
    <circle cx="42" cy="54" r="2.2" fill="#BB8CFF"/>
    <circle cx="108" cy="82" r="1.8" fill="#BB8CFF"/>
    <polyline points="0,110 25,110 25,138 72,138 72,122 105,122"
      fill="none" stroke="#BB8CFF" stroke-width="0.5" stroke-dasharray="3 3" opacity=".6"/>
  </g>

  <!-- ── Circuit traces — right ── -->
  <g filter="url(#glow-line)" opacity="0.4">
    <polyline points="900,70 858,70 858,44 782,44" fill="none" stroke="#F57799" stroke-width="0.9"/>
    <circle cx="858" cy="70" r="2.2" fill="#F57799"/>
    <circle cx="782" cy="44" r="1.8" fill="#F57799"/>
    <polyline points="900,118 872,118 872,142 824,142 824,128 790,128"
      fill="none" stroke="#F57799" stroke-width="0.5" stroke-dasharray="3 3" opacity=".6"/>
  </g>

  <!-- ── Circuit traces — bottom ── -->
  <g filter="url(#glow-line)" opacity="0.3">
    <polyline points="130,300 130,274 196,274 196,284 278,284"
      fill="none" stroke="#2BCFD8" stroke-width="0.8"/>
    <circle cx="130" cy="274" r="1.8" fill="#2BCFD8"/>
    <polyline points="620,300 620,278 680,278 680,264 745,264"
      fill="none" stroke="#2BCFD8" stroke-width="0.8"/>
    <circle cx="620" cy="278" r="1.8" fill="#2BCFD8"/>
  </g>

  <!-- ── Dot matrix — faint atmosphere ── -->
  <pattern id="dot-grid" x="0" y="0" width="30" height="30" patternUnits="userSpaceOnUse">
    <circle cx="15" cy="15" r="0.9" fill="#FCE7F3" opacity="0.055"/>
  </pattern>
  <rect width="900" height="300" fill="url(#dot-grid)"/>

  <!-- ── Top rule ── -->
  <line class="cline" x1="62" y1="98" x2="838" y2="98"
    stroke="#BB8CFF" stroke-width="0.4" opacity="0.5"/>

  <!-- ── HARSHIT — serif display ── -->
  <text x="450" y="176"
    font-family="Georgia, 'Book Antiqua', serif"
    font-size="82"
    font-weight="400"
    letter-spacing="20"
    text-anchor="middle"
    fill="#FCE7F3"
    filter="url(#glow-name)"
    opacity="0.97">HARSHIT</text>

  <!-- ── BADYAL — spaced violet ── -->
  <text x="450" y="218"
    font-family="Georgia, 'Book Antiqua', serif"
    font-size="30"
    font-weight="400"
    letter-spacing="30"
    text-anchor="middle"
    fill="#BB8CFF"
    opacity="0.92">BADYAL</text>

  <!-- ── Divider under name ── -->
  <line x1="288" y1="236" x2="612" y2="236"
    stroke="#F57799" stroke-width="0.6" opacity="0.55"/>

  <!-- ── Tagline ── -->
  <text x="450" y="262"
    font-family="'Courier New', 'Lucida Console', monospace"
    font-size="11"
    letter-spacing="5"
    text-anchor="middle"
    fill="#6B5A80"
    opacity="0.95">developer  ·  designer  ·  dreamer</text>

  <!-- ── Micro labels ── -->
  <text x="64" y="84"
    font-family="'Courier New', monospace"
    font-size="8.5" letter-spacing="2.5"
    fill="#BB8CFF" opacity="0.65">SIGNAL : ACTIVE</text>
  <text x="836" y="84"
    font-family="'Courier New', monospace"
    font-size="8.5" letter-spacing="2.5"
    fill="#F57799" opacity="0.65"
    text-anchor="end">JAMMU, IN</text>

  <!-- ── Bottom status bar ── -->
  <rect x="0" y="282" width="900" height="18" fill="#050508" opacity="0.75"/>
  <text x="64" y="294"
    font-family="'Courier New', monospace"
    font-size="7.5" letter-spacing="2"
    fill="#2BCFD8" opacity="0.55">CS STUDENT</text>
  <text x="450" y="294"
    font-family="'Courier New', monospace"
    font-size="7.5" letter-spacing="2"
    fill="#6B5A80" opacity="0.55"
    text-anchor="middle">[ GITHUB.COM/HARIII01 ]</text>
  <text x="836" y="294"
    font-family="'Courier New', monospace"
    font-size="7.5" letter-spacing="2"
    fill="#2BCFD8" opacity="0.55"
    text-anchor="end">CREATING &amp; LEARNING</text>
</svg>

<br/>

<!-- ── TYPING SVG ── -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=2800&pause=900&color=F57799&center=true&vCenter=true&width=680&lines=Hello%2C+I'm+Hari+%E2%9C%A6;I+turn+ideas+into+experiences.;Python+is+my+language%2C+design+is+my+voice.;A+curious+mind+with+a+creative+soul.;Building+beautiful+things%2C+one+line+at+a+time."/>

<br/><br/>

<!-- ── BADGES — deeper darks, your palette ── -->
[![Portfolio](https://img.shields.io/badge/✦_MY_WORLD-badyal.netlify.app-F57799?style=for-the-badge&labelColor=0B0718)](https://badyal.netlify.app)
[![Project](https://img.shields.io/badge/✧_MY_CREATION-harshya.in-BB8CFF?style=for-the-badge&labelColor=0B0718)](https://harshya.in)
[![Instagram](https://img.shields.io/badge/♡_MY_LITTLE_CORNER-dear__harshit__01-FF6B9D?style=for-the-badge&labelColor=0B0718)](https://instagram.com/dear_harshit_01)

<br/><br/>

*"Some create with colours, some with code. I fell in love with both."*

</div>

---

<div align="center">

### ◈ 00 — THE PERSON BEHIND THE PIXELS ◈

</div>

<br/>

<!-- ── IDENTITY CARD — custom SVG, yours but elevated ── -->
<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 540 220" width="80%">
  <defs>
    <linearGradient id="card-bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%"   stop-color="#0B0718"/>
      <stop offset="100%" stop-color="#170A28"/>
    </linearGradient>
    <linearGradient id="card-border" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%"   stop-color="#BB8CFF" stop-opacity="0.6"/>
      <stop offset="50%"  stop-color="#F57799" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#BB8CFF" stop-opacity="0.3"/>
    </linearGradient>
    <filter id="card-glow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <style>
      @keyframes blink-cursor { 0%,100%{opacity:1} 50%{opacity:0} }
      .cursor { animation: blink-cursor 1s step-end infinite; }
    </style>
  </defs>

  <!-- Card glow halo -->
  <rect x="12" y="12" width="516" height="196" rx="14"
    fill="#BB8CFF" opacity="0.07" filter="url(#card-glow)"/>

  <!-- Card body -->
  <rect x="1" y="1" width="538" height="218" rx="13" fill="url(#card-bg)"/>

  <!-- Border — gradient stroke trick via two rects -->
  <rect x="0.5" y="0.5" width="539" height="219" rx="13.5"
    fill="none" stroke="url(#card-border)" stroke-width="1"/>

  <!-- Top-left corner accent -->
  <polyline points="2,30 2,2 30,2" fill="none" stroke="#BB8CFF" stroke-width="1.5" opacity=".7"/>
  <!-- Top-right corner accent -->
  <polyline points="510,2 538,2 538,30" fill="none" stroke="#F57799" stroke-width="1.5" opacity=".7"/>
  <!-- Bottom-left corner accent -->
  <polyline points="2,190 2,218 30,218" fill="none" stroke="#F57799" stroke-width="1.5" opacity=".7"/>
  <!-- Bottom-right corner accent -->
  <polyline points="510,218 538,218 538,190" fill="none" stroke="#BB8CFF" stroke-width="1.5" opacity=".7"/>

  <!-- Header bar -->
  <rect x="1" y="1" width="538" height="36" rx="13" fill="#BB8CFF" opacity="0.07"/>
  <rect x="1" y="25" width="538" height="12" fill="#BB8CFF" opacity="0.07"/>

  <!-- Header text -->
  <text x="20" y="24"
    font-family="'Courier New', monospace"
    font-size="11" font-weight="bold" letter-spacing="3"
    fill="#BB8CFF" opacity="0.9">IDENTITY FOUND</text>
  <text x="520" y="24"
    font-family="'Courier New', monospace"
    font-size="9" letter-spacing="2"
    fill="#F57799" opacity="0.6"
    text-anchor="end">ACCESS GRANTED</text>

  <!-- Divider -->
  <line x1="1" y1="37" x2="539" y2="37" stroke="#BB8CFF" stroke-width="0.5" opacity="0.3"/>

  <!-- Data rows — left column labels -->
  <text x="22" y="68"  font-family="'Courier New', monospace" font-size="11" letter-spacing="2" fill="#6B5A80">NAME</text>
  <text x="22" y="96"  font-family="'Courier New', monospace" font-size="11" letter-spacing="2" fill="#6B5A80">ALIAS</text>
  <text x="22" y="124" font-family="'Courier New', monospace" font-size="11" letter-spacing="2" fill="#6B5A80">ROLE</text>
  <text x="22" y="152" font-family="'Courier New', monospace" font-size="11" letter-spacing="2" fill="#6B5A80">STUDY</text>
  <text x="22" y="180" font-family="'Courier New', monospace" font-size="11" letter-spacing="2" fill="#6B5A80">BASE</text>
  <text x="22" y="208" font-family="'Courier New', monospace" font-size="11" letter-spacing="2" fill="#6B5A80">STATUS</text>

  <!-- Separators -->
  <text x="118" y="68"  font-family="'Courier New', monospace" font-size="11" fill="#F57799" opacity="0.5">:</text>
  <text x="118" y="96"  font-family="'Courier New', monospace" font-size="11" fill="#F57799" opacity="0.5">:</text>
  <text x="118" y="124" font-family="'Courier New', monospace" font-size="11" fill="#F57799" opacity="0.5">:</text>
  <text x="118" y="152" font-family="'Courier New', monospace" font-size="11" fill="#F57799" opacity="0.5">:</text>
  <text x="118" y="180" font-family="'Courier New', monospace" font-size="11" fill="#F57799" opacity="0.5">:</text>
  <text x="118" y="208" font-family="'Courier New', monospace" font-size="11" fill="#F57799" opacity="0.5">:</text>

  <!-- Data values -->
  <text x="136" y="68"  font-family="'Courier New', monospace" font-size="11" fill="#FCE7F3">Harshit Badyal</text>
  <text x="136" y="96"  font-family="'Courier New', monospace" font-size="11" fill="#F57799">Hari</text>
  <text x="136" y="124" font-family="'Courier New', monospace" font-size="11" fill="#FCE7F3">Developer  /  Designer</text>
  <text x="136" y="152" font-family="'Courier New', monospace" font-size="11" fill="#FCE7F3">Computer Science</text>
  <text x="136" y="180" font-family="'Courier New', monospace" font-size="11" fill="#FCE7F3">Jammu, India</text>
  <text x="136" y="208" font-family="'Courier New', monospace" font-size="11" fill="#39FF88">Creating &amp; Learning</text>

  <!-- Blinking cursor after STATUS value -->
  <text class="cursor" x="284" y="208"
    font-family="'Courier New', monospace"
    font-size="11" fill="#39FF88">_</text>
</svg>
</div>

<br/>

Hey, I'm **Harshit**, but you can call me Hari.

I'm a Computer Science student, Python developer and designer who enjoys bringing ideas to life.

I spend my time between Python applications, automation, web technologies, security experiments and visual design.

I love understanding how things work, breaking complex ideas into smaller pieces, and turning those pieces into something useful.

**My world has two sides:**

- `LOGIC.exe` — Programming, automation, problem-solving and technology.
- `CREATIVITY.exe` — Graphic design, typography, interfaces and visual storytelling.

And somewhere between the two, I keep creating.

---

<div align="center">

### ◈ 01 — THE DEVELOPER'S WORKBENCH ◈

*Every language is a different way to express an idea.*

</div>

### 🐍 Python — My primary playground

Python is where I enjoy experimenting, developing and solving problems.

| Area | What I've explored |
|---|---|
| GUI Development | Tkinter |
| Graphics & Animation | Turtle |
| Browser Automation | Selenium |
| Web Scraping | BeautifulSoup |
| Data Analysis | Pandas |
| Numerical Computing | NumPy |
| Programming Concepts | OOP, functions, exception handling |

<div align="center">

<img src="https://img.shields.io/badge/PYTHON-0B0718?style=for-the-badge&logo=python&logoColor=F57799"/>
<img src="https://img.shields.io/badge/TKINTER-0B0718?style=for-the-badge&logo=python&logoColor=BB8CFF"/>
<img src="https://img.shields.io/badge/SELENIUM-0B0718?style=for-the-badge&logo=selenium&logoColor=43B02A"/>
<img src="https://img.shields.io/badge/BEAUTIFULSOUP-0B0718?style=for-the-badge&logoColor=F57799"/>
<img src="https://img.shields.io/badge/PANDAS-0B0718?style=for-the-badge&logo=pandas&logoColor=BB8CFF"/>
<img src="https://img.shields.io/badge/NUMPY-0B0718?style=for-the-badge&logo=numpy&logoColor=4DABCF"/>

</div>

<br/>

### ☕ Other programming languages

<div align="center">

<img src="https://skillicons.dev/icons?i=java,c,html,css,js&theme=dark"/>

</div>

<br/>

Java currently has a special place on my workbench.

**Current focus:** Data Structures & Algorithms with Java.

---

<div align="center">

### ◈ 02 — THE SECURITY UNDERGROUND ◈

*Curiosity is the first step towards understanding security.*

<br/>

<img src="https://img.shields.io/badge/ACCESS-RESEARCH_MODE-39FF88?style=for-the-badge&labelColor=0B0718"/>

</div>

<br/>

I enjoy exploring how networks, operating systems and web applications work beneath the surface.

**My security toolkit**

<div align="center">

<img src="https://img.shields.io/badge/KALI_LINUX-0B0718?style=for-the-badge&logo=kalilinux&logoColor=557C94"/>
<img src="https://img.shields.io/badge/NMAP-0B0718?style=for-the-badge&logoColor=4682B4"/>
<img src="https://img.shields.io/badge/BURP_SUITE-0B0718?style=for-the-badge&logo=burpsuite&logoColor=FF6633"/>
<img src="https://img.shields.io/badge/OWASP_TOP_10-0B0718?style=for-the-badge&logo=owasp&logoColor=39FF88"/>

</div>

<br/>

Things I explore:

- Network discovery and scanning using Nmap.
- Web application security testing with Burp Suite.
- OWASP Top 10 vulnerabilities and security concepts.
- Linux environments and Kali Linux.
- Ethical hacking fundamentals and security awareness.

*Understand the system. Find the weakness. Learn how to protect it.*

---

<div align="center">

### ◈ 03 — THE CREATIVE STUDIO ◈

*Code can build a website. Design makes someone want to stay.*

</div>

<br/>

This is the part of me that doesn't want everything to look like a typical developer project.

I enjoy designing experiences, experimenting with layouts and making information visually interesting.

**What I create:**

| Creative field | My interests |
|---|---|
| Graphic Design | College posters, promotional graphics |
| Typography | Font combinations, hierarchy, visual rhythm |
| Colour Theory | Palettes, contrast, composition |
| Web Design | Website layouts and visual identity |
| UI/UX | User flows, usability and interface design |
| Visual Storytelling | Creative concepts and digital experiences |

<div align="center">

<img src="https://skillicons.dev/icons?i=figma,canva,gimp,html,css&theme=dark"/>

<br/><br/>

<img src="https://img.shields.io/badge/DESIGN-WITH_INTENTION-F57799?style=for-the-badge&labelColor=0B0718"/>
<img src="https://img.shields.io/badge/CREATE-WITH_EMOTION-BB8CFF?style=for-the-badge&labelColor=0B0718"/>

</div>

<br/>

I believe design isn't decoration.

It's the art of making something understandable, memorable and enjoyable.

---

<div align="center">

### ◈ 04 — EXPERIMENTS & CREATIONS ◈

*Ideas are only interesting until you build them.*

</div>

<br/>

**01 — Harshya.in**

<sup>INDEPENDENT WEB PROJECT · DIGITAL EXPERIENCE</sup>

A project where I'm exploring modern website development, professional design, user experience and digital identity.

[↗ Visit Harshya.in](https://harshya.in)

---

**02 — Badyal Portfolio**

<sup>PERSONAL WEBSITE · CREATIVE IDENTITY</sup>

My personal space on the internet, representing my work, creativity and developer journey.

[↗ Explore my portfolio](https://badyal.netlify.app)

---

**03 — Python Playground**

<sup>PYTHON · APPLICATIONS · EXPERIMENTS</sup>

A collection of programming experiments and practical projects, including:

- Python Quiz Application
- Turtle Graphics & Pattern Generator
- Sweet Shop Management Application
- Python learning projects

[↗ Explore my repositories](https://github.com/Hariii01?tab=repositories)

---

**04 — Security Experiments**

<sup>LINUX · NETWORKING · WEB SECURITY</sup>

Learning through security tools, practical environments and cybersecurity experiments.

[↗ Explore my GitHub](https://github.com/Hariii01)

---

<div align="center">

### ◈ 05 — THE PROBLEM-SOLVING ARENA ◈

*Every problem is a puzzle. Every solution is progress.*

<br/>

[![LeetCode](https://img.shields.io/badge/LEETCODE-dear__harshit__01-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0B0718)](https://leetcode.com/u/dear_harshit_01/)
[![GFG](https://img.shields.io/badge/GEEKSFORGEEKS-harshit1eeyd-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white&labelColor=0B0718)](https://www.geeksforgeeks.org/user/harshit1eeyd/)

</div>

<br/>

### 🧩 Where logic meets persistence

I'm currently strengthening my problem-solving skills, focusing on Data Structures & Algorithms using Java.

<div align="center">

<a href="https://leetcode.com/u/dear_harshit_01/">
<img src="https://leetcard.jacoblin.cool/dear_harshit_01?theme=dark&font=Fira%20Code&ext=heatmap&border=0&radius=8" width="96%"/>
</a>

<br/><br/>

<a href="https://www.geeksforgeeks.org/user/harshit1eeyd/">
<img src="https://img.shields.io/badge/GeeksforGeeks-Explore_My_Profile-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white&labelColor=0B0718"/>
</a>
&nbsp;
<a href="https://leetcode.com/u/dear_harshit_01/">
<img src="https://img.shields.io/badge/LeetCode-Explore_My_Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0B0718"/>
</a>

</div>

<br/>

**Current mission:** Think better, write cleaner solutions, and become a stronger problem solver.

---

<br/>

*The best version of yourself is always under development.*

<br/>

```python
current_quest = {
    "learning": [
        "Data Structures & Algorithms",
        "Java",
        "Advanced Python",
        "Problem Solving"
    ],

    "exploring": [
        "Automation",
        "Web Development",
        "Cybersecurity",
        "UI/UX Design"
    ],

    "building": [
        "Meaningful Projects",
        "Creative Interfaces",
        "Better Digital Experiences"
    ],

    "mission": "Never stop creating."
}
```

---

<div align="center">

### ◈ 06 — THE DIGITAL FOOTPRINT ◈

*Every contribution is a little piece of the journey.*

<br/>

<img width="48%" src="https://github-readme-stats.vercel.app/api?username=Hariii01&show_icons=true&theme=tokyonight&bg_color=0B0718&title_color=F57799&icon_color=BB8CFF&text_color=FCE7F3&border_color=2D1142&rank_icon=github&border_radius=8"/>
<img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hariii01&layout=compact&theme=tokyonight&bg_color=0B0718&title_color=F57799&text_color=FCE7F3&border_color=2D1142&border_radius=8"/>

<br/><br/>

<img width="96%" src="https://streak-stats.demolab.com?user=Hariii01&theme=tokyonight&background=0B0718&ring=F57799&fire=FF6B9D&currStreakLabel=BB8CFF&sideLabels=F57799&border=2D1142&border_radius=8"/>

</div>

---

<div align="center">

### ◈ 07 — A LETTER FROM THE CREATOR ◈

<br/>

<img width="68%" src="https://capsule-render.vercel.app/api?type=blur&color=0:21132E,40:38204D,80:2D1142,100:0B0718&height=120&section=header&text=Stay%20curious.%20Stay%20creative.&fontSize=24&fontColor=FCE7F3&animation=fadeIn"/>

<br/><br/>

</div>

I don't want to be someone who simply knows how to use technology.

I want to understand it, experiment with it, challenge it and create something of my own.

I write code with logic, approach design with emotion, and believe that even the smallest details deserve attention.

**Because why should technology be functional only, when it can be beautiful too?**

<br/>

<div align="center">

### FIND ME IN MY LITTLE CORNER OF THE INTERNET

<br/>

[![GitHub](https://img.shields.io/badge/GITHUB-Hariii01-FCE7F3?style=for-the-badge&logo=github&labelColor=0B0718)](https://github.com/Hariii01)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-dear__harshit__01-E4405F?style=for-the-badge&logo=instagram&labelColor=0B0718)](https://instagram.com/dear_harshit_01)
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-BADYAL.NETLIFY.APP-F57799?style=for-the-badge&logo=googlechrome&labelColor=0B0718)](https://badyal.netlify.app)
[![Harshya](https://img.shields.io/badge/PROJECT-HARSHYA.IN-BB8CFF?style=for-the-badge&logo=googlechrome&labelColor=0B0718)](https://harshya.in)

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Hariii01&label=SOULS+WHO+VISITED&color=F57799&style=for-the-badge&labelColor=0B0718"/>

<br/><br/>

*Made with logic, designed with love, and powered by curiosity.*

**— Harshit Badyal ♡**

<br/>

<!-- ═══════ HEARTBEAT FOOTER SVG — the signature ═══════ -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 72" width="100%">
  <defs>
    <!-- Left-to-right gradient for the pulse line -->
    <linearGradient id="pulse-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#0B0718"/>
      <stop offset="20%"  stop-color="#BB8CFF" stop-opacity="0.7"/>
      <stop offset="45%"  stop-color="#F57799" stop-opacity="0.9"/>
      <stop offset="55%"  stop-color="#F57799" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#BB8CFF" stop-opacity="0.7"/>
      <stop offset="100%" stop-color="#0B0718"/>
    </linearGradient>
    <!-- Glow for the pulse -->
    <filter id="pulse-glow" x="-5%" y="-200%" width="110%" height="500%">
      <feGaussianBlur stdDeviation="2.2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Glow for the nodes -->
    <filter id="node-glow" x="-200%" y="-200%" width="500%" height="500%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="72" fill="#0B0718"/>

  <!-- The heartbeat/ECG line — this is the signature of the entire profile -->
  <!-- Flat → first spike → flat → main spike (tall) → flat → second spike → flat → end -->
  <polyline
    points="
      0,36
      60,36
      80,36
      95,14
      110,58
      125,36
      145,36
      165,36
      183,22
      193,50
      203,36
      225,36
      280,36
      298,20
      308,52
      318,36
      340,36
      400,36
      418,16
      428,56
      438,36
      460,36
      520,36
      538,22
      548,50
      558,36
      580,36
      640,36
      658,10
      670,62
      682,36
      705,36
      760,36
      778,20
      788,52
      798,36
      820,36
      900,36
    "
    fill="none"
    stroke="url(#pulse-grad)"
    stroke-width="1.8"
    stroke-linecap="round"
    stroke-linejoin="round"
    filter="url(#pulse-glow)"
    opacity="0.95"
  />

  <!-- Circuit nodes at the peak points — violet -->
  <circle cx="95"  cy="14" r="2.2" fill="#BB8CFF" filter="url(#node-glow)" opacity="0.9"/>
  <circle cx="110" cy="58" r="2.2" fill="#BB8CFF" filter="url(#node-glow)" opacity="0.9"/>
  <!-- Main tall spike — rose -->
  <circle cx="658" cy="10" r="3"   fill="#F57799" filter="url(#node-glow)" opacity="1"/>
  <circle cx="670" cy="62" r="3"   fill="#F57799" filter="url(#node-glow)" opacity="1"/>
  <!-- Mid nodes — alternating -->
  <circle cx="298" cy="20" r="2"   fill="#BB8CFF" filter="url(#node-glow)" opacity="0.8"/>
  <circle cx="308" cy="52" r="2"   fill="#BB8CFF" filter="url(#node-glow)" opacity="0.8"/>
  <circle cx="418" cy="16" r="2"   fill="#F57799" filter="url(#node-glow)" opacity="0.8"/>
  <circle cx="428" cy="56" r="2"   fill="#F57799" filter="url(#node-glow)" opacity="0.8"/>
  <circle cx="778" cy="20" r="2"   fill="#BB8CFF" filter="url(#node-glow)" opacity="0.8"/>
  <circle cx="788" cy="52" r="2"   fill="#BB8CFF" filter="url(#node-glow)" opacity="0.8"/>

  <!-- Flat connector dots between spikes — very subtle -->
  <circle cx="165" cy="36" r="1.2" fill="#6B5A80" opacity="0.4"/>
  <circle cx="340" cy="36" r="1.2" fill="#6B5A80" opacity="0.4"/>
  <circle cx="520" cy="36" r="1.2" fill="#6B5A80" opacity="0.4"/>
  <circle cx="705" cy="36" r="1.2" fill="#6B5A80" opacity="0.4"/>

  <!-- Bottom fade strip -->
  <rect x="0" y="58" width="900" height="14" fill="#0B0718"/>
</svg>

</div>
