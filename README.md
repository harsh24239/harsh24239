 <div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,35:180A0D,70:351016,100:B83A46&height=175&section=header&text=HARSH%20KUMAR%20%E5%BD%B1&fontSize=46&fontColor=F0F6FC&animation=fadeIn&fontAlignY=40&desc=SOFTWARE%20SYSTEMS%20%20%E2%80%A2%20%20AGENTIC%20AI%20%20%E2%80%A2%20%20SPATIAL%20COMPUTING&descAlignY=65&descSize=12&descColor=C9D1D9" width="100%" alt="Harsh Kumar — Software Systems, Agentic AI and Spatial Computing" />

<br/>

<a href="https://codeinshadows.vercel.app">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=14&duration=3600&pause=1100&color=B83A46&center=true&vCenter=true&width=700&height=40&lines=%3E+Building+systems+that+solve+real+problems;%3E+Exploring+agentic+AI+and+intelligent+software;%3E+Engineering+interactive+3D+experiences;%3E+From+architecture+to+implementation." alt="Engineering focus animation" />
</a>

<br/>

<a href="https://codeinshadows.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-0D1117?style=for-the-badge&logo=vercel&logoColor=B83A46" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/harsh-kumar-837a9139b"><img src="https://img.shields.io/badge/LINKEDIN-0D1117?style=for-the-badge&logo=linkedin&logoColor=8B949E" alt="LinkedIn"/></a>
<a href="https://leetcode.com/u/codezharsh"><img src="https://img.shields.io/badge/LEETCODE-0D1117?style=for-the-badge&logo=leetcode&logoColor=B83A46" alt="LeetCode"/></a>
<a href="mailto:kumarharsh1851@gmail.com"><img src="https://img.shields.io/badge/CONTACT-0D1117?style=for-the-badge&logo=gmail&logoColor=8B949E" alt="Email"/></a>

<br/><br/>

<sub><code>BUILD WITH INTENT</code> &nbsp;·&nbsp; <code>DESIGN FOR SCALE</code> &nbsp;·&nbsp; <code>LEARN BY SHIPPING</code></sub>

</div>

---

## `01 / PROFILE`

I'm a Computer Science undergraduate at **IIIT Delhi**, interested in building reliable software systems, AI-powered applications, and interactive spatial computing experiences.

My work spans full-stack development, retrieval-augmented generation, multi-agent workflows, database architecture, and Unity-based 3D simulation.

I enjoy working across the stack — understanding a problem, designing its architecture, implementing the solution, and refining it through testing and iteration.

