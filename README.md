<!-- Animated 3D Bubbles Header -->
<div align="center">

<!-- SVG Animated Bubbles Background -->
<svg width="100%" height="350" viewBox="0 0 1200 350" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Gradient for bubbles -->
    <radialGradient id="bubble1" cx="30%" cy="30%">
      <stop offset="0%" style="stop-color:#ffffff;stop-opacity:0.8"/>
      <stop offset="50%" style="stop-color:#00d9ff;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#0066ff;stop-opacity:0.4"/>
    </radialGradient>
    <radialGradient id="bubble2" cx="25%" cy="25%">
      <stop offset="0%" style="stop-color:#ffffff;stop-opacity:0.9"/>
      <stop offset="50%" style="stop-color:#ff00ff;stop-opacity:0.5"/>
      <stop offset="100%" style="stop-color:#6600ff;stop-opacity:0.3"/>
    </radialGradient>
    <radialGradient id="bubble3" cx="35%" cy="30%">
      <stop offset="0%" style="stop-color:#ffffff;stop-opacity:0.85"/>
      <stop offset="50%" style="stop-color:#00ffcc;stop-opacity:0.55"/>
      <stop offset="100%" style="stop-color:#0099ff;stop-opacity:0.35"/>
    </radialGradient>
    <radialGradient id="bubble4" cx="28%" cy="28%">
      <stop offset="0%" style="stop-color:#ffffff;stop-opacity:0.9"/>
      <stop offset="50%" style="stop-color:#ff6600;stop-opacity:0.5"/>
      <stop offset="100%" style="stop-color:#ff0066;stop-opacity:0.3"/>
    </radialGradient>
    <radialGradient id="bubble5" cx="32%" cy="32%">
      <stop offset="0%" style="stop-color:#ffffff;stop-opacity:0.88"/>
      <stop offset="50%" style="stop-color:#66ff00;stop-opacity:0.52"/>
      <stop offset="100%" style="stop-color:#00cc99;stop-opacity:0.32"/>
    </radialGradient>

    <!-- Background gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#161b22"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>

    <!-- Glow filter for bubbles -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="100%" height="100%" fill="url(#bgGrad)"/>

  <!-- Animated Bubbles - Multiple sizes floating and moving -->
  <!-- Large bubbles -->
  <circle cx="100" cy="280" r="45" fill="url(#bubble1)" filter="url(#glow)" opacity="0.7">
    <animate attributeName="cy" values="280;80;280" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="100;150;100" dur="12s" repeatCount="indefinite"/>
    <animate attributeName="r" values="45;55;45" dur="4s" repeatCount="indefinite"/>
  </circle>

  <circle cx="300" cy="320" r="55" fill="url(#bubble2)" filter="url(#glow)" opacity="0.65">
    <animate attributeName="cy" values="320;50;320" dur="10s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="300;250;300" dur="14s" repeatCount="indefinite"/>
    <animate attributeName="r" values="55;70;55" dur="5s" repeatCount="indefinite"/>
  </circle>

  <circle cx="500" cy="290" r="40" fill="url(#bubble3)" filter="url(#glow)" opacity="0.75">
    <animate attributeName="cy" values="290;60;290" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="500;550;500" dur="11s" repeatCount="indefinite"/>
    <animate attributeName="r" values="40;50;40" dur="3.5s" repeatCount="indefinite"/>
  </circle>

  <circle cx="700" cy="310" r="60" fill="url(#bubble4)" filter="url(#glow)" opacity="0.6">
    <animate attributeName="cy" values="310;40;310" dur="9s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="700;650;700" dur="13s" repeatCount="indefinite"/>
    <animate attributeName="r" values="60;75;60" dur="4.5s" repeatCount="indefinite"/>
  </circle>

  <circle cx="900" cy="300" r="50" fill="url(#bubble5)" filter="url(#glow)" opacity="0.7">
    <animate attributeName="cy" values="300;70;300" dur="8.5s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="900;950;900" dur="10s" repeatCount="indefinite"/>
    <animate attributeName="r" values="50;62;50" dur="4s" repeatCount="indefinite"/>
  </circle>

  <circle cx="1100" cy="285" r="48" fill="url(#bubble1)" filter="url(#glow)" opacity="0.68">
    <animate attributeName="cy" values="285;75;285" dur="7.5s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="1100;1050;1100" dur="12s" repeatCount="indefinite"/>
    <animate attributeName="r" values="48;58;48" dur="3.8s" repeatCount="indefinite"/>
  </circle>

  <!-- Medium bubbles -->
  <circle cx="150" cy="180" r="30" fill="url(#bubble3)" filter="url(#glow)" opacity="0.6">
    <animate attributeName="cy" values="180;320;180" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="150;200;150" dur="9s" repeatCount="indefinite"/>
    <animate attributeName="r" values="30;38;30" dur="3s" repeatCount="indefinite"/>
  </circle>

  <circle cx="400" cy="120" r="35" fill="url(#bubble4)" filter="url(#glow)" opacity="0.55">
    <animate attributeName="cy" values="120;300;120" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="400;350;400" dur="10s" repeatCount="indefinite"/>
    <animate attributeName="r" values="35;45;35" dur="3.2s" repeatCount="indefinite"/>
  </circle>

  <circle cx="600" cy="150" r="32" fill="url(#bubble5)" filter="url(#glow)" opacity="0.62">
    <animate attributeName="cy" values="150;310;150" dur="6.5s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="600;650;600" dur="8.5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="32;40;32" dur="2.8s" repeatCount="indefinite"/>
  </circle>

  <circle cx="800" cy="100" r="38" fill="url(#bubble1)" filter="url(#glow)" opacity="0.58">
    <animate attributeName="cy" values="100;280;100" dur="7.8s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="800;750;800" dur="11s" repeatCount="indefinite"/>
    <animate attributeName="r" values="38;48;38" dur="3.5s" repeatCount="indefinite"/>
  </circle>

  <circle cx="1000" cy="140" r="33" fill="url(#bubble2)" filter="url(#glow)" opacity="0.63">
    <animate attributeName="cy" values="140;290;140" dur="6.8s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="1000;1050;1000" dur="9.5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="33;42;33" dur="3.1s" repeatCount="indefinite"/>
  </circle>

  <!-- Small bubbles -->
  <circle cx="80" cy="100" r="18" fill="url(#bubble2)" filter="url(#glow)" opacity="0.5">
    <animate attributeName="cy" values="100;250;100" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="80;120;80" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="r" values="18;24;18" dur="2.5s" repeatCount="indefinite"/>
  </circle>

  <circle cx="220" cy="220" r="20" fill="url(#bubble5)" filter="url(#glow)" opacity="0.52">
    <animate attributeName="cy" values="220;80;220" dur="5.5s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="220;180;220" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="r" values="20;26;20" dur="2.2s" repeatCount="indefinite"/>
  </circle>

  <circle cx="350" cy="200" r="22" fill="url(#bubble1)" filter="url(#glow)" opacity="0.48">
    <animate attributeName="cy" values="200;70;200" dur="5.2s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="350;400;350" dur="7.5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="22;28;22" dur="2.8s" repeatCount="indefinite"/>
  </circle>

  <circle cx="550" cy="240" r="19" fill="url(#bubble4)" filter="url(#glow)" opacity="0.53">
    <animate attributeName="cy" values="240;90;240" dur="4.8s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="550;500;550" dur="6.8s" repeatCount="indefinite"/>
    <animate attributeName="r" values="19;25;19" dur="2.4s" repeatCount="indefinite"/>
  </circle>

  <circle cx="750" cy="210" r="21" fill="url(#bubble3)" filter="url(#glow)" opacity="0.5">
    <animate attributeName="cy" values="210;60;210" dur="5.3s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="750;800;750" dur="7.2s" repeatCount="indefinite"/>
    <animate attributeName="r" values="21;27;21" dur="2.6s" repeatCount="indefinite"/>
  </circle>

  <circle cx="950" cy="230" r="23" fill="url(#bubble2)" filter="url(#glow)" opacity="0.51">
    <animate attributeName="cy" values="230;85;230" dur="5.1s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="950;900;950" dur="7.8s" repeatCount="indefinite"/>
    <animate attributeName="r" values="23;29;23" dur="2.3s" repeatCount="indefinite"/>
  </circle>

  <circle cx="1080" cy="200" r="17" fill="url(#bubble5)" filter="url(#glow)" opacity="0.54">
    <animate attributeName="cy" values="200;95;200" dur="4.6s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="1080;1120;1080" dur="6.5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="17;22;17" dur="2.1s" repeatCount="indefinite"/>
  </circle>

  <!-- Extra tiny bubbles for depth -->
  <circle cx="50" cy="50" r="12" fill="url(#bubble3)" filter="url(#glow)" opacity="0.4">
    <animate attributeName="cy" values="50;200;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="50;90;50" dur="6s" repeatCount="indefinite"/>
  </circle>

  <circle cx="180" cy="300" r="14" fill="url(#bubble1)" filter="url(#glow)" opacity="0.42">
    <animate attributeName="cy" values="300;100;300" dur="4.2s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="180;220;180" dur="5.5s" repeatCount="indefinite"/>
  </circle>

  <circle cx="450" cy="50" r="13" fill="url(#bubble4)" filter="url(#glow)" opacity="0.38">
    <animate attributeName="cy" values="50;250;50" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="450;480;450" dur="6.2s" repeatCount="indefinite"/>
  </circle>

  <circle cx="650" cy="320" r="15" fill="url(#bubble2)" filter="url(#glow)" opacity="0.44">
    <animate attributeName="cy" values="320;80;320" dur="4.8s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="650;620;650" dur="5.8s" repeatCount="indefinite"/>
  </circle>

  <circle cx="850" cy="40" r="11" fill="url(#bubble5)" filter="url(#glow)" opacity="0.36">
    <animate attributeName="cy" values="40;220;40" dur="3.8s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="850;880;850" dur="5.2s" repeatCount="indefinite"/>
  </circle>

  <circle cx="1050" cy="310" r="16" fill="url(#bubble3)" filter="url(#glow)" opacity="0.45">
    <animate attributeName="cy" values="310;90;310" dur="4.3s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="1050;1020;1050" dur="6.5s" repeatCount="indefinite"/>
  </circle>

  <!-- Main Title with glow effect -->
  <text x="600" y="140" text-anchor="middle" fill="#ffffff" font-size="72" font-family="'Segoe UI', Arial, sans-serif" font-weight="bold" filter="url(#glow)">
    GERALD VARGAS
    <animate attributeName="opacity" values="0;1" dur="2s" fill="freeze"/>
  </text>

  <!-- Subtitle with typing effect simulation -->
  <text x="600" y="200" text-anchor="middle" fill="#00d9ff" font-size="24" font-family="'Segoe UI', Arial, sans-serif" font-weight="300">
    <animate attributeName="opacity" values="0;0;1" dur="3s" fill="freeze"/>
    Informatic Engineer
  </text>

  <text x="600" y="235" text-anchor="middle" fill="#ff00ff" font-size="22" font-family="'Segoe UI', Arial, sans-serif" font-weight="300">
    <animate attributeName="opacity" values="0;0;0;1" dur="4s" fill="freeze"/>
    Full Stack Developer
  </text>

  <text x="600" y="270" text-anchor="middle" fill="#00ffcc" font-size="22" font-family="'Segoe UI', Arial, sans-serif" font-weight="300">
    <animate attributeName="opacity" values="0;0;0;0;1" dur="5s" fill="freeze"/>
    AI Enthusiast
  </text>
