<div align="center">

  <!-- Architectural Graphite & Muted Crimson Studio Header -->
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,65:141921,100:3B0A14&height=140&section=header&text=HARSH%20KUMAR%20%E5%BD%B1&fontSize=42&fontColor=F0F6FC&fontAlignY=42&desc=GRAPHITE%20STUDY%20%E2%80%94%20FULL-STACK%20SYSTEMS%20%E2%80%A2%20AGENTIC%20AI%20%E2%80%A2%20SPATIAL%20XR&descAlignY=68&descSize=12&stroke=30363D&strokeWidth=1" width="100%" alt="Harsh Kumar — Code in the Shadows" />

  <br/>

  <!-- Editorial Thesis & Typographic Telemetry -->
  <p>
    <b>B.Tech CSAM @ IIIT Delhi</b> &nbsp;·&nbsp; <b>New Delhi, India</b> &nbsp;·&nbsp; <code><b>Open to SWE & AI Roles</b></code><br/>
    <sub><i>"Mastery is not speed. It is the elimination of wasted motion."</i></sub>
  </p>

  <!-- Unified 4-Channel Command Bar -->
  <p>
    <a href="https://codeinshadows.vercel.app"><img src="https://img.shields.io/badge/01-HARSH.DEV_PORTFOLIO-9F1239?style=flat-square&labelColor=0D1117" alt="Portfolio" /></a>&nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/harsh-kumar-837a9139b"><img src="https://img.shields.io/badge/02-LINKEDIN_CONNECT-161B22?style=flat-square&labelColor=0D1117" alt="LinkedIn" /></a>&nbsp;&nbsp;
    <a href="https://leetcode.com/u/codezharsh"><img src="https://img.shields.io/badge/03-LEETCODE_(130%2B_DSA)-161B22?style=flat-square&labelColor=0D1117" alt="LeetCode" /></a>&nbsp;&nbsp;
    <a href="mailto:harsh24239@iiitd.ac.in"><img src="https://img.shields.io/badge/04-EMAIL_DIRECT-161B22?style=flat-square&labelColor=0D1117" alt="Email" /></a>
  </p>

</div>

---

### `01 // ENGINEERING DISCIPLINES`

<table>
  <tr>
    <td width="33%" valign="top">
      <p><sub><code>I // ARCHITECTURE</code></sub></p>
      <h4>Full-Stack Systems</h4>
      <p><sub>Modular backends, role-gated security (RBAC), connection pooling, and clean API contracts engineered for production reliability.</sub></p>
    </td>
    <td width="33%" valign="top">
      <p><sub><code>II // INTELLIGENCE</code></sub></p>
      <h4>Agentic AI & RAG</h4>
      <p><sub>Stateful multi-agent orchestration, ChromaDB vector retrieval, and context-grounded LLM workflows with low-latency gateways.</sub></p>
    </td>
    <td width="33%" valign="top">
      <p><sub><code>III // INTERACTION</code></sub></p>
      <h4>Spatial XR & Craft</h4>
      <p><sub>Immersive 3D mathematical environments, real-time spatial visualization, and high-precision interfaces with zero clutter.</sub></p>
    </td>
  </tr>
</table>

---

### `02 // SELECTED WORKS`