- **Currently exploring:** Agentic AI, RAG pipelines, and AI-assisted developer tools.
- **Building with:** Python, TypeScript, Java, React, FastAPI, and Unity.
- **Interested in:** Software engineering, AI infrastructure, backend systems, and XR.
- **Portfolio:** [codeinshadows.vercel.app](https://codeinshadows.vercel.app)

---

## `02 / SELECTED PROJECTS`

<table>
<tr>
<td width="50%" valign="top">

### AI Placement Copilot

<sub><code>AI ENGINEERING</code> · <code>IN PROGRESS</code></sub>

An AI-powered placement preparation platform designed to combine contextual retrieval with specialized agent workflows.

- Multi-agent orchestration with LangGraph.
- Semantic retrieval using ChromaDB.
- API layer built with FastAPI.
- React-based user interface.

**Stack:** Python · LangGraph · ChromaDB · FastAPI · React

<a href="https://github.com/harsh24239/ai-placement-copilot">Explore repository ↗</a>

</td>
<td width="50%" valign="top">

### SpatialMath XR

<sub><code>SPATIAL COMPUTING</code> · <code>RESEARCH</code></sub>

An interactive VR learning environment that explores ways to make mathematical concepts more visual, spatial, and intuitive.

- Interactive 3D mathematical visualizations.
- Virtual textbook and learning panels.
- Unity-based XR interface.
- Exploration of symbolic mathematics integration.

**Stack:** Unity · C# · Blender · XR · SymPy

<a href="https://github.com/harsh24239/SpatialMath">Explore repository ↗</a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### VR Manual Milling Simulator

<sub><code>XR SIMULATION</code> · <code>ENGINEERING</code></sub>

A virtual milling training experience focused on interactive machine operation and exploring force-based haptic feedback.

- 3D machine and tool interaction.
- Virtual training workflows.
- Exploration of haptic interaction.

**Stack:** Unity · C# · Blender · XR

<a href="https://github.com/harsh24239/vr-manual-milling-simulator">Explore repository ↗</a>

</td>
<td width="50%" valign="top">

### Student Qualification Verification System

<sub><code>FULL-STACK</code> · <code>WEB SYSTEMS</code></sub>

A student credential verification application designed around structured data management and role-based access.

- React-based frontend.
- Node.js and Express backend.
- MySQL relational data model.
- Role-based access and audit logging.

**Stack:** React · Node.js · Express · MySQL

<a href="https://codeinshadows.vercel.app/#projects">View project case study ↗</a>

</td>
</tr>
</table>

### Additional engineering work

**Four-Layer University ERP**

A Java desktop application organized around separation of concerns, with distinct UI, service, data-access, and database layers.

`Java Swing` · `JDBC` · `HikariCP` · `MySQL` · `JUnit 5`

<a href="https://codeinshadows.vercel.app/#projects">View architecture and project details ↗</a>

---

## `03 / ENGINEERING APPROACH`

<details>
<summary><b>AI Placement Copilot — Conceptual architecture</b></summary>

<br/>

```mermaid
flowchart TD
    U["React Client"] --> API["FastAPI"]
    API --> G{"LangGraph Orchestration"}
    G --> R["Semantic Retrieval"]
    R <--> DB[("ChromaDB")]
    R --> C["Context Assembly"]
    G --> A["Interview Agent"]
    C --> L["LLM Integration"]
    A --> L
    L --> API
    API --> U

    style U fill:#161B22,stroke:#30363D,color:#F0F6FC
    style API fill:#161B22,stroke:#B83A46,color:#F0F6FC
    style G fill:#351016,stroke:#B83A46,color:#FFFFFF
    style DB fill:#161B22,stroke:#6E7681,color:#F0F6FC
    style L fill:#161B22,stroke:#6E7681,color:#F0F6FC
```

<sub>Conceptual architecture; update the diagram to reflect the implementation as the system evolves.</sub>

</details>

<details>
<summary><b>University ERP — Layered architecture</b></summary>

<br/>

```mermaid
flowchart TD
    UI["Presentation Layer"] --> S["Service Layer"]
    S --> D["Data Access Layer"]
    D --> DB[("Relational Database")]

    style UI fill:#161B22,stroke:#30363D,color:#F0F6FC
    style S fill:#161B22,stroke:#B83A46,color:#F0F6FC
    style D fill:#161B22,stroke:#6E7681,color:#F0F6FC
    style DB fill:#161B22,stroke:#6E7681,color:#F0F6FC
```

</details>

---

## `04 / TECHNOLOGY STACK`

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,java,cpp,cs,ts,js,sql&theme=dark" alt="Python, Java, C++, C#, TypeScript, JavaScript and SQL" />

**Frontend and Backend**

<img src="https://skillicons.dev/icons?i=react,vite,nodejs,express,fastapi&theme=dark" alt="React, Vite, Node.js, Express and FastAPI" />

**AI, Databases and Spatial Computing**

<img src="https://skillicons.dev/icons?i=github,git,mysql,unity,blender,figma&theme=dark" alt="GitHub, Git, MySQL, Unity, Blender and Figma" />

</div>

<sub>Technologies and tools used across projects and ongoing exploration.</sub>

---

## `05 / GITHUB ACTIVITY`

<div align="center">

<a href="https://github.com/harsh24239">
<img src="https://github-readme-stats.vercel.app/api?username=harsh24239&show_icons=true&hide_border=true&bg_color=0D1117&title_color=C9D1D9&text_color=8B949E&icon_color=B83A46&rank_icon=github" width="49%" alt="GitHub statistics"/>
</a>
<a href="https://github.com/harsh24239">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harsh24239&layout=compact&hide_border=true&bg_color=0D1117&title_color=C9D1D9&text_color=8B949E" width="41%" alt="Most used programming languages"/>
</a>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=harsh24239&theme=dark&hide_border=true&background=0D1117&ring=B83A46&fire=B83A46&currStreakLabel=C9D1D9&sideLabels=8B949E&dates=6E7681" width="80%" alt="GitHub contribution streak"/>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:1B0C10,100:351016&height=2&section=footer" width="100%" alt=""/>

<sub>ENGINEER WITH CURIOSITY &nbsp;·&nbsp; BUILD WITH PURPOSE &nbsp;·&nbsp; IMPROVE CONTINUOUSLY</sub>

<br/>

<sub>Harsh Kumar · IIIT Delhi</sub>

</div>
