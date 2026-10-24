<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:0D1117,55:210B16,100:65142B&height=180&section=header&text=HARSH%20KUMAR%20%E5%BD%B1&fontSize=46&fontColor=F0F6FC&animation=fadeIn&fontAlignY=40&desc=SOFTWARE%20SYSTEMS%20%E2%80%A2%20AGENTIC%20AI%20%E2%80%A2%20SPATIAL%20XR&descAlignY=65&descSize=14" width="100%" alt="Harsh Kumar" />

  <a href="https://codeinshadows.vercel.app">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=15&duration=3200&pause=1300&color=FB7185&center=true&vCenter=true&width=760&height=38&lines=%3E+Full-Stack+Engineering+%2F%2F+Agentic+AI+%2F%2F+Spatial+XR;%3E+Precision+over+volume.+Always." alt="Typing SVG" />
  </a>

  <p>
    <a href="https://codeinshadows.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-9F1239?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0D1117" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/harsh-kumar-837a9139b"><img src="https://img.shields.io/badge/LINKEDIN-20202A?style=for-the-badge&logo=linkedin&logoColor=FB7185&labelColor=0D1117" alt="LinkedIn" /></a>
    <a href="https://leetcode.com/u/codezharsh/"><img src="https://img.shields.io/badge/LEETCODE-20202A?style=for-the-badge&logo=leetcode&logoColor=FB7185&labelColor=0D1117" alt="LeetCode" /></a>
    <a href="mailto:harsh24239@iiitd.ac.in"><img src="https://img.shields.io/badge/EMAIL-20202A?style=for-the-badge&logo=gmail&logoColor=FB7185&labelColor=0D1117" alt="Email" /></a>
  </p>

</div>

---

### `01 // SYSTEM PROFILE`

<table>
  <tr>
    <td width="50%" valign="top">
<pre lang="yaml">engineer:  Harsh Kumar (影)
institute: IIIT Delhi (B.Tech CSE)
location:  New Delhi, IN
status:    Open to SWE & AI Roles</pre>
    </td>
    <td width="50%" valign="top">
<pre lang="yaml">ai_systems:   LangGraph · Multi-Agent RAG · Vector DBs
backend:      FastAPI · Node.js · RBAC · HikariCP
spatial_xr:   Unity 3D · Haptic Physics · Shaders
philosophy:   Strict boundaries. Zero bloat.</pre>
    </td>
  </tr>
</table>

---

### `02 // SYSTEMS ARCHITECTURE`

<!-- TOP BENTO SPAN: FLAGSHIP -->
<table>
  <tr>
    <td width="60%" valign="top">
      <img src="https://img.shields.io/badge/SYS_01-FLAGSHIP_ARCHITECTURE-9F1239?style=flat-square&labelColor=0D1117" alt="Flagship" />
      <img src="https://img.shields.io/badge/MULTI--AGENT_RAG-20202A?style=flat-square&labelColor=0D1117" alt="RAG" />
      <h3>AI Placement Copilot</h3>
<pre lang="yaml">scope: Stateful interview simulation & grounded retrieval
flow:  Query ➔ LangGraph Router ➔ [RAG | Eval] ➔ Gemini</pre>
      <p>
        <img src="https://skillicons.dev/icons?i=py,fastapi,react,vite&theme=dark" height="24" alt="Stack" />
        &nbsp;
        <a href="https://github.com/harsh24239/ai-placement-copilot">
          <img src="https://img.shields.io/badge/SOURCE_CODE-9F1239?style=flat-square&logo=github&logoColor=white&labelColor=0D1117" height="24" alt="Repo" />
        </a>
      </p>
    </td>
    <td width="40%" valign="top">
<pre lang="yaml">CLIENT:    React + Vite
GATEWAY:   FastAPI (Async REST)
AGENTS:    LangGraph State Graph
MEMORY:    ChromaDB Vector Store
INFERENCE: Gemini API
ROUTING:   Deterministic</pre>
    </td>
  </tr>
</table>

```mermaid
flowchart LR
    subgraph CLIENT ["CLIENT & GATEWAY"]
        WEB["React + Vite"] --> API["FastAPI"]
    end
    subgraph ENGINE ["AGENTIC ORCHESTRATION"]
        API --> SUP{"LangGraph Router"}
        SUP -->|Context| RAG["RAG Node"]
        SUP -->|Mock Eval| INT["Interview Node"]
        RAG --> GEN["Gemini API"]
        INT --> GEN
    end
    subgraph DATA ["VECTOR MEMORY"]
        RAG <--> DB[("ChromaDB")]
    end
    GEN --> API
    classDef ruby fill:#4C0519,stroke:#FB7185,color:#F0F6FC,stroke-width:2px;
    classDef graphite fill:#0D1117,stroke:#30363D,color:#F0F6FC;
    class SUP,GEN ruby;
    class WEB,API,RAG,INT,DB graphite;
    style CLIENT fill:#0D1117,stroke:#30363D,color:#8B949E
    style ENGINE fill:#0D1117,stroke:#9F1239,color:#FB7185
    style DATA fill:#0D1117,stroke:#30363D,color:#8B949E
```

<!-- 2x2 BENTO GRID: CORE SYSTEMS -->
<table>
  <tr>
    <td width="50%" valign="top">
      <img src="https://img.shields.io/badge/SYS_02-HAPTIC_SIMULATION-9F1239?style=flat-square&labelColor=0D1117" alt="SYS_02" />
      <h3>VR Manual Milling</h3>
