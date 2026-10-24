<div align="center">

  <!-- Ambient Obsidian-Wine Header (Warm, Low-Glare Crimson Glow) -->
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:0D1117,65:180609,100:4C0519&height=155&section=header&text=HARSH%20KUMAR%20%E5%BD%B1&fontSize=46&fontColor=F0F6FC&animation=fadeIn&fontAlignY=42&desc=SOFTWARE%20SYSTEMS%20%E2%80%A2%20AGENTIC%20AI%20%E2%80%A2%20SPATIAL%20COMPUTING%20(XR)&descAlignY=68&descSize=13&stroke=30363D&strokeWidth=1" width="100%" alt="Harsh Kumar Header" />

  <!-- Balanced 2-Line Sub-Header (Zero Orphan Word Wrapping) -->
  <p>
    <code><b>B.Tech CSE @ IIIT Delhi</b></code> &nbsp;•&nbsp; <code><b>Full-Stack & Agentic AI Engineer</b></code><br/>
    <sub><i>"Mastery is not speed. It is the elimination of wasted motion."</i></sub>
  </p>

  <!-- Single-Line Command Bar (All Icons & Live Links Restored) -->
  <p>
    <a href="https://codeinshadows.vercel.app"><img src="https://img.shields.io/badge/HARSH.DEV-PORTFOLIO-9F1239?style=flat-square&logo=vercel&logoColor=white&labelColor=0D1117" alt="Portfolio" /></a>
    <a href="https://linkedin.com/in/harsh-kumar-837a9139b"><img src="https://img.shields.io/badge/IN-LINKEDIN_CONNECT-161B22?style=flat-square&labelColor=0D1117&color=161B22" alt="LinkedIn" /></a>
    <a href="https://leetcode.com/u/codezharsh/"><img src="https://img.shields.io/badge/LEETCODE-130%2B_DSA-161B22?style=flat-square&logo=leetcode&logoColor=F43F5E&labelColor=0D1117" alt="LeetCode" /></a>
    <a href="mailto:harsh24239@iiitd.ac.in"><img src="https://img.shields.io/badge/EMAIL-CONTACT-161B22?style=flat-square&logo=gmail&logoColor=F43F5E&labelColor=0D1117" alt="Email" /></a>
  </p>

</div>

---

### `01 // ARCHITECTURE & FOCUS`

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><code>SYSTEM TELEMETRY</code></h4>
      <pre lang="yaml">
operative: Harsh Kumar (影)
institute: IIIT Delhi (B.Tech CSE)
focus:     Web, Agentic AI & XR
tenure:    3+ Years Building
shipped:   6+ Core Systems
clearance: Open to SWE & AI Roles</pre>
    </td>
    <td width="50%" valign="top">
      <h4><code>ENGINEERING DOMAINS</code></h4>
      <ul>
        <li><b>Agentic AI & RAG:</b> Multi-agent flows with <code>LangGraph</code>, <code>ChromaDB</code> & <code>FastAPI</code>.</li>
        <li><b>Full-Stack Web:</b> Production apps via <code>React</code>, <code>TypeScript</code>, <code>Node.js</code> & <code>Express</code>.</li>
        <li><b>Enterprise Systems:</b> 4-Layer design, <code>RBAC</code>, <code>HikariCP</code>, <code>BCrypt</code> & <code>JUnit 5</code>.</li>
        <li><b>Spatial XR:</b> Haptic 3D simulation in <code>Unity</code>, <code>C#</code> & <code>Blender</code>.</li>
      </ul>
    </td>
  </tr>
</table>

---

