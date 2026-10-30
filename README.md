<div align="center">

  <!-- Hero Header Banner -->
  <a href="https://github.com/Lander2007">
    <img src="./assets/banner.svg" alt="Khaled Amr - 3D Web & Frontend Engineer" width="100%" />
  </a>

  <br/>

  <!-- Quick Action & Social Pills -->
  <p align="center">
    <a href="https://www.linkedin.com/in/kh%E1%A5%B2%E1%A5%A3%E1%A5%B1d-amr-263334343/">
      <img src="https://img.shields.io/badge/LinkedIn-Khaled%20Amr-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile" />
    </a>
    &nbsp;
    <a href="mailto:kaledamr457@gmail.com">
      <img src="https://img.shields.io/badge/Email-kaledamr457%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Direct Email" />
    </a>
    &nbsp;
    <a href="#-interactive-featured-projects">
      <img src="https://img.shields.io/badge/Showcase-View%20Projects-38BDF8?style=for-the-badge&logo=three.js&logoColor=white" alt="View Projects" />
    </a>
    &nbsp;
    <img src="https://img.shields.io/badge/Status-Building%20SpaceEdu-10B981?style=for-the-badge&logo=statuspage&logoColor=white" alt="Status" />
  </p>

</div>

> [!NOTE]
> **Engineering Focus:** I craft high-performance web applications that merge rock-solid frontend architecture (`React`, `TypeScript`, `Tailwind CSS`) with immersive 3D graphics (`Three.js`, `React Three Fiber`, `GLSL`) and autonomous AI agent workflows.

---

### ⚡ Developer Telemetry // `khaled.config.ts`

```typescript
export const engineer: DeveloperProfile = {
  name: "Khaled Amr",
  role: "Creative Frontend & 3D Web Engineer",
  location: "Cairo, Egypt",
  aesthetic: ["Dark Mode", "Glassmorphism", "Spatial 3D UI", "Minimal Futurism"],
  
  stack: {
    graphics3D: ["Three.js", "React Three Fiber (R3F)", "@react-three/drei", "GLSL Shaders"],
    frontend:   ["React 18+", "TypeScript", "Vite", "Tailwind CSS", "Next.js"],
    backend:    ["Node.js", "Express", "PostgreSQL", "REST APIs"],
    workflow:   ["Git / GitHub", "Figma", "Docker", "Linux / Bash"]
  },

  currentMission: {
    project: "SpaceEdu",
    mission: "Architecting a 60 FPS real-time 3D celestial simulator paired with ARIA, an AI science companion.",
    status: "Active Development"
  },

  philosophy: "Flat screens are a limitation of the past. High frame rates, tactile 3D interactions, and intuitive UI make software feel alive."
};
```

---

### 🚀 Interactive Featured Projects

Click on any project to expand technical deep dives, architecture decisions, and live specs:

<details open>
<summary><b>🪐 01. SpaceEdu — Immersive 3D Space Platform & AI Science Tutor</b> <code>FEATURED</code></summary>
<br/>

> *An interactive space exploration ecosystem featuring a real-time 3D solar system, physics-driven orbital mechanics, and an intelligent copilot.*

- **Key Highlights:**
  - **Custom 3D Engine:** Built on **Vite**, **Three.js**, and **React Three Fiber** with custom instanced meshes for asteroid belts and realistic starfields.
  - **Dynamic Shaders:** GLSL atmospheric scattering and solar flares running at a silky-smooth **60 FPS** on desktop & mobile web.
  - **Physics Simulator:** Implements orbital gravitational mechanics allowing users to simulate celestial trajectories.
  - **ARIA Copilot:** Integrated generative AI companion that answers astrophysics questions, guides explorations, and narrates cosmic phenomena in real-time.
- **Tech Stack:** `Three.js` • `React Three Fiber` • `TypeScript` • `Vite` • `Tailwind CSS` • `AI Agent API`
- **Architecture Highlights:**
  ```text
  [User 3D Viewport] <---> [R3F Scene Graph & Camera Rig]
                                   |
         +-------------------------+-------------------------+
         |                                                   |
  [Physics & Orbit Worker]                         [ARIA AI Streaming HUD]
  (Keplerian math & collision)                     (Context-aware astrophysics Q&A)
  ```

</details>

<details>
<summary><b>🛍️ 02. King-Store — High-Fidelity Modern E-Commerce Platform</b> <code>FULL-STACK</code></summary>
<br/>

> *A multi-language storefront with sub-second page transitions, dynamic cart state management, and a comprehensive real-time admin dashboard.*

