<div align="center">

<!-- ANIMATED OBSIDIAN & EMERALD HEADER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:09090B,55:18181B,100:10B981&height=220&section=header&text=SYAM%20SURESH&fontSize=52&fontColor=FFFFFF&animation=fadeIn&fontAlignY=36&desc=Technical%20Project%20Manager%20%C2%B7%20Business%20Analyst%20%C2%B7%20Full-Stack%20Architect&descAlignY=58&descSize=16" alt="Syam Suresh Header" />

<!-- LIVE TERMINAL TYPING ANIMATION -->
<a href="https://www.syamsuresh.in">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2800&pause=1000&color=10B981&center=true&vCenter=true&width=780&lines=Bridging+Production+Code+%26+Executive+Business+Strategy;Architecting+DPDP+%26+HIPAA+Compliant+Healthcare+Systems+(CareOne);Engineering+60+FPS+Real-Time+Transit+Telemetry+(Cochin+Metro);From+PRD+%26+System+Schema+to+Zero-Trust+Cloud+Deployment" alt="Typing SVG" />
</a>

<br/>

<!-- NAVIGATION & SOCIAL PILLS -->
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-SYAMSURESH.IN-09090B?style=for-the-badge&logo=vercel&logoColor=10B981)](https://www.syamsuresh.in)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-SYAMSURESH-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/syamsuresh/)
[![Behance](https://img.shields.io/badge/BEHANCE-SYAMS11-1769FF?style=for-the-badge&logo=behance&logoColor=white)](https://www.behance.net/syams11)
[![Location](https://img.shields.io/badge/KOCHI,_KERALA-IN-18181B?style=for-the-badge&logo=googlemaps&logoColor=10B981)](#)

</div>

<br/>

<!-- ANIMATED PULSE DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

### `01` // EXECUTIVE SUMMARY

I operate at the intersection of **Product Strategy, Business Analysis, and Full-Stack Systems Engineering**. Rather than treating product management and software engineering as separate handoffs, I own the entire lifecycle—translating complex business requirements into **scalable database schemas, compliant APIs, and minimalist dark-mode interfaces**.

* **Product & Governance:** End-to-end PRD/FRD authoring, Agile sprint orchestration, system architecture audits, and regulatory compliance (**DPDP Act 2023 / HIPAA**).
* **Full-Stack Engineering:** High-concurrency web & mobile applications built with **Next.js, React, TypeScript, Python (FastAPI/Django), and Flutter**.
* **Cloud & Realtime Data:** Event-driven architectures powered by **Supabase, PostgreSQL, Redis, Cloudflare D1, and WebRTC/LiveKit**.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

### `02` // FLAGSHIP PRODUCTION SYSTEMS

<table>
  <tr>
    <td width="50%" valign="top">
      <h3> CareOne (<code>CARE-ONE-</code>)</h3>
      <p>
        <img src="https://img.shields.io/badge/STATUS-PRODUCTION_ARCHITECTURE-10B981?style=flat-square" />
        <img src="https://img.shields.io/badge/SECURITY-DPDP_%26_HIPAA-09090B?style=flat-square" />
      </p>
      <p><strong>Three-Sided Enterprise Healthcare & Continuity-of-Care Ecosystem</strong></p>
      <p>Architected to eliminate fragmented hospital workflows by uniting <strong>Patients, Clinicians, and Hospital Administrators</strong> on a single real-time clinical backbone.</p>
      <ul>
        <li><strong>Patient Experience:</strong> Instant specialist discovery, live OPD token queue tracking, HD tele-consultation via <strong>LiveKit</strong>, and <strong>Razorpay</strong> checkout.</li>
        <li><strong>Clinical & Admin Ops:</strong> One-click longitudinal patient records, structured digital prescriptions, multi-department slot sharding, and immutable audit logs.</li>
        <li><strong>Stack:</strong> <code>React</code> · <code>TypeScript</code> · <code>FastAPI</code> · <code>PostgreSQL</code> · <code>Supabase</code> · <code>Redis</code></li>
      </ul>
      <p><a href="https://github.com/itsmesyaam/CARE-ONE-"><strong>→ View CareOne Repository</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3> Cochin Metro Live Tracker</h3>
      <p>
        <img src="https://img.shields.io/badge/TELEMETRY-60_FPS_REALTIME-10B981?style=flat-square" />
        <img src="https://img.shields.io/badge/GEOSPATIAL-KOCHI_METRO-09090B?style=flat-square" />
      </p>
      <p><strong>Real-Time Urban Transit Telemetry & Geospatial Commuter Engine</strong></p>
      <p>A high-contrast, obsidian dark-mode transit platform built for <strong>Kochi Metro (KMRL)</strong> commuters, replacing static timetables with live corridor intelligence.</p>
      <ul>
        <li><strong>60 FPS Train Motion:</strong> Smooth vector trainset interpolation across the Aluva–Thrippunithura corridor using custom SVG markers.</li>
        <li><strong>Commuter Intelligence:</strong> Live platform arrival countdowns, terminal headway tracking, and an instant station-to-station fare & route calculator.</li>
        <li><strong>Stack:</strong> <code>Next.js</code> · <code>TypeScript</code> · <code>Supabase Realtime</code> · <code>Leaflet / Google Maps</code> · <code>Tailwind CSS</code></li>
      </ul>
      <p><a href="https://github.com/itsmesyaam"><strong>→ View Cochin Metro Project</strong></a></p>
    </td>
  </tr>
</table>

<!-- INTERACTIVE ARCHITECTURE DRAWERS (CLICK TO EXPAND) -->
<details>
<summary><strong> Click to Expand: CareOne & Cochin Metro System Architecture Blueprints</strong></summary>
<br/>

#### 🏥 CareOne — Three-Sided Clinical Architecture
```mermaid
graph LR
    P[Patient Portal] -->|REST / WSS| GW[API Gateway / FastAPI]
    D[Doctor Console] -->|REST / WSS| GW
    A[Admin Command] -->|RBAC Policy| GW
    GW --> DB[(PostgreSQL / Supabase)]
    GW --> R[(Redis Pub/Sub Queue)]
    GW --> LK[LiveKit WebRTC Video]
    GW --> RP[Razorpay Settlement]