<table>
  <tr>
    <td width="50%" valign="top">
      <p><sub><code>01 // AGENTIC AI & RAG</code> &nbsp;·&nbsp; <b>ACTIVE BUILD</b></sub></p>
      <h4>AI Placement Copilot</h4>
      <p><sub>Stateful multi-agent interview and placement preparation platform unifying practice workflows, grounded vector retrieval, and real-time evaluation.</sub></p>
      <p><sub><code>React + Vite</code> · <code>FastAPI</code> · <code>LangGraph</code> · <code>ChromaDB</code> · <code>Gemini API</code></sub></p>
      <p><a href="https://github.com/harsh24239/ai-placement-copilot"><kbd> VIEW REPOSITORY ↗ </kbd></a></p>
    </td>
    <td width="50%" valign="top">
      <p><sub><code>02 // SPATIAL COMPUTING</code></sub></p>
      <h4>SpatialMath XR</h4>
      <p><sub>Interactive 3D computation environment translating abstract multivariable mathematics into manipulable spatial scenes.</sub></p>
      <p><sub><code>Unity 3D</code> · <code>C#</code> · <code>3D Visualization</code> · <code>Custom Shaders</code></sub></p>
      <p><a href="https://github.com/harsh24239/SpatialMath"><kbd> VIEW REPOSITORY ↗ </kbd></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <p><sub><code>03 // ACCESS CONTROL & SECURITY</code></sub></p>
      <h4>SQVS — Qualification Verifier</h4>
      <p><sub>Role-gated credential verification system built around strict RBAC permissions, normalized schemas, and immutable audit logs.</sub></p>
      <p><sub><code>React</code> · <code>Node.js</code> · <code>Express</code> · <code>MySQL</code> · <code>RBAC</code></sub></p>
      <p><a href="https://github.com/Anilcodee/sqvs"><kbd> VIEW ON GITHUB ↗ </kbd></a></p>
    </td>
    <td width="50%" valign="top">
      <p><sub><code>04 // ENTERPRISE DESKTOP CORE</code></sub></p>
      <h4>4-Layer University ERP</h4>
      <p><sub>Decoupled desktop ERP isolating Swing presentation, BCrypt/RBAC service logic, JDBC DAO persistence, and HikariCP pooling.</sub></p>
      <p><sub><code>Java Swing</code> · <code>JDBC</code> · <code>HikariCP</code> · <code>BCrypt</code> · <code>JUnit 5</code></sub></p>
      <p><a href="https://github.com/Anilcodee/erp_university"><kbd> VIEW ON GITHUB ↗ </kbd></a></p>
    </td>
  </tr>
</table>

<details>
<summary><b><code>+ EXPAND SYSTEM ARCHITECTURE BLUEPRINTS (MERMAID.JS)</code></b></summary>
<br/>

```mermaid
flowchart LR
    UI["React + Vite Client"] -->|REST JSON| API["FastAPI Gateway"]
    API --> SUP{"LangGraph Router"}
    SUP -->|Semantic Search| VDB[("ChromaDB Vector Store")]
    VDB -->|Grounded Context| RAG["RAG Synthesis Node"]
    SUP -->|Mock Evaluation| INT["DSA & Interview Agent"]
    RAG --> LLM["Gemini API"]
    INT --> LLM
    LLM --> UI
    style SUP fill:#9F1239,stroke:#F0F6FC,color:#FFFFFF
    style API fill:#0D1117,stroke:#30363D,color:#F0F6FC
    style VDB fill:#161B22,stroke:#9F1239,color:#F0F6FC
```
</details>

---

### `03 // TECHNICAL SPECIFICATION`

<div align="center">

| Layer | Production Technologies & Methods | Stack |
| :--- | :--- | :---: |
| **Languages** | `Python` · `Java` · `TypeScript` · `JavaScript` · `C / C++` · `C#` · `SQL` | <img src="https://skillicons.dev/icons?i=py,java,ts,js,cpp,cs&theme=dark" height="24" alt="Languages" /> |
| **Web & Backend** | `React` · `Vite` · `FastAPI` · `Node.js` · `Express` · `REST APIs` · `HikariCP` | <img src="https://skillicons.dev/icons?i=react,vite,fastapi,nodejs,express,linux&theme=dark" height="24" alt="Web and Backend" /> |
| **AI & Data** | `LangGraph` · `Multi-Agent RAG` · `ChromaDB` · `Gemini API` · `MySQL` · `SQLite` | <img src="https://skillicons.dev/icons?i=mysql,sqlite,py,gcp&theme=dark" height="24" alt="AI and Data" /> |
| **Spatial & Craft** | `Unity 3D` · `XR Toolkit` · `Blender` · `Figma` · `JUnit 5` · `RBAC / JWT` · `Git` | <img src="https://skillicons.dev/icons?i=unity,blender,figma,git&theme=dark" height="24" alt="Spatial and Craft" /> |

</div>

---

### `04 // TELEMETRY`

<div align="center">
  <table>
    <tr>
      <td width="50%" align="center">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=harsh24239&theme=dark&background=0D1117&border=30363D&ring=9F1239&fire=F43F5E&currStreakLabel=F0F6FC&sideLabels=8B949E&dates=8B949E" width="100%" alt="GitHub contribution streak" />
      </td>
      <td width="50%" align="center">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harsh24239&layout=compact&langs_count=6&bg_color=0D1117&title_color=F0F6FC&text_color=8B949E&border_color=30363D" width="100%" alt="Most used repository languages" />
      </td>
    </tr>
  </table>
  <p><sub><b><code>DESIGN WITH INTENT</code></b> &nbsp;•&nbsp; <b><code>PRECISION OVER VOLUME</code></b> &nbsp;•&nbsp; <b><code>HARSH.DEV 影</code></b></sub></p>
</div>