</svg>

</div>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- About Section with Computer GIF -->
<table>
<tr>
<td width="50%" valign="top">

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
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=700&size=24&duration=1500&pause=500&color=00FFFF&center=true&vCenter=true&width=450&lines=Full+Stack+Developer;Data+Analyst;AI+%26+ML+Engineer;n8n+Automation+Expert" alt="Roles" />
</p>

</td>
</tr>
</table>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Snake Section -->
<div align="center">
  <img src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</div>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Tech Stack Section -->
<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Righteous&weight=600&size=35&duration=2000&pause=800&color=00D9FF&center=true&vCenter=true&width=500&lines=Tech+Stack" alt="Tech Stack" />
</h3>

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
<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Righteous&weight=600&size=35&duration=2000&pause=800&color=FF00FF&center=true&vCenter=true&width=500&lines=Languages+and+Tools" alt="Languages and Tools" />
</h3>

<h4 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=1500&pause=500&color=FFFFFF&center=true&vCenter=true&width=200&lines=Backend" alt="Backend" />
</h4>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,java,php,laravel,nodejs,express,haskell,cpp" />
  </a>
</p>

<h4 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=1500&pause=500&color=FFFFFF&center=true&vCenter=true&width=200&lines=Frontend" alt="Frontend" />
</h4>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,flutter,js,html,css,tailwind" />
  </a>
