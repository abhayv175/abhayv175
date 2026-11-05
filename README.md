<div align="center">

<!-- LIQUID GLASS AESTHETIC HERO BANNER WITH EMBEDDED CSS HOVER INTERACTION -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 850 260" width="100%" height="260">
  <defs>
    <!-- Background Gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0b0f19"/>
      <stop offset="50%" stop-color="#111827"/>
      <stop offset="100%" stop-color="#090d16"/>
    </linearGradient>

    <!-- Liquid Mesh Ambient Orbs -->
    <radialGradient id="liquidOrb1" cx="30%" cy="30%" r="70%">
      <stop offset="0%" stop-color="#6366f1" stop-opacity="0.55"/>
      <stop offset="50%" stop-color="#3b82f6" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#0b0f19" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="liquidOrb2" cx="70%" cy="70%" r="70%">
      <stop offset="0%" stop-color="#ec4899" stop-opacity="0.45"/>
      <stop offset="50%" stop-color="#8b5cf6" stop-opacity="0.2"/>
      <stop offset="100%" stop-color="#0b0f19" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="liquidOrb3" cx="50%" cy="50%" r="60%">
      <stop offset="0%" stop-color="#06b6d4" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#0b0f19" stop-opacity="0"/>
    </radialGradient>

    <!-- Frosted Glass Surface Gradient -->
    <linearGradient id="glassFill" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.12"/>
      <stop offset="100%" stop-color="#ffffff" stop-opacity="0.03"/>
    </linearGradient>

    <!-- Glass Specular Border -->
    <linearGradient id="glassBorder" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.45"/>
      <stop offset="50%" stop-color="#ffffff" stop-opacity="0.1"/>
      <stop offset="100%" stop-color="#38bdf8" stop-opacity="0.3"/>
    </linearGradient>

    <filter id="glassGlow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feComposite in="SourceGraphic" in2="blur" operator="over"/>
    </filter>

    <style>
      .glass-container {
        cursor: pointer;
        transition: transform 0.4s cubic-bezier(0.16, 1, 0.3, 1), filter 0.4s ease;
      }
      .glass-card {
        transition: fill 0.3s ease, stroke 0.3s ease;
      }
      .glass-container:hover {
        transform: translateY(-4px) scale(1.008);
      }
      .glass-container:hover .glass-card {
        fill: url(#glassFillHover);
        stroke: #38bdf8;
      }
      .glass-container:hover .hero-title {
        fill: #38bdf8;
      }
      .hero-title {
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        font-weight: 800;
        fill: #ffffff;
        letter-spacing: -0.5px;
        transition: fill 0.3s ease;
      }
      .hero-sub {
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        font-size: 14.5px;
        font-weight: 500;
        fill: #94a3b8;
        letter-spacing: 0.8px;
      }
      .badge-tag {
        font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
        font-size: 11px;
        font-weight: 600;
        fill: #38bdf8;
      }
    </style>

    <linearGradient id="glassFillHover" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#ffffff" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#38bdf8" stop-opacity="0.08"/>
    </linearGradient>
  </defs>

  <!-- Deep Canvas Base -->
  <rect width="100%" height="100%" rx="16" fill="url(#bgGrad)" />

  <!-- Ambient Fluid Elements -->
  <ellipse cx="220" cy="80" rx="200" ry="90" fill="url(#liquidOrb1)" />
  <ellipse cx="640" cy="180" rx="220" ry="110" fill="url(#liquidOrb2)" />
  <ellipse cx="420" cy="130" rx="140" ry="70" fill="url(#liquidOrb3)" />

  <!-- Frosted Glass Interactive Card -->
  <g class="glass-container">
    <rect class="glass-card" x="35" y="30" width="780" height="200" rx="20" fill="url(#glassFill)" stroke="url(#glassBorder)" stroke-width="1.2" />

    <!-- Frosted Chip Badge -->
    <rect x="335" y="48" width="180" height="24" rx="12" fill="#ffffff" fill-opacity="0.06" stroke="#ffffff" stroke-opacity="0.18" stroke-width="0.8" />
    <circle cx="347" cy="60" r="3.5" fill="#10b981" />
    <text x="358" y="64" class="badge-tag">READY TO INNOVATE</text>

    <!-- Main Title -->
    <text x="425" y="118" text-anchor="middle" class="hero-title" font-size="38">Abhay Verma</text>

    <!-- Subtitle Spec -->
    <text x="425" y="152" text-anchor="middle" class="hero-sub">
      Software Engineer  •  System Design  •  QA &amp; Protocol Testing
    </text>

    <!-- Tech Highlight Bar -->
    <rect x="180" y="174" width="490" height="32" rx="16" fill="#000000" fill-opacity="0.25" stroke="#ffffff" stroke-opacity="0.08" stroke-width="0.8" />
    <text x="425" y="195" text-anchor="middle" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="12" fill="#cbd5e1" font-weight="500">
      C#  ·  C++  ·  TypeScript  ·  Python  ·  QXDM / ADB  ·  Next.js
    </text>
  </g>
</svg>

<br/>

<!-- HOVER-REACTIVE LIQUID GLASS NAVIGATION BUTTONS -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 760 48" width="100%" height="48">
  <defs>
    <style>
      .btn {
        cursor: pointer;
        transition: transform 0.25s cubic-bezier(0.16, 1, 0.3, 1);
      }
      .btn-bg {
        fill: #1e293b;
        fill-opacity: 0.55;
        stroke: #ffffff;
        stroke-opacity: 0.15;
        stroke-width: 1;
        transition: fill 0.2s, stroke 0.2s, fill-opacity 0.2s;
      }
      .btn-text {
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
        font-size: 12px;
        font-weight: 600;
        fill: #f1f5f9;
        letter-spacing: 0.4px;
        transition: fill 0.2s;
      }
      .btn:hover {
        transform: translateY(-2px);
      }
      .btn:hover .btn-bg {
        fill: #38bdf8;
        fill-opacity: 0.2;
        stroke: #38bdf8;
        stroke-opacity: 0.8;
      }
      .btn:hover .btn-text {
        fill: #38bdf8;
      }
    </style>
  </defs>

  <!-- Portfolio -->
  <a href="https://abhayv175.netlify.app" target="_blank">
    <g class="btn" transform="translate(15, 4)">
      <rect class="btn-bg" width="135" height="38" rx="19"/>
      <text x="67" y="24" text-anchor="middle" class="btn-text">🌐 Portfolio</text>
    </g>
  </a>

  <!-- LinkedIn -->
  <a href="https://linkedin.com/in/abhayv175" target="_blank">
    <g class="btn" transform="translate(165, 4)">
      <rect class="btn-bg" width="135" height="38" rx="19"/>
      <text x="67" y="24" text-anchor="middle" class="btn-text">💼 LinkedIn</text>
    </g>
  </a>

  <!-- LeetCode -->
  <a href="https://leetcode.com/abhayv175" target="_blank">
    <g class="btn" transform="translate(315, 4)">
      <rect class="btn-bg" width="135" height="38" rx="19"/>
      <text x="67" y="24" text-anchor="middle" class="btn-text">🧩 LeetCode</text>
    </g>
  </a>

  <!-- HackerRank -->
  <a href="https://hackerrank.com/abhayv175" target="_blank">
    <g class="btn" transform="translate(465, 4)">
      <rect class="btn-bg" width="135" height="38" rx="19"/>
      <text x="67" y="24" text-anchor="middle" class="btn-text">⚡ HackerRank</text>
    </g>
  </a>

  <!-- Email -->
  <a href="mailto:abhayv175@icloud.com">
    <g class="btn" transform="translate(615, 4)">
      <rect class="btn-bg" width="130" height="38" rx="19"/>
      <text x="65" y="24" text-anchor="middle" class="btn-text">✉️ Contact</text>
    </g>
  </a>
</svg>

</div>

---

### 👨‍💻 Engineering Profile

- 💻 **Software Engineer** specializing in full-stack web applications, distributed workflows, and scalable **System Design**[cite: 5, 6].
- 🧪 **Hands-on QA & Test Engineering** background encompassing protocol/modem-level testing, device logs (QXDM, QCAT, ADB), and cross-platform regression[cite: 5].
- 🎓 **Education:** B.Sc. in Information Technology at Vilnius Gediminas Technical University[cite: 6].
- 🌍 **Passions:** Distributed architectures, clean codebases, and global geopolitics.

---

### 💼 Work Experience

#### 🔹 **Test Engineer** · [Marquistech](https://marquistech.com/) *(Nov 2025 – Present)*[cite: 5]
- Capture device and network logs using **QXDM, QCAT, and ADB** to identify modem, RF, and protocol-level anomalies across unreleased OEM devices[cite: 5].
- Reproduce and validate network issues involving **5G NR, IMS/VoLTE**, attach failures, throughput drops, and handovers[cite: 5].
- Document findings with detailed logs, reproduction steps, and KPIs (**RSRP, RSRQ, SINR**) for OEM, carrier, and chipset engineering reviews[cite: 5].

#### 🔹 **Junior Test Engineer** · [Unity](https://unity.com/) *(Nov 2024 – Apr 2025)*[cite: 5]
- Executed manual, ad-hoc, and exploratory test cases across engine environments including **IL2CPP and DOMS**[cite: 5].
- Managed internal QA hardware labs with diverse machines and deployed local FTP server setups to streamline distributed remote team testing[cite: 5].
- Tracked defects to resolution using Jira, identifying regression versions and providing workarounds for critical bugs[cite: 5].

#### 🔹 **Software Development Intern** · UAB First Riddle *(Dec 2023 – Apr 2024)*[cite: 5]
- Designed and developed responsive e-commerce web platform features to improve user engagement[cite: 5].
- Engineered user query and messaging database models, cutting retrieval times by 40%[cite: 5].

---

### 🚀 Projects & Architecture

| Project | Tech Stack | Highlights | Links |
| :--- | :--- | :--- | :--- |
| **Passenger Messenger** | Next.js, TypeScript, React, MongoDB, Pusher[cite: 5] | Real-time chat application featuring live messaging, NextAuth session auth, and Cloudinary media delivery[cite: 5]. | [Source Code](https://github.com/abhayverma2108/passengermessenge)[cite: 5] |
| **Move-It Logistics** | React, JavaScript, HTML5/CSS3, MongoDB[cite: 6] | Interactive courier and package dispatch platform with intuitive pickup scheduling and shipment tracking[cite: 6]. | [Live Demo](https://abhayverma2108.github.io/MOVE-17/)[cite: 6] |
| **Bank Application** | Java, JavaFX, FXML, Custom CSS[cite: 6] | Desktop banking interface designed with SceneBuilder supporting secure account transactions and balance flows[cite: 6]. | [Source Code](https://github.com/abhayverma2108/Bank_Application)[cite: 6] |
| **Greek Vocabulary App** | Flutter, Dart, SQLite[cite: 6] | Mobile learning app tracking travel and dining vocabulary with offline JSON/SQLite persistence[cite: 6]. | [Source Code](https://github.com/BenBinary/greek_vocs)[cite: 6] |
| **Pika Panic** | Unity Engine, C#, Plastic SCM[cite: 6] | Desktop game highlighting custom mechanics, level design, and team version control via Plastic SCM[cite: 6]. | [Overview](https://cloud.unity.com/home/organizations/24756934479511c6-4dab-94d2-c940bf45f6a4/details)[cite: 6] |
| **Personal Portfolio** | React, Vite, JavaScript[cite: 5] | Responsive developer portfolio showcasing engineering projects, interactive UI components, and tech stacks[cite: 5]. | [Live Site](https://abhayv175.netlify.app)[cite: 5] |

---

### 🛠️ Tech Stack & Tooling

<div align="center">

**Languages & Architecture**  
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Frontend & Mobile**  
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Databases & Backend**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**QA, Protocol & System Tools**  
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=android-studio&logoColor=white)

</div>

---

### 🧩 LeetCode Metrics

<div align="center">
  <a href="https://leetcode.com/abhayv175" target="_blank">
    <img src="https://leetcard.jacoblin.cool/abhayv175?theme=dark&font=Ubuntu&ext=activity" alt="LeetCode Stats & Activity" height="190" />
  </a>
</div>

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://streak-stats.demolab.com?user=abhayv175&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="150" />
</div>

---

<div align="center">
  <sub>Designed with Frosted Glassmorphism by Abhay Verma</sub>
</div>
