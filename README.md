
<div align="center">

  <!-- CODE IN THE SHADOWS / OBSIDIAN + RUBY -->
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:0D1117,55:210B16,100:65142B&height=165&section=header&text=HARSH%20KUMAR%20%E5%BD%B1&fontSize=46&fontColor=F0F6FC&animation=fadeIn&fontAlignY=40&desc=SOFTWARE%20ENGINEERING%20%E2%80%A2%20AGENTIC%20AI%20%E2%80%A2%20SPATIAL%20XR&descAlignY=68&descSize=14" width="100%" alt="Harsh Kumar — Code in the Shadows" />

  <a href="https://codeinshadows.vercel.app">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&duration=3500&pause=1400&color=FB7185&center=true&vCenter=true&width=720&height=36&lines=%3E+Building+software+with+purpose.;%3E+From+clean+interfaces+to+intelligent+systems." alt="Engineering focus" />
  </a>

  <p><b>B.Tech CSE · IIIT Delhi</b> &nbsp;|&nbsp; Full-Stack &amp; AI Systems Builder</p>

  <p>
    <a href="https://codeinshadows.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-EXPLORE-9F1239?style=flat-square&logo=vercel&logoColor=white&labelColor=0D1117" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/harsh-kumar-837a9139b"><img src="https://img.shields.io/badge/LINKEDIN-CONNECT-20202A?style=flat-square&logo=linkedin&logoColor=FB7185&labelColor=0D1117" alt="LinkedIn" /></a>
    <a href="mailto:harsh24239@iiitd.ac.in"><img src="https://img.shields.io/badge/EMAIL-CONTACT-20202A?style=flat-square&logo=gmail&logoColor=FB7185&labelColor=0D1117" alt="Email" /></a>
    <a href="https://leetcode.com/u/codezharsh/"><img src="https://img.shields.io/badge/LEETCODE-PROFILE-20202A?style=flat-square&logo=leetcode&logoColor=FB7185&labelColor=0D1117" alt="LeetCode" /></a>
  </p>

</div>

---

### `01 // ABOUT`

<table>
  <tr>
    <td width="66%" valign="top">
      <h3>I build software where design meets engineering.</h3>
      <p>I'm interested in <b>full-stack products, agentic AI, and immersive 3D experiences</b>. I enjoy turning complex ideas into practical systems with clear interfaces and maintainable architecture.</p>
    </td>
    <td width="34%" valign="top">
      <h4><code>FOCUS / NOW</code></h4>
      <p><code>01</code> &nbsp; Agentic AI &amp; RAG<br/>
      <code>02</code> &nbsp; Full-stack systems<br/>
      <code>03</code> &nbsp; Spatial computing</p>
    </td>
  </tr>
</table>

### `02 // SELECTED WORK`

<!-- ONE STRONG FEATURED CARD, RATHER THAN A LONG PROJECT DESCRIPTION -->
<table>
  <tr>
    <td width="61%" valign="top">
      <sub><b>01 / FEATURED BUILD &nbsp;·&nbsp; IN DEVELOPMENT</b></sub>
      <h3>AI Placement Copilot</h3>
      <p>An AI-assisted placement preparation platform combining <b>multi-agent workflows</b>, semantic retrieval, and an accessible web interface.</p>
      <p><sub><code>LangGraph</code> &nbsp; <code>FastAPI</code> &nbsp; <code>ChromaDB</code> &nbsp; <code>React</code></sub></p>
      <p><a href="https://github.com/harsh24239/ai-placement-copilot"><b>Explore the repository ↗</b></a></p>
    </td>
    <td width="39%" valign="top">
      <h4><code>HOW IT WORKS</code></h4>
      <pre>  STUDENT INPUT
       ↓
  FASTAPI + AGENTS
       ↓
  RETRIEVAL / RAG
       ↓
  GROUNDED RESPONSE</pre>
      <sub>Agent routing &amp; retrieval-based responses</sub>
    </td>
  </tr>
</table>