</p>

<h4 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=1500&pause=500&color=FFFFFF&center=true&vCenter=true&width=250&lines=Data+Science+%26+ML" alt="Data Science & ML" />
</h4>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=tensorflow,pytorch,anaconda" />
  </a>
</p>

<h4 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=1500&pause=500&color=FFFFFF&center=true&vCenter=true&width=200&lines=Database" alt="Database" />
</h4>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=mysql,postgresql,mongodb,sqlite" />
  </a>
</p>

<h4 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=1500&pause=500&color=FFFFFF&center=true&vCenter=true&width=200&lines=Tools" alt="Tools" />
</h4>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,github,docker,vscode,linux,figma,postman" />
  </a>
</p>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Image before Achievements -->
<div align="center">
  <img src="https://lh3.googleusercontent.com/rd-gg-dl/AOI_d__HwhoxAMHnhWWSreR5AWb2uJEsYcIFapqT1_dpJwz5FW6ScjpD7cmYKTyo_Tc8wPgDZZzcQVaLQK4kzdddxPcb4qvnRgnHLAV4aaN3_Or_zjob3t64JKbsB-MtaLuTnxJTv-0cLM4VD95MiPQgismOQhUJISEhFqAArR-WRMW-M-_4g17YDskCSTCI_DnWXOZO8vuhpRqrbuBOf6VpyZs8gZzfUYo0z4XcFBxbY15vWf01YHW3ZVL-Gp5t3ki943USGT9DOl7LQ8vFxrMdDpU6x9cfAtCw29KXuDlhH9D7j7Iy4lsY5IA-RjcvVZfaJOzXJUvXiiBZ2jRoL0H1Sf4UM8Wb6AciwCIhOI7Z84ttVxxjmBfw47J-4Nk62EWXob_lIbk52zIv7ochRKc4YcmesgEocrOxyS-tGb7nfEzxax7Z0n7VHhw_oho3CNtRTRQytzqnxZgjYFyVudjkU5H05iPb5i-9wwr9bv62VmlRWYfw8yuEFTj56slsTbMqJIWbrCHPId17vvEN7ze1O8L6cApvRgW9EaO4CALuHrn-79addgEGewOw7T1KfYHzGeXeSbsW4fn8YSCFjXKzHEmlSLQwa7zJTpipdp7aHYcLqIcFffOlYEZor98EU53Qb6w_1LhosBi3BTCn2RhhAosttutKbxiVC_mrZb1Oo73p4GpY-Aw-eyTVII7HoZXgeLb6G8AN8O6Qf6wmED_dKOSsTVEzfOadeOOMShYFNr61nyAypYvXAMJwyk9RAUobziJAx2LmlZIVqP0MNZSnngYQLip7lA64IGntRv_D5V5smRKgMoYo_jKAo-ZGG0IN7RYHFVN6bfyvtYI3brSaTbd5ZMziuGPL0VoHzFvv-UXbebaZl17Nx2keBPbtQJJjaE8CiiBJzo2EilGhtcjirIA-iEHMyTOzhHR00UVcpGdFUrQy5p2KsG83-DXgXdR8QXqSUGUICr4YRQJnwkiqwG_cXx_1TJjGGpbSGPkNEP0CVNpsnA9CnbQahjAVAzipf4rUZVqY6jMZIQX0FDUwgtoe3YfuMgl2b2lqhRMFH8qWh-abQS5rnKBcO2HKG4ZxK71pjoBMxPpoEcCogxrYXdr26A7KsbdAZ46n37N03p81hXdao7pSyn7Ko-yGByVqPivi_xtlnFM25QEYQjNBVN8iLTOoIPHyImvOQY3LoVMs4llUzlvZPVNMZd1VvVPwe2EKUTvoZkI-UYfFwtXPRzvmu2NIOjujr2e0XydS0Lh9R4msHMqqBq5w5JE2=s1600-rj?authuser=1" width="80%" alt="Certificate" />
