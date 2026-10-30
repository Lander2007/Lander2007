<div align="center">

  <img src="./assets/banner.svg" alt="Khaled Amr — Form / Shift" width="100%" />

  <br><br>

  <p align="center">
    <a href="#01--about--form--shift">About</a>
    &nbsp;&nbsp;&bull;&nbsp;&nbsp;
    <a href="#02--work--selected-systems">Work</a>
    &nbsp;&nbsp;&bull;&nbsp;&nbsp;
    <a href="#03--capabilities--engineering-arsenal">Capabilities</a>
    &nbsp;&nbsp;&bull;&nbsp;&nbsp;
    <a href="#04--contact--direct-dispatch">Contact</a>
    &nbsp;&nbsp;&bull;&nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/kh%E1%A5%B2%E1%A5%A3%E1%A5%B1d-amr-263334343/">LinkedIn ↗</a>
  </p>

</div>

---

## 01 // ABOUT &bull; FORM / SHIFT

> *“I build interactive digital experiences through code, design, and motion.”*

<br>

<table width="100%" border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td width="58%" valign="top">
      <h3>Turning Ideas Into Interfaces</h3>
      <p>
        Software engineer focused on high-performance frontend engineering, spatial computing, and real-time 3D web systems. Specialized in executing continuous 60 FPS graphics pipelines on the web through Three.js, React Three Fiber, and custom WebGL shaders, paired with robust, type-safe full-stack backbones.
      </p>
    </td>
    <td width="42%" valign="top">
      <h3>Studio Telemetry</h3>
      <p>
        <strong>Identity:</strong> Khaled Amr &bull; Form / Shift<br>
        <strong>Discipline:</strong> Real-Time 3D &amp; Frontend Architecture<br>
        <strong>Flagship:</strong> SpaceEdu Simulation Architecture<br>
        <strong>Runtime:</strong> React &bull; TypeScript &bull; Vite &bull; PostgreSQL<br>
        <strong>Base:</strong> Cairo, Egypt [UTC+2]<br>
        <strong>Status:</strong> Active &bull; Open for select mandates
      </p>
    </td>
  </tr>
</table>

---

## 02 // WORK &bull; SELECTED SYSTEMS

<details open>
<summary><strong>01 / SpaceEdu &mdash; Real-Time Celestial Simulation Platform &amp; AI Copilot</strong></summary>
<br>

*An interactive 3D astrophysics simulation environment engineered to render large-scale astronomical systems natively in the browser at a persistent 60 frames per second.*

<p>
  <img src="https://img.shields.io/badge/THREE.JS-381932?style=for-the-badge&logo=three.js&logoColor=C6F277" alt="Three.js" />
  <img src="https://img.shields.io/badge/REACT_THREE_FIBER-381932?style=for-the-badge&logo=react&logoColor=C6F277" alt="R3F" />
  <img src="https://img.shields.io/badge/WEBGL_&_SHADERS-381932?style=for-the-badge&logo=opengl&logoColor=C6F277" alt="WebGL" />
  <img src="https://img.shields.io/badge/TYPESCRIPT-381932?style=for-the-badge&logo=typescript&logoColor=C6F277" alt="TypeScript" />
  <img src="https://img.shields.io/badge/VITE-381932?style=for-the-badge&logo=vite&logoColor=C6F277" alt="Vite" />
</p>

```
+---------------------+      Draw Call Batching      +-----------------------------+
| Viewport Controller | ---------------------------> | React Three Fiber Scene     |
+---------------------+                              +-----------------------------+
           |                                                        |
           v                                                        v
+---------------------+       Context-Aware Streams  +-----------------------------+
| Keplerian Physics   | <--------------------------- | ARIA AI Autonomous Guidance |
+---------------------+                              +-----------------------------+
```

### Architectural Decisions &amp; Engineering Highlights
- **Instanced Geometry Pipeline:** Replaced individual mesh render passes with instanced buffer geometry for asteroid belts and stellar dust, shrinking GPU draw calls from ~1,200 to under 10 passes per frame.
- **Custom Shading Models:** Implemented GLSL vertex and fragment shaders for planetary atmospheric Rayleigh scattering, dynamic solar corona emissions, and planetary axial light falloff.
- **Physics Engine Integration:** Real-time n-body and Keplerian orbit calculations executing in dedicated animation frames, maintaining mathematical stability across orbital trajectories.
- **Autonomous AI Copilot (ARIA):** Integrated context-aware conversational AI streamed to a customized heads-up display (HUD), dynamically resolving user astrophysics queries based on active viewport coordinates.

</details>

<br>

<details>
<summary><strong>02 / King-Store &mdash; High-Throughput E-Commerce Platform &amp; Administration Suite</strong></summary>
<br>

*A full-stack, enterprise-grade storefront designed for international distribution, sub-second page rendering, and real-time inventory telemetry.*

<p>
  <img src="https://img.shields.io/badge/REACT-381932?style=for-the-badge&logo=react&logoColor=C6F277" alt="React" />
  <img src="https://img.shields.io/badge/TYPESCRIPT-381932?style=for-the-badge&logo=typescript&logoColor=C6F277" alt="TypeScript" />
  <img src="https://img.shields.io/badge/TAILWIND_CSS-381932?style=for-the-badge&logo=tailwindcss&logoColor=C6F277" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/REST_GATEWAY-381932?style=for-the-badge&logo=fastapi&logoColor=C6F277" alt="REST" />
</p>

### Architectural Decisions &amp; Engineering Highlights
- **Internationalization (i18n) Engine:** Dynamic layout mirroring and locale switching supporting right-to-left (RTL) and left-to-right (LTR) typography with zero layout recalculation overhead.
- **Optimistic State Pipeline:** Decoupled cart and checkout state logic ensuring zero unnecessary component re-renders across deep product trees and sub-second transaction states.
- **Administrative Telemetry Dashboard:** Real-time operational console for catalog CRUD, order lifecycle monitoring, dynamic inventory synchronization, and sales velocity metrics.

