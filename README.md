<!-- ═══════════════════════════════════════════════════════════════ -->
<!--              ANIMATED HEADER - BUBBLES 3D + TEXT              -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="900" height="350" viewBox="0 0 900 350" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background -->
    <linearGradient id="bg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#080b12"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>

    <!-- Bubble gradients 3D - Red/Coral -->
    <radialGradient id="b1" cx="35%" cy="32%" r="65%">
      <stop offset="0%" stop-color="#ff9e95"/>
      <stop offset="30%" stop-color="#e85d52"/>
      <stop offset="70%" stop-color="#c03228"/>
      <stop offset="100%" stop-color="#7a1a12"/>
    </radialGradient>
    <radialGradient id="shine1" cx="30%" cy="28%" r="45%">
      <stop offset="0%" stop-color="rgba(255,255,255,0.7)"/>
      <stop offset="100%" stop-color="rgba(255,255,255,0)"/>
    </radialGradient>

    <!-- Bubble gradients - Blue -->
    <radialGradient id="b2" cx="35%" cy="32%" r="65%">
      <stop offset="0%" stop-color="#8abfff"/>
      <stop offset="30%" stop-color="#4a90e8"/>
      <stop offset="70%" stop-color="#2560b5"/>
      <stop offset="100%" stop-color="#0e3470"/>
    </radialGradient>
    <radialGradient id="shine2" cx="30%" cy="28%" r="45%">
      <stop offset="0%" stop-color="rgba(255,255,255,0.65)"/>
      <stop offset="100%" stop-color="rgba(255,255,255,0)"/>
    </radialGradient>

    <!-- Bubble gradients - Purple -->
    <radialGradient id="b3" cx="35%" cy="32%" r="65%">
      <stop offset="0%" stop-color="#d09bff"/>
      <stop offset="30%" stop-color="#9b5de5"/>
      <stop offset="70%" stop-color="#6b2fb0"/>
      <stop offset="100%" stop-color="#3d1270"/>
    </radialGradient>
    <radialGradient id="shine3" cx="30%" cy="28%" r="45%">
      <stop offset="0%" stop-color="rgba(255,255,255,0.6)"/>
      <stop offset="100%" stop-color="rgba(255,255,255,0)"/>
    </radialGradient>

    <!-- Bubble gradients - Cyan -->
    <radialGradient id="b4" cx="35%" cy="32%" r="65%">
      <stop offset="0%" stop-color="#90efff"/>
      <stop offset="30%" stop-color="#30c5de"/>
      <stop offset="70%" stop-color="#1090aa"/>
      <stop offset="100%" stop-color="#055068"/>
    </radialGradient>
    <radialGradient id="shine4" cx="30%" cy="28%" r="45%">
      <stop offset="0%" stop-color="rgba(255,255,255,0.65)"/>
      <stop offset="100%" stop-color="rgba(255,255,255,0)"/>
    </radialGradient>

    <!-- Bubble gradients - Orange -->
    <radialGradient id="b5" cx="35%" cy="32%" r="65%">
      <stop offset="0%" stop-color="#ffb87a"/>
      <stop offset="30%" stop-color="#e8822a"/>
      <stop offset="70%" stop-color="#c05810"/>
      <stop offset="100%" stop-color="#7a3005"/>
    </radialGradient>
    <radialGradient id="shine5" cx="30%" cy="28%" r="45%">
      <stop offset="0%" stop-color="rgba(255,255,255,0.65)"/>
      <stop offset="100%" stop-color="rgba(255,255,255,0)"/>
    </radialGradient>

    <!-- Bubble gradients - Small teal -->
    <radialGradient id="b6" cx="35%" cy="32%" r="65%">
      <stop offset="0%" stop-color="#70ffde"/>
      <stop offset="30%" stop-color="#20c99a"/>
      <stop offset="70%" stop-color="#0a9070"/>
      <stop offset="100%" stop-color="#024d3c"/>
    </radialGradient>
    <radialGradient id="shine6" cx="30%" cy="28%" r="45%">
      <stop offset="0%" stop-color="rgba(255,255,255,0.6)"/>
      <stop offset="100%" stop-color="rgba(255,255,255,0)"/>
    </radialGradient>

    <!-- Bubble gradients - Rose/Pink -->
    <radialGradient id="b7" cx="35%" cy="32%" r="65%">
      <stop offset="0%" stop-color="#ffa8d5"/>
      <stop offset="30%" stop-color="#e0569a"/>
      <stop offset="70%" stop-color="#b02870"/>
      <stop offset="100%" stop-color="#6a0d40"/>
    </radialGradient>
    <radialGradient id="shine7" cx="30%" cy="28%" r="45%">
      <stop offset="0%" stop-color="rgba(255,255,255,0.65)"/>
      <stop offset="100%" stop-color="rgba(255,255,255,0)"/>
    </radialGradient>

    <!-- Glow filter for text -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Soft glow for bubbles -->
    <filter id="bubbleGlow" x="-15%" y="-15%" width="130%" height="130%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Clip -->
    <clipPath id="clip"><rect width="900" height="350"/></clipPath>
  </defs>

  <rect width="900" height="350" fill="url(#bg)"/>

  <!-- ─── BUBBLES GROUP ─── -->
  <g clip-path="url(#clip)" filter="url(#bubbleGlow)">

    <!-- BUBBLE 1 - Large red, center-left, bouncing horizontally -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; 38,12; 70,−8; 40,20; 0,0"
        dur="9s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="200" cy="175" r="52" fill="url(#b1)" opacity="0.92"/>
      <circle cx="200" cy="175" r="52" fill="url(#shine1)"/>
      <circle cx="200" cy="175" r="52" fill="none" stroke="rgba(255,160,150,0.3)" stroke-width="1.5"/>
    </g>

    <!-- BUBBLE 2 - Medium blue, top area -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; −20,18; −45,−10; −22,28; 0,0"
        dur="7.5s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="680" cy="80" r="38" fill="url(#b2)" opacity="0.9"/>
      <circle cx="680" cy="80" r="38" fill="url(#shine2)"/>
      <circle cx="680" cy="80" r="38" fill="none" stroke="rgba(100,160,255,0.3)" stroke-width="1.5"/>
    </g>

    <!-- BUBBLE 3 - Purple, right side -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; −30,−15; −55,10; −28,−25; 0,0"
        dur="11s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="820" cy="220" r="48" fill="url(#b3)" opacity="0.88"/>
      <circle cx="820" cy="220" r="48" fill="url(#shine3)"/>
      <circle cx="820" cy="220" r="48" fill="none" stroke="rgba(180,120,255,0.3)" stroke-width="1.5"/>
    </g>

    <!-- BUBBLE 4 - Cyan, bottom-left -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; 25,−20; 50,5; 30,−30; 0,0"
        dur="8.5s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="80" cy="280" r="42" fill="url(#b4)" opacity="0.88"/>
      <circle cx="80" cy="280" r="42" fill="url(#shine4)"/>
      <circle cx="80" cy="280" r="42" fill="none" stroke="rgba(60,200,225,0.3)" stroke-width="1.5"/>
    </g>

    <!-- BUBBLE 5 - Orange, top-left -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; 15,30; 35,−5; 18,42; 0,0"
        dur="10s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="100" cy="70" r="35" fill="url(#b5)" opacity="0.9"/>
      <circle cx="100" cy="70" r="35" fill="url(#shine5)"/>
      <circle cx="100" cy="70" r="35" fill="none" stroke="rgba(255,170,80,0.3)" stroke-width="1.5"/>
    </g>

    <!-- BUBBLE 6 - Small teal, right-bottom -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; −18,−22; −38,8; −20,−35; 0,0"
        dur="6.5s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="750" cy="310" r="28" fill="url(#b6)" opacity="0.85"/>
      <circle cx="750" cy="310" r="28" fill="url(#shine6)"/>
      <circle cx="750" cy="310" r="28" fill="none" stroke="rgba(50,210,160,0.3)" stroke-width="1.5"/>
    </g>

    <!-- BUBBLE 7 - Rose/Pink small, top center -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; 28,15; 5,35; −18,12; 0,0"
        dur="7s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="430" cy="45" r="24" fill="url(#b7)" opacity="0.85"/>
      <circle cx="430" cy="45" r="24" fill="url(#shine7)"/>
      <circle cx="430" cy="45" r="24" fill="none" stroke="rgba(240,120,180,0.3)" stroke-width="1.5"/>
    </g>

    <!-- BUBBLE 8 - Medium blue-ish, center right, collides with bubble 1 -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; −60,−8; −100,5; −65,−15; 0,0"
        dur="8s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="370" cy="190" r="33" fill="url(#b2)" opacity="0.82"/>
      <circle cx="370" cy="190" r="33" fill="url(#shine2)"/>
      <circle cx="370" cy="190" r="33" fill="none" stroke="rgba(100,160,255,0.25)" stroke-width="1.5"/>
    </g>

    <!-- BUBBLE 9 - Tiny red, bottom center -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; 22,−18; 40,10; 25,−28; 0,0"
        dur="5.5s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="540" cy="315" r="20" fill="url(#b1)" opacity="0.8"/>
      <circle cx="540" cy="315" r="20" fill="url(#shine1)"/>
    </g>

    <!-- BUBBLE 10 - Tiny purple, left middle -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; 12,25; 30,−10; 15,38; 0,0"
        dur="9.5s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="50" cy="160" r="18" fill="url(#b3)" opacity="0.78"/>
      <circle cx="50" cy="160" r="18" fill="url(#shine3)"/>
    </g>

    <!-- BUBBLE 11 - Medium orange, far right middle -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; −25,20; −48,−8; −28,32; 0,0"
        dur="12s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="875" cy="140" r="30" fill="url(#b5)" opacity="0.85"/>
      <circle cx="875" cy="140" r="30" fill="url(#shine5)"/>
      <circle cx="875" cy="140" r="30" fill="none" stroke="rgba(255,170,80,0.25)" stroke-width="1.5"/>
    </g>

    <!-- BUBBLE 12 - Small cyan, top right -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; −15,22; −30,−5; −18,35; 0,0"
        dur="6s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="820" cy="45" r="22" fill="url(#b4)" opacity="0.82"/>
      <circle cx="820" cy="45" r="22" fill="url(#shine4)"/>
    </g>

    <!-- BUBBLE 13 - Small teal, between center -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; 32,−12; 58,18; 35,−22; 0,0"
        dur="10.5s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="310" cy="55" r="26" fill="url(#b6)" opacity="0.8"/>
      <circle cx="310" cy="55" r="26" fill="url(#shine6)"/>
    </g>

    <!-- BUBBLE 14 - Tiny rose, scattered -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; −10,−28; −25,12; −12,−40; 0,0"
        dur="7.8s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="620" cy="270" r="16" fill="url(#b7)" opacity="0.75"/>
      <circle cx="620" cy="270" r="16" fill="url(#shine7)"/>
    </g>

    <!-- BUBBLE 15 - Medium red scattered -->
    <g>
      <animateTransform attributeName="transform" type="translate"
        values="0,0; 20,−35; 45,5; 22,−50; 0,0"
        dur="13s" repeatCount="indefinite" calcMode="spline"
        keySplines="0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1; 0.4 0 0.6 1"/>
      <circle cx="480" cy="295" r="32" fill="url(#b1)" opacity="0.82"/>
      <circle cx="480" cy="295" r="32" fill="url(#shine1)"/>
      <circle cx="480" cy="295" r="32" fill="none" stroke="rgba(255,140,130,0.25)" stroke-width="1.5"/>
    </g>

  </g>
  <!-- ─── END BUBBLES ─── -->

  <!-- ─── TEXT LAYER ─── -->

  <!-- GERALD VARGAS - main title with reveal animation -->
  <text x="450" y="168"
    font-family="'Arial Black', 'Impact', 'Haettenschweiler', sans-serif"
    font-size="76" font-weight="900" text-anchor="middle"
    letter-spacing="3" filter="url(#glow)">
    <tspan fill="#ffffff">GERALD VARGAS</tspan>
    <animate attributeName="opacity" values="0;0;1" keyTimes="0;0.15;0.35" dur="4s" fill="freeze"/>
    <animate attributeName="font-size" values="60;80;76" keyTimes="0;0.15;0.35" dur="4s" fill="freeze"/>
  </text>

  <!-- Subtitle 1: Informatic Engineer -->
  <text x="248" y="212"
    font-family="'Georgia', 'Palatino Linotype', serif"
    font-size="18" font-weight="700" font-style="italic"
    text-anchor="middle" fill="#ff7b6e" letter-spacing="1.5">
    Informatic Engineer
    <animate attributeName="opacity" values="0;0;0;1" keyTimes="0;0;0.45;0.65" dur="6s" fill="freeze"/>
    <animate attributeName="y" values="220;212" keyTimes="0.45;0.65" dur="6s" fill="freeze"/>
  </text>

  <!-- Divider 1 -->
  <text x="370" y="212"
    font-family="sans-serif" font-size="18" text-anchor="middle"
    fill="rgba(255,255,255,0.25)">
    |
    <animate attributeName="opacity" values="0;0;0;1" keyTimes="0;0;0.55;0.7" dur="6s" fill="freeze"/>
  </text>

  <!-- Subtitle 2: Full Stack Developer -->
  <text x="505" y="212"
    font-family="'Georgia', 'Palatino Linotype', serif"
    font-size="18" font-weight="700" font-style="italic"
    text-anchor="middle" fill="#6eb8ff" letter-spacing="1.5">
    Full Stack Developer
    <animate attributeName="opacity" values="0;0;0;1" keyTimes="0;0;0.6;0.8" dur="6s" fill="freeze"/>
    <animate attributeName="y" values="220;212" keyTimes="0.6;0.8" dur="6s" fill="freeze"/>
  </text>

  <!-- Divider 2 -->
  <text x="630" y="212"
    font-family="sans-serif" font-size="18" text-anchor="middle"
    fill="rgba(255,255,255,0.25)">
    |
    <animate attributeName="opacity" values="0;0;0;1" keyTimes="0;0;0.7;0.85" dur="6s" fill="freeze"/>
  </text>

  <!-- Subtitle 3: AI Enthusiast -->
  <text x="718" y="212"
    font-family="'Georgia', 'Palatino Linotype', serif"
    font-size="18" font-weight="700" font-style="italic"
    text-anchor="middle" fill="#b06eff" letter-spacing="1.5">
    AI Enthusiast
    <animate attributeName="opacity" values="0;0;0;1" keyTimes="0;0;0.75;0.95" dur="6s" fill="freeze"/>
    <animate attributeName="y" values="220;212" keyTimes="0.75;0.95" dur="6s" fill="freeze"/>
  </text>

  <!-- Bottom accent line -->
  <line x1="0" y1="348" x2="900" y2="348" stroke="url(#lineGrad)" stroke-width="2"/>
  <defs>
    <linearGradient id="lineGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ff7b6e" stop-opacity="0"/>
      <stop offset="30%" stop-color="#ff7b6e"/>
      <stop offset="50%" stop-color="#6eb8ff"/>
      <stop offset="70%" stop-color="#b06eff"/>
      <stop offset="100%" stop-color="#b06eff" stop-opacity="0"/>
    </linearGradient>
  </defs>

</svg>

</div>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- About Section with Computer GIF -->
<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">About Me</h3>

<img align="center" src="https://media.giphy.com/media/ao9DUiTKH60XS/giphy.gif" width="100%"/>

</td>
<td width="50%" valign="top">

<br>

```javascript
const gerald = {
    role: "Full Stack Developer",
    location: "Cochabamba, Bolivia",
    university: "UMSS",
    skills: ["Laravel", "Flutter", "React",
             "Python", "Node.js", "AI/ML"],
    currentWork: "Electoral Systems",
    passion: "Building Smart Solutions",
    contact: "202405633@est.umss.edu"
};
```

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=00FFFF&center=true&vCenter=true&width=400&lines=Full+Stack+Developer;Data+Analyst;AI+%26+ML+Engineer;n8n+Automation+Expert" alt="Roles" />
</p>

</td>
</tr>
</table>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Snake Animation (sin título) -->
<div align="center">
  <img src="https://raw.githubusercontent.com/GeraldVargas/GeraldVargas/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</div>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Tech Stack Section -->
<h3 align="center">Tech Stack</h3>

<!-- Animated Tech Icons -->
<div align="center">
  <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="icon" width="65" height="65" />
  <img src="https://techstack-generator.vercel.app/java-icon.svg" alt="icon" width="65" height="65" />
  <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="65" height="65" />
  <img src="https://techstack-generator.vercel.app/ts-icon.svg" alt="icon" width="65" height="65" />
  <img src="https://techstack-generator.vercel.app/react-icon.svg" alt="icon" width="65" height="65" />
  <img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="icon" width="65" height="65" />
</div>

<br>

<div align="center">
  <img src="https://techstack-generator.vercel.app/cpp-icon.svg" alt="icon" width="65" height="65" />
  <img src="https://techstack-generator.vercel.app/docker-icon.svg" alt="icon" width="65" height="65" />
  <img src="https://techstack-generator.vercel.app/github-icon.svg" alt="icon" width="65" height="65" />
  <img src="https://techstack-generator.vercel.app/restapi-icon.svg" alt="icon" width="65" height="65" />
  <img src="https://techstack-generator.vercel.app/nginx-icon.svg" alt="icon" width="65" height="65" />
</div>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Languages and Tools -->
<h3 align="center">Languages and Tools</h3>

<h4 align="center">Backend</h4>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,java,php,laravel,nodejs,express,haskell,cpp" />
  </a>
</p>

<h4 align="center">Frontend</h4>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,flutter,js,html,css,tailwind" />
  </a>
</p>

<h4 align="center">Data Science & ML</h4>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=tensorflow,pytorch,anaconda" />
  </a>
</p>

<h4 align="center">Database</h4>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=mysql,postgresql,mongodb,sqlite" />
  </a>
</p>

<h4 align="center">Tools</h4>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,github,docker,vscode,linux,figma,postman" />
  </a>
</p>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Achievements -->
<h3 align="center">Achievements</h3>

<div align="center">

| | Achievement | Description |
|:---:|:---|:---|
| :trophy: | **ICPC Cochabamba** | Rank #18 (First competition) |
| :mortar_board: | **Electoral System** | Curricular Value Certification |
| :robot: | **n8n Automation** | +6,500 automated records |
| :brain: | **Deep Learning** | 94.2% accuracy fraud detection |

</div>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Experience -->
<h3 align="center">Professional Experience</h3>

<table align="center">
<tr>
<td width="33%" align="center">

**Backend Developer**

Electoral Ballot System

*Colcapirhua 2026*

`Laravel 12` `APIs` `Security`

</td>
<td width="33%" align="center">

**Full Stack Developer**

Electoral System

*Cochabamba 2025-2026*

`React` `Node.js` `Express`

</td>
<td width="33%" align="center">

**Internship**

Municipal Government

*Colcapirhua 2026*

`Flutter` `Laravel 11`

</td>
</tr>
</table>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- GitHub Stats -->
<h3 align="center">GitHub Stats</h3>

<div align="center">

![Gerald's GitHub stats](https://github-readme-stats.vercel.app/api?username=GeraldVargas&theme=tokyonight&show_icons=true&count_private=true&hide_border=true&bg_color=0D1117)

[![GitHub Streak](https://streak-stats.demolab.com/?user=GeraldVargas&theme=tokyonight&hide_border=true&background=0D1117)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=GeraldVargas&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=10)](https://github.com/GeraldVargas)

</div>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Activity Graph -->
<h3 align="center">Activity Graph</h3>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=GeraldVargas&custom_title=Gerald%20Vargas%20-%20Contribution%20Graph&bg_color=0d1117&color=00d9ff&line=00d9ff&point=FFFFFF&area_color=00d9ff&title_color=FFFFFF&area=true&hide_border=true" alt="Contribution Graph" width="100%"/>
</div>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Connect -->
<h3 align="center">Connect With Me</h3>

<p align="center">
<a href="mailto:202405633@est.umss.edu">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/gerald-emanuel-vargas-morales-42b444">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://github.com/GeraldVargas">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="tel:+59176476507">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
</a>
</p>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

<img src="https://komarev.com/ghpvc/?username=GeraldVargas&color=blueviolet&style=for-the-badge" />

<br><br>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />

</div>

<br>

<!-- Animated Footer Wave -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=footer"/>
</div>