- **Key Highlights:**
  - **Localization (i18n):** Seamless multi-language support with instant locale switching and dynamic RTL/LTR layout mirroring.
  - **Optimistic UI:** Instantaneous cart operations, localized currency conversions, and zero-layout-shift (CLS < 0.01) product showcases.
  - **Admin Command Center:** Complete administrative workflow including order lifecycle management, dynamic inventory editing, and sales velocity charting.
- **Tech Stack:** `React` • `TypeScript` • `Tailwind CSS` • `RESTful APIs` • `Admin UI Kit`
- **Key Modules:**
  - ⚡ Granular state management with decoupled checkout pipeline
  - 🎨 Glassmorphic product showcase cards with smooth micro-interactions
  - 📊 Real-time inventory telemetry & analytics dashboard

</details>

<details>
<summary><b>📦 03. Warehouse Management System — LAN Distributed Architecture</b> <code>SYSTEMS & DB</code></summary>
<br/>

> *A low-latency, mission-critical inventory management system engineered for high concurrency across local area networks (LAN).*

- **Key Highlights:**
  - **High Concurrency:** Handles high-throughput barcode scanning and simultaneous multi-station inventory adjustments without data drift.
  - **ACID-Compliant PostgreSQL Schema:** Strict foreign key integrity and transactional isolation to eliminate race conditions during bulk stock movements.
  - **Role-Based Access Control (RBAC):** Granular permissions separating warehouse floor operators, dispatch coordinators, and system administrators.
- **Tech Stack:** `Node.js` • `Express` • `PostgreSQL` • `REST APIs` • `LAN Architecture`

</details>

---

### 🛠️ Tech Stack & Engineering Arsenal

<div align="center">

| Domain | Core Technologies | Specialization & Focus |
| :--- | :--- | :--- |
| **🌌 3D & Creative** | `Three.js` • `React Three Fiber` • `GLSL` • `WebGL` | Real-time scene graphs, particle systems, procedural shaders, 60fps rendering |
| **⚛️ Frontend** | `React` • `TypeScript` • `Next.js` • `Vite` | Component architecture, state machines, clean TypeScript typing, responsive UX |
| **🎨 UI & Styling** | `Tailwind CSS` • `Framer Motion` • `CSS3` | Modern glassmorphism, high-contrast dark themes, tactile interactive animations |
| **⚙️ Backend & Data** | `Node.js` • `Express` • `PostgreSQL` • `REST` | Relational schemas, ACID transactions, API design, high-reliability services |
| **🔧 Workflow** | `Git` • `GitHub` • `Figma` • `VS Code` • `Bash` | Design-to-code pipelines, Git workflows, clean documentation, UI prototyping |

</div>

<br/>

<div align="center">

<!-- Visual Badges Grid -->
<p>
  <img src="https://img.shields.io/badge/Three.js-black?style=flat-square&logo=three.js&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/React_Three_Fiber-000000?style=flat-square&logo=react&logoColor=61DAFB" alt="R3F" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React_18%2B-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

</div>

---

### 📈 GitHub Telemetry

<div align="center">
  <a href="https://github.com/Lander2007">
    <img src="https://streak-stats.demolab.com?user=Lander2007&theme=tokyonight&hide_border=true&background=0d111a&ring=38bdf8&fire=00f2fe&currStreakLabel=38bdf8&sideNums=38bdf8&currStreakNum=ffffff" alt="Khaled's GitHub Streak" />
  </a>
</div>

---

### 📬 Connect & Collaborate

Have an exciting 3D web project, innovative frontend role, or creative tech idea? Let's connect:

| Platform | Channel | Primary Use Case |
| :--- | :--- | :--- |
| **💼 LinkedIn** | [Khaled Amr on LinkedIn](https://www.linkedin.com/in/kh%E1%A5%B2%E1%A5%A3%E1%A5%B1d-amr-263334343/) | Professional networking, opportunities, and references |
| **✉️ Email** | [kaledamr457@gmail.com](mailto:kaledamr457@gmail.com) | Direct contracts, consulting, and project inquiries |
| **💻 GitHub** | [@Lander2007](https://github.com/Lander2007) | Open source collaboration, code reviews, and discussions |

<br/>

<div align="center">

```bash
# Clone and explore my work
gh repo clone Lander2007/SpaceEdu
```

<sub>⚡ *"Every pixel tells a story, but every vertex gives it depth."* — Handcrafted by Khaled Amr</sub>

</div>