</details>

<br>

<details>
<summary><strong>03 / Warehouse Management System &mdash; High-Reliability LAN Architecture</strong></summary>
<br>

*A low-latency inventory management architecture engineered for high concurrency across local area networks (LAN) within industrial logistics operations.*

<p>
  <img src="https://img.shields.io/badge/NODE.JS-381932?style=for-the-badge&logo=nodedotjs&logoColor=C6F277" alt="Node.js" />
  <img src="https://img.shields.io/badge/EXPRESS-381932?style=for-the-badge&logo=express&logoColor=C6F277" alt="Express" />
  <img src="https://img.shields.io/badge/POSTGRESQL-381932?style=for-the-badge&logo=postgresql&logoColor=C6F277" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/LAN_CONCURRENCY-381932?style=for-the-badge&logo=wireguard&logoColor=C6F277" alt="LAN" />
</p>

### Architectural Decisions &amp; Engineering Highlights
- **Transactional Consistency:** ACID-compliant PostgreSQL schema with row-level locking routines, eliminating race conditions during concurrent barcode scans across multi-station terminals.
- **Network Resilience:** Structured to sustain zero data loss in intermittent LAN connectivity conditions with automated reconciliation protocols.
- **Access Control &amp; Audit Logs:** Role-based access control (RBAC) separating station operators, dispatch coordinators, and system administrators with tamper-evident audit trails.

</details>

---

## 03 // CAPABILITIES &bull; ENGINEERING ARSENAL

### Core Technologies

<p>
  <img src="https://img.shields.io/badge/THREE.JS-381932?style=for-the-badge&logo=three.js&logoColor=C6F277" alt="Three.js" />
  <img src="https://img.shields.io/badge/REACT_THREE_FIBER-381932?style=for-the-badge&logo=react&logoColor=C6F277" alt="R3F" />
  <img src="https://img.shields.io/badge/WEBGL_&_SHADERS-381932?style=for-the-badge&logo=opengl&logoColor=C6F277" alt="WebGL" />
  <img src="https://img.shields.io/badge/REACT_18+-381932?style=for-the-badge&logo=react&logoColor=C6F277" alt="React" />
  <img src="https://img.shields.io/badge/TYPESCRIPT-381932?style=for-the-badge&logo=typescript&logoColor=C6F277" alt="TypeScript" />
  <img src="https://img.shields.io/badge/NEXT.JS-381932?style=for-the-badge&logo=nextdotjs&logoColor=C6F277" alt="Next.js" />
  <img src="https://img.shields.io/badge/VITE-381932?style=for-the-badge&logo=vite&logoColor=C6F277" alt="Vite" />
  <img src="https://img.shields.io/badge/TAILWIND_CSS-381932?style=for-the-badge&logo=tailwindcss&logoColor=C6F277" alt="Tailwind" />
  <img src="https://img.shields.io/badge/NODE.JS-381932?style=for-the-badge&logo=nodedotjs&logoColor=C6F277" alt="Node" />
  <img src="https://img.shields.io/badge/POSTGRESQL-381932?style=for-the-badge&logo=postgresql&logoColor=C6F277" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/FIGMA-381932?style=for-the-badge&logo=figma&logoColor=C6F277" alt="Figma" />
  <img src="https://img.shields.io/badge/GIT-381932?style=for-the-badge&logo=git&logoColor=C6F277" alt="Git" />
</p>

<br>

| Domain | Core Stack | Implementation Discipline |
| :--- | :--- | :--- |
| **Real-Time 3D &amp; Motion** | Three.js, React Three Fiber, GLSL, WebGL | Buffer geometry instancing, procedural shaders, camera rigs, 60 FPS enforcement |
| **Frontend Architecture** | React 18+, TypeScript, Next.js, Vite | Immutable state patterns, frame budget enforcement, strict typing, modular hooks |
| **Interface Design** | Tailwind CSS, Motion, Figma | High-contrast editorial systems, tactile micro-interactions, responsive typography |
| **Backend &amp; Persistence** | Node.js, Express, PostgreSQL, REST | ACID transaction pipelines, query optimization, connection pooling, RBAC |
| **Engineering Workflow** | Git, Docker, Bash, Linux / Unix | Deterministic build pipelines, semantic versioning, containerization, linting |

---

## 04 // CONTACT &bull; DIRECT DISPATCH

| Channel | Destination / Endpoint | Purpose |
| :--- | :--- | :--- |
| **Electronic Mail** | [kaledamr457@gmail.com](mailto:kaledamr457@gmail.com) | Direct contracts, consulting, technical proposals |
| **LinkedIn Network** | [Khaled Amr](https://www.linkedin.com/in/kh%E1%A5%B2%E1%A5%A3%E1%A5%B1d-amr-263334343/) | Professional credentials, references, and network |
| **Version Control** | [@Lander2007](https://github.com/Lander2007) | Open-source source code, architecture patterns, commits |

<br>

```bash
$ curl -s https://api.github.com/users/Lander2007 | jq '{name, studio, specialization, location}'
{
  "name": "Khaled Amr",
  "studio": "Form / Shift",
  "specialization": "Frontend & Real-Time 3D Web",
  "location": "Cairo, Egypt",
  "availability": "Available for contractual mandates and engineering roles"
}
```

<br><br>

<div align="center">

  <img src="./assets/footer.svg" alt="Khaled Amr — Form / Shift Footer" width="100%" />

  <br>

  <sub>Khaled Amr &bull; Form / Shift &bull; Cairo, Egypt &bull; All Systems Nominal</sub>

</div>