### `02 // SELECTED ENGINEERING WORK`

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🔴 AI Placement Copilot &nbsp;<sub><code>ACTIVE</code></sub></h4>
      <p><sub><code>FastAPI</code> · <code>LangGraph</code> · <code>ChromaDB</code> · <code>React</code></sub></p>
      <p>Grounded placement preparation engine utilizing multi-agent LangGraph orchestration, semantic vector retrieval, and a low-latency FastAPI gateway.</p>
      <p><a href="https://github.com/harsh24239/ai-placement-copilot"><kbd> VIEW REPOSITORY ↗ </kbd></a></p>
    </td>
    <td width="50%" valign="top">
      <h4>⚪ VR Milling & SpatialMath XR &nbsp;<sub><code>RESEARCH</code></sub></h4>
      <p><sub><code>Unity 3D</code> · <code>C#</code> · <code>Blender</code> · <code>XR Haptics</code></sub></p>
      <p>Force-based haptic manual milling trainer and an interactive 3D Virtual Reality platform designed to visualize undergraduate mathematics.</p>
      <p>
        <a href="https://github.com/harsh24239/vr-manual-milling-simulator"><kbd> MILLING XR ↗ </kbd></a>
        <a href="https://github.com/harsh24239/SpatialMath"><kbd> SPATIALMATH ↗ </kbd></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>⚪ SQVS — Credential Verifier &nbsp;<sub><code>SHIPPED</code></sub></h4>
      <p><sub><code>React.js</code> · <code>Node.js</code> · <code>Express</code> · <code>MySQL</code></sub></p>
      <p>Student Qualification Verification System engineered around strict Role-Based Access Control (RBAC), normalized relational schemas, and audit logs.</p>
      <p><a href="https://codeinshadows.vercel.app"><kbd> CASE STUDY ↗ </kbd></a></p>
    </td>
    <td width="50%" valign="top">
      <h4>⚪ 4-Layer University ERP &nbsp;<sub><code>SHIPPED</code></sub></h4>
      <p><sub><code>Java Swing</code> · <code>JDBC</code> · <code>HikariCP</code> · <code>JUnit 5</code></sub></p>
      <p>Modular desktop ERP isolating authentication (<code>university_auth</code>) and academic operations across a strict <code>UI → Service → DAO → DB</code> architecture.</p>
      <p><a href="https://codeinshadows.vercel.app"><kbd> ARCHITECTURE ↗ </kbd></a></p>
    </td>
  </tr>
</table>

<details>
<summary><b><code>+ INSPECT SYSTEM ARCHITECTURE BLUEPRINTS (MERMAID.JS)</code></b></summary>
<br/>

#### `A. AI Placement Copilot — Multi-Agent LangGraph Pipeline`
```mermaid
flowchart LR
    UI["React + Vite Client"] -->|REST JSON| API["FastAPI Gateway"]
    API --> SUP{"LangGraph Supervisor"}
    SUP -->|Vector Search| VDB[("ChromaDB Store")]
    VDB -->|Grounded Context| RAG["RAG Synthesis Node"]
    SUP -->|Evaluation| INT["Interview Agent"]
    RAG --> LLM["Gemini API"]
    INT --> LLM
    LLM --> UI
    style SUP fill:#881337,stroke:#F0F6FC,color:#FFFFFF
    style API fill:#0D1117,stroke:#30363D,color:#F0F6FC
    style VDB fill:#0D1117,stroke:#F43F5E,color:#F0F6FC
```

#### `B. University ERP — 4-Layer Enterprise Security Flow`
```mermaid
flowchart LR
    SW["1. Java Swing UI"] --> SRV["2. Service Layer (RBAC + BCrypt)"]
    SRV --> DAO["3. DAO Layer (JDBC Contracts)"]
    DAO --> POOL["HikariCP Connection Pool"]
    POOL --> AUTH[("MySQL: university_auth")]
    POOL --> ERP[("MySQL: university_erp")]
    style SRV fill:#881337,stroke:#F0F6FC,color:#FFFFFF
    style POOL fill:#0D1117,stroke:#F43F5E,color:#F0F6FC
```
</details>

---

### `03 // PRODUCTION STACK & TOOLING`

