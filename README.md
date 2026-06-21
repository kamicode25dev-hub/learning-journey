[![PT-BR](https://img.shields.io/badge/🌎_Português-blue?style=for-the-badge)](README.pt-BR.md)
[![EN](https://img.shields.io/badge/🌍_English-red?style=for-the-badge)](README.md)

<svg width="1600" height="450" viewBox="0 0 1600 450" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <!-- Galaxy Background -->
    <linearGradient id="space" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0B1026"/>
      <stop offset="50%" stop-color="#5B21B6"/>
      <stop offset="100%" stop-color="#1E1B4B"/>
    </linearGradient>

    <!-- Nebula -->
    <radialGradient id="nebula">
      <stop offset="0%" stop-color="#A78BFA" stop-opacity="0.5">
        <animate attributeName="stop-opacity"
                 values="0.2;0.7;0.2"
                 dur="8s"
                 repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
    </radialGradient>

    <!-- Neon Glow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1600" height="450" fill="url(#space)"/>
  <rect width="1600" height="450" fill="url(#nebula)"/>

  <!-- Animated Stars -->
  <g fill="white">
    <circle cx="100" cy="70" r="2">
      <animate attributeName="opacity" values="1;0.2;1" dur="3s" repeatCount="indefinite"/>
    </circle>

    <circle cx="350" cy="120" r="2">
      <animate attributeName="opacity" values="1;0.1;1" dur="4s" repeatCount="indefinite"/>
    </circle>

    <circle cx="700" cy="80" r="2">
      <animate attributeName="opacity" values="1;0.2;1" dur="5s" repeatCount="indefinite"/>
    </circle>

    <circle cx="1100" cy="140" r="2">
      <animate attributeName="opacity" values="1;0.2;1" dur="3.5s" repeatCount="indefinite"/>
    </circle>

    <circle cx="1450" cy="60" r="3">
      <animate attributeName="opacity" values="1;0.1;1" dur="4.5s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Planet -->
  <g>
    <circle cx="1320" cy="250" r="75" fill="#8B5CF6">
      <animateTransform
        attributeName="transform"
        type="rotate"
        from="0 1320 250"
        to="360 1320 250"
        dur="30s"
        repeatCount="indefinite"/>
    </circle>

    <ellipse cx="1320"
             cy="250"
             rx="120"
             ry="35"
             fill="none"
             stroke="#DDD6FE"
             stroke-width="4"
             opacity="0.8"/>
  </g>

  <!-- Orbiting Satellite -->
  <circle r="8" fill="#F5F3FF">
    <animateMotion
      dur="12s"
      repeatCount="indefinite"
      path="M1320 250 m-120 0 a120 35 0 1 0 240 0 a120 35 0 1 0 -240 0"/>
  </circle>

  <!-- Floating Computer -->
  <g transform="translate(100,130)">
    <rect width="130" height="90"
          rx="12"
          fill="#7C3AED"/>

    <rect x="15"
          y="15"
          width="100"
          height="55"
          rx="5"
          fill="#1E1B4B"/>

    <text x="28"
          y="52"
          fill="#C4B5FD"
          font-size="26"
          font-family="Consolas">
      &lt;/&gt;
    </text>

    <animateTransform
      attributeName="transform"
      type="translate"
      values="100,130;100,120;100,130"
      dur="4s"
      repeatCount="indefinite"/>
  </g>

  <!-- Main Title -->
  <text x="270"
        y="190"
        font-family="Poppins, Arial"
        font-size="84"
        font-weight="700"
        fill="#FFFFFF"
        filter="url(#glow)">
    Courses &amp; Projects
  </text>

  <!-- Subtitle -->
  <text x="275"
        y="260"
        font-family="Inter, Arial"
        font-size="40"
        fill="#DDD6FE">
    Computer Science
  </text>

  <!-- Decorative Line -->
  <line x1="275"
        y1="295"
        x2="980"
        y2="295"
        stroke="#A78BFA"
        stroke-width="3">
    <animate attributeName="stroke-opacity"
             values="0.3;1;0.3"
             dur="4s"
             repeatCount="indefinite"/>
  </line>

  <!-- Footer -->
  <text x="275"
        y="360"
        fill="#C4B5FD"
        font-size="28"
        font-family="Consolas">

    Python • Backend Development • Software Engineering • Cloud

    <animate attributeName="opacity"
             values="0.5;1;0.5"
             dur="3s"
             repeatCount="indefinite"/>
  </text>

</svg>

# 🚀 Learning Journey 🚀

📚 Repository created to organize all the courses I have completed throughout my journey as an aspiring Computer Science professional.  
Here you will find **summaries, notes, and projects** for each course I finish.

---

## 🙋 About Me

- 🌟 **Name:** Kami Code  
- 🎯 **Focus:** Junior Back-end & Front-end Development  
- 📍 **Location:** Florianópolis, Santa Catarina, Brazil  
- 🚀 **Goal:** Get my first tech position and keep evolving always!  

---

## 📂 Repository Organization

01 - HTML  
02 - HTML5 & CSS3 - World 1  
03 - HTML5 & CSS3 - World 2  
04 - HTML5 & CSS3 - World 3  
05 - HTML5 & CSS3 - World 4  
06 - Python 3 - World 1  
07 - Python 3 - World 2  
08 - Python 3 - World 3  
09 - Git & GitHub  
10 - MySQL  
11 - JavaScript  
12 - Java OOP  
13 - Basic PHP  
14 - Algorithms  

---

## 🛠️ Technologies & Tools

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🎯 Goals

- Build practical projects for each course  
- Publish my journey on GitHub as a portfolio  
- Share my growth on LinkedIn  
- Achieve my first job as a **Junior Back-end Developer**  

---

## 🌐 Contacts

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kamicode)  
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kamicode25.dev@gmail.com)  