</div>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Achievements -->
<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Righteous&weight=600&size=35&duration=2000&pause=800&color=00FFCC&center=true&vCenter=true&width=500&lines=Achievements" alt="Achievements" />
</h3>

<div align="center">

| | Achievement | Description |
|:---:|:---|:---|
| | **ICPC Cochabamba** | Rank #18 (First competition) |
| | **Electoral System** | Curricular Value Certification |
| | **n8n Automation** | +6,500 automated records |
| | **Deep Learning** | 94.2% accuracy fraud detection |

</div>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Experience -->
<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Righteous&weight=600&size=35&duration=2000&pause=800&color=FF6600&center=true&vCenter=true&width=500&lines=Professional+Experience" alt="Professional Experience" />
</h3>

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
<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Righteous&weight=600&size=35&duration=2000&pause=800&color=6600FF&center=true&vCenter=true&width=500&lines=GitHub+Stats" alt="GitHub Stats" />
</h3>

<div align="center">

![Gerald's GitHub stats](https://github-readme-stats.vercel.app/api?username=GeraldVargas&theme=tokyonight&show_icons=true&count_private=true&hide_border=true&bg_color=0D1117)

[![GitHub Streak](https://streak-stats.demolab.com/?user=GeraldVargas&theme=tokyonight&hide_border=true&background=0D1117)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=GeraldVargas&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=10)](https://github.com/GeraldVargas)

</div>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Activity Graph -->
<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Righteous&weight=600&size=35&duration=2000&pause=800&color=00FF66&center=true&vCenter=true&width=500&lines=Activity+Graph" alt="Activity Graph" />
</h3>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=GeraldVargas&custom_title=Gerald%20Vargas%20-%20Contribution%20Graph&bg_color=0d1117&color=00d9ff&line=00d9ff&point=FFFFFF&area_color=00d9ff&title_color=FFFFFF&area=true&hide_border=true" alt="Contribution Graph" width="100%"/>
</div>

<br>

<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- Connect -->
<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Righteous&weight=600&size=35&duration=2000&pause=800&color=FF0066&center=true&vCenter=true&width=500&lines=Connect+With+Me" alt="Connect With Me" />
</h3>

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