<div align="center">

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=F43F5E) ![Java](https://img.shields.io/badge/Java-161B22?style=flat-square&logo=openjdk&logoColor=F43F5E) ![TypeScript](https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=F43F5E) ![JavaScript](https://img.shields.io/badge/JavaScript-161B22?style=flat-square&logo=javascript&logoColor=F43F5E) ![C++](https://img.shields.io/badge/C%2FC%2B%2B-161B22?style=flat-square&logo=cplusplus&logoColor=F43F5E) ![C#](https://img.shields.io/badge/C%23-161B22?style=flat-square&logo=sharp&logoColor=F43F5E) ![SQL](https://img.shields.io/badge/SQL-161B22?style=flat-square&logo=mysql&logoColor=F43F5E) |
| **Web & Backend** | ![React](https://img.shields.io/badge/React.js-161B22?style=flat-square&logo=react&logoColor=F43F5E) ![Vite](https://img.shields.io/badge/Vite-161B22?style=flat-square&logo=vite&logoColor=F43F5E) ![FastAPI](https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=F43F5E) ![Node.js](https://img.shields.io/badge/Node.js-161B22?style=flat-square&logo=nodedotjs&logoColor=F43F5E) ![Express](https://img.shields.io/badge/Express.js-161B22?style=flat-square&logo=express&logoColor=F43F5E) ![REST](https://img.shields.io/badge/REST_APIs-161B22?style=flat-square&logo=insomnia&logoColor=F43F5E) |
| **AI, Data & XR** | ![LangGraph](https://img.shields.io/badge/LangGraph-161B22?style=flat-square&logo=chainlink&logoColor=F43F5E) ![ChromaDB](https://img.shields.io/badge/ChromaDB_RAG-161B22?style=flat-square&logo=databricks&logoColor=F43F5E) ![Gemini](https://img.shields.io/badge/Gemini_API-161B22?style=flat-square&logo=googlegemini&logoColor=F43F5E) ![MySQL](https://img.shields.io/badge/MySQL-161B22?style=flat-square&logo=mysql&logoColor=F43F5E) ![HikariCP](https://img.shields.io/badge/HikariCP-161B22?style=flat-square&logo=apachemaven&logoColor=F43F5E) ![Unity](https://img.shields.io/badge/Unity_3D-161B22?style=flat-square&logo=unity&logoColor=F43F5E) |
| **Engineering Craft** | ![RBAC](https://img.shields.io/badge/RBAC_%26_JWT-161B22?style=flat-square&logo=jsonwebtokens&logoColor=F43F5E) ![JUnit5](https://img.shields.io/badge/JUnit_5-161B22?style=flat-square&logo=junit5&logoColor=F43F5E) ![Git](https://img.shields.io/badge/Git_%26_Linux-161B22?style=flat-square&logo=linux&logoColor=F43F5E) ![Blender](https://img.shields.io/badge/Blender-161B22?style=flat-square&logo=blender&logoColor=F43F5E) ![Figma](https://img.shields.io/badge/Figma-161B22?style=flat-square&logo=figma&logoColor=F43F5E) |

</div>

---

### `04 // TELEMETRY & ACTIVITY`

<div align="center">
  <table>
    <tr>
      <td width="50%" align="center">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=harsh24239&theme=dark&background=0D1117&border=30363D&ring=9F1239&fire=F43F5E&currStreakLabel=F0F6FC&sideLabels=8B949E&dates=8B949E" width="100%" alt="GitHub Streak" />
      </td>
      <td width="50%" align="center">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harsh24239&layout=compact&langs_count=6&bg_color=0D1117&title_color=F0F6FC&text_color=8B949E&border_color=30363D" width="100%" alt="Top Languages" />
      </td>
    </tr>
  </table>
  <p><sub><b><code>PRECISION OVER VOLUME</code></b> &nbsp;•&nbsp; <b><code>LEAVE NO TRACE</code></b> &nbsp;•&nbsp; <b><code>HARSH.DEV 影</code></b></sub></p>
</div>