<pre lang="yaml">scope: Virtual machining & force feedback
flow:  Kinematics ➔ Force Calc ➔ Haptics</pre>
      <p>
        <img src="https://skillicons.dev/icons?i=unity,cs,blender&theme=dark" height="22" alt="Stack" />
        &nbsp;
        <a href="https://github.com/harsh24239/vr-manual-milling-simulator">
          <img src="https://img.shields.io/badge/REPO-20202A?style=flat-square&logo=github&logoColor=FB7185&labelColor=0D1117" height="22" alt="Repo" />
        </a>
      </p>
    </td>
    <td width="50%" valign="top">
      <img src="https://img.shields.io/badge/SYS_03-SPATIAL_COMPUTING-20202A?style=flat-square&labelColor=0D1117" alt="SYS_03" />
      <h3>SpatialMath XR</h3>
<pre lang="yaml">scope: Interactive 3D multivariable math
flow:  Function ➔ Procedural Mesh ➔ 3D Scene</pre>
      <p>
        <img src="https://skillicons.dev/icons?i=unity,cs&theme=dark" height="22" alt="Stack" />
        &nbsp;
        <img src="https://img.shields.io/badge/3D_SHADERS-0D1117?style=flat-square&color=20202A" height="22" alt="Shaders" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="https://img.shields.io/badge/SYS_04-SECURITY_%26_AUDIT-9F1239?style=flat-square&labelColor=0D1117" alt="SYS_04" />
      <h3>SQVS — Credential Verifier</h3>
<pre lang="yaml">scope: Role-gated qualification verification
flow:  JWT ➔ RBAC Guard ➔ Verify ➔ Audit Log</pre>
      <p>
        <img src="https://skillicons.dev/icons?i=react,nodejs,express,mysql&theme=dark" height="22" alt="Stack" />
        &nbsp;
        <img src="https://img.shields.io/badge/RBAC_%2B_JWT-0D1117?style=flat-square&color=20202A" height="22" alt="RBAC" />
      </p>
    </td>
    <td width="50%" valign="top">
      <img src="https://img.shields.io/badge/SYS_05-4--LAYER_ERP-20202A?style=flat-square&labelColor=0D1117" alt="SYS_05" />
      <h3>4-Layer University ERP</h3>
<pre lang="yaml">scope: Decoupled desktop academic ERP
flow:  Swing ➔ Service (RBAC) ➔ DAO ➔ HikariCP</pre>
      <p>
        <img src="https://skillicons.dev/icons?i=java,mysql,git&theme=dark" height="22" alt="Stack" />
        &nbsp;
        <img src="https://img.shields.io/badge/HIKARICP_%2B_JUNIT5-0D1117?style=flat-square&color=20202A" height="22" alt="HikariCP" />
      </p>
    </td>
  </tr>
</table>

<details>
<summary><b>↳ INSPECT 4-LAYER ERP TOPOLOGY</b></summary>
<br/>

```mermaid
flowchart LR
    UI["Swing UI"] --> SERVICE["Service (RBAC + BCrypt)"] --> DAO["DAO (JDBC)"] --> POOL["HikariCP"]
    POOL --> AUTH[("Auth DB")]
    POOL --> ERP[("Academic DB")]
    classDef ruby fill:#4C0519,stroke:#FB7185,color:#F0F6FC,stroke-width:2px;
    classDef graphite fill:#0D1117,stroke:#30363D,color:#F0F6FC;
    class SERVICE,POOL ruby;
    class UI,DAO,AUTH,ERP graphite;
```
</details>

---

### `03 // INFRASTRUCTURE & TOOLING`

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,java,cpp,ts,js,cs,react,vite,nodejs,express,fastapi,mysql,unity,blender,git,linux&perline=8&theme=dark" alt="Tech Stack" />
</div>

<br/>

| Domain | Core Primitives |
| :--- | :--- |
| **Languages** | `Python` · `Java` · `TypeScript` · `JavaScript` · `C/C++` · `C#` · `SQL` |
| **AI & Data** | `LangGraph` · `Multi-Agent RAG` · `ChromaDB` · `Gemini API` · `MySQL` |
| **Backend & Auth** | `FastAPI` · `Node.js` · `Express` · `RBAC` · `JWT` · `BCrypt` · `HikariCP` · `JUnit 5` |
| **Frontend & XR** | `React` · `Vite` · `Unity 3D` · `XR Toolkit` · `Blender` · `Linux` |

---

### `04 // TELEMETRY`

<div align="center">
  <a href="https://github.com/harsh24239">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=harsh24239&theme=dark&background=0D1117&border=30363D&ring=9F1239&fire=FB7185&currStreakLabel=F0F6FC&sideLabels=8B949E&dates=8B949E" height="165" alt="GitHub Streak" />
  </a>
  <a href="https://github.com/harsh24239?tab=repositories">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harsh24239&layout=compact&langs_count=6&bg_color=0D1117&title_color=FB7185&text_color=ABB4C0&border_color=30363D" height="165" alt="Top Languages" />
  </a>
  <br/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=harsh24239&bg_color=0D1117&color=8B949E&line=9F1239&point=FB7185&area=true&hide_border=true&custom_title=CONTRIBUTION%20TELEMETRY" width="98%" alt="Activity Graph" />
</div>

<div align="center">
  <br/>
  <p><sub><code>PRECISION OVER VOLUME</code> &nbsp;•&nbsp; <code>HARSH.DEV 影</code></sub></p>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:65142B,55:210B16,100:0D1117&height=80&section=footer" width="100%" alt="Footer" />
</div>