<!-- FOUR COMPACT PROJECT CARDS -->
<table>
  <tr>
    <td width="50%" valign="top">
      <sub><code>02 / XR · SIMULATION</code></sub>
      <h4>VR Manual Milling</h4>
      <p>Virtual machining trainer exploring force-based haptic feedback and 3D interaction.</p>
      <p><sub><code>Unity</code> · <code>C#</code> · <code>Blender</code></sub></p>
      <a href="https://github.com/harsh24239/vr-manual-milling-simulator"><b>View source ↗</b></a>
    </td>
    <td width="50%" valign="top">
      <sub><code>03 / XR · EDUCATION</code></sub>
      <h4>SpatialMath XR</h4>
      <p>Immersive 3D visualizations designed to make undergraduate mathematics easier to explore.</p>
      <p><sub><code>Unity 3D</code> · <code>C#</code> · <code>Visualization</code></sub></p>
      <sub>Research / interactive learning</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <sub><code>04 / WEB · SECURITY</code></sub>
      <h4>SQVS — Credential Verifier</h4>
      <p>Qualification verification with role-based permissions, structured records, and audit logs.</p>
      <p><sub><code>React</code> · <code>Node.js</code> · <code>MySQL</code></sub></p>
      <a href="https://codeinshadows.vercel.app/#projects"><b>View case study ↗</b></a>
    </td>
    <td width="50%" valign="top">
      <sub><code>05 / JAVA · ARCHITECTURE</code></sub>
      <h4>University ERP</h4>
      <p>Modular academic system built with clearly separated UI, service, data access, and database layers.</p>
      <p><sub><code>Java Swing</code> · <code>JDBC</code> · <code>JUnit 5</code></sub></p>
      <a href="https://codeinshadows.vercel.app/#projects"><b>View case study ↗</b></a>
    </td>
  </tr>
</table>

<details>
<summary><b>▸ View AI Placement Copilot architecture</b></summary>

<sub>Conceptual flow · project in development</sub>

```mermaid
flowchart LR
    UI["React"] --> API["FastAPI"]
    API --> AGENT{"LangGraph"}
    AGENT --> RAG["Retrieval"]
    AGENT --> INT["Interview agent"]
    RAG <--> DB[("ChromaDB")]
    RAG --> LLM["Gemini"]
    INT --> LLM
    LLM --> API
    classDef accent fill:#4C0519,stroke:#FB7185,color:#F0F6FC;
    classDef base fill:#0D1117,stroke:#67707D,color:#F0F6FC;
    class AGENT,LLM accent;
    class UI,API,RAG,INT,DB base;
```

</details>

---

### `03 // TOOLKIT`

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,java,cpp,ts,js,cs,react,vite,nodejs,express,fastapi,mysql,unity,blender,git,linux&perline=8&theme=dark" alt="Technology stack" />
  <p><sub><b>Languages</b> &nbsp;·&nbsp; Python, Java, TypeScript, C/C++ &nbsp;&nbsp;|&nbsp;&nbsp; <b>Systems</b> &nbsp;·&nbsp; React, FastAPI, Node.js, MySQL &nbsp;&nbsp;|&nbsp;&nbsp; <b>AI &amp; XR</b> &nbsp;·&nbsp; LangGraph, ChromaDB, Unity</sub></p>
</div>

---

### `04 // GITHUB ACTIVITY`

<div align="center">
  <a href="https://github.com/harsh24239"><img src="https://github-readme-streak-stats.herokuapp.com/?user=harsh24239&theme=dark&background=0D1117&border=30363D&ring=9F1239&fire=FB7185&currStreakLabel=F0F6FC&sideLabels=8B949E&dates=8B949E" height="155" alt="GitHub contribution streak" /></a>
  <a href="https://github.com/harsh24239?tab=repositories"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harsh24239&layout=compact&langs_count=6&bg_color=0D1117&title_color=FB7185&text_color=ABB4C0&border_color=30363D" height="155" alt="Top repository languages" /></a>

  <p><sub><code>PRECISION OVER VOLUME</code> &nbsp;·&nbsp; <code>CODE IN THE SHADOWS</code> &nbsp;·&nbsp; <code>HARSH.DEV 影</code></sub></p>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:65142B,55:210B16,100:0D1117&height=65&section=footer" width="100%" alt="Footer" />
</div>
