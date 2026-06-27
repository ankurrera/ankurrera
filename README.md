# Hi there! I'm Ankur Bag <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28px" alt="Waving Hand">

<p align="left">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&duration=3000&pause=1000&color=58A6FF&width=650&lines=B.Tech+Computer+Science+Graduate;Flutter+%26+Mobile+Engineer;Full+Stack+Software+Engineer;Building+Offline-First+Ecosystems;TypeScript+%7C+Dart+%7C+Python" alt="Typing SVG" />
</p>

I am a **Computer Science & Engineering graduate** (Class of 2026) passionate about building high-performance mobile applications, robust full-stack architectures, real-time telemetry pipelines, and edge computer vision. I thrive on solving complex state-synchronization problems, offline-first reliability, and end-to-end software design.

---

### 🎓 Academic & Professional Focus
- **Degree:** B.Tech in Computer Science & Engineering (Graduating Summer 2026)
- **Specializations:** Mobile Application Development (Flutter), Relational & Real-Time Databases, Computer Vision Pipelines, and Offline-First Architectures.
- **Goal:** Designing robust, scalable systems that bridge the gap between polished user interfaces and complex database layers.

---

### 🛠️ Tech Stack & Tools

<table>
  <tr>
    <td valign="top" width="50%">
      <strong>Languages:</strong><br/>
      <img src="https://skillicons.dev/icons?i=dart,ts,js,python,cpp,html,css" height="36" />
    </td>
    <td valign="top" width="50%">
      <strong>Frameworks & Libraries:</strong><br/>
      <img src="https://skillicons.dev/icons?i=flutter,react,nextjs,nodejs,express,tailwind,fastapi" height="36" />
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <strong>Databases & Cloud:</strong><br/>
      <img src="https://skillicons.dev/icons?i=supabase,postgres,mysql,sqlite,firebase,vercel" height="36" />
    </td>
    <td valign="top" width="50%">
      <strong>Developer Tools & OS:</strong><br/>
      <img src="https://skillicons.dev/icons?i=git,github,vscode,androidstudio,figma,postman,docker" height="36" />
    </td>
  </tr>
</table>

**Computer Vision & ML:** OpenCV | YOLOv8 (Pose) | ByteTrack

---

### 🚀 Featured Engineering Projects

#### 🍛 [Mother's Hut](https://github.com/OrbitInnovations/Mothers-Hut) — Enterprise Restaurant Operating System
*A full-stack, cloud-native ERP monorepo (Melos) coordinating 5 client applications with a Supabase PostgreSQL backend.*
- **Offline-First Sync Engine:** Developed a local transactional queue using **Drift (SQLite)** to buffer POS and Kitchen Display System (KDS) operations, synchronizing changes chronologically with database-level idempotency key gating on connection recovery.
- **Telemetry & Track Coalescing:** Designed batch GPS logging that queues coordinates locally and uploads them in blocks of 10 every 60s, reducing telemetry database write traffic by **90%** and preventing WebSocket connection exhaustion.
- **Production Gating & Security:** Enforced Row-Level Security (RLS) across 54 tables and restricted critical state mutations to audited PostgreSQL RPCs to maintain financial compliance.
- **Tech Stack:** Flutter, Supabase, PostgreSQL 15, Drift (SQLite), Riverpod, pg_cron, Melos.

#### 🏥 [CareSync](https://github.com/ankurrera/CareSync) — Biometric E-Prescription & Medical Logging Platform
*A secure, HIPAA-compliant medical logging app facilitating patient, doctor, pharmacist, and first-responder interactions.*
- **Two-Factor Biometrics:** Integrated native hardware biometric authentication (Face ID/Fingerprint) with cloud-based face verification (**Azure Face API**) for secure identity verification.
- **Emergency QR System:** Created a secure QR pipeline allowing first responders instant access to patient medical summaries without credentials.
- **State & Data Integrity:** Structured reactive application state with **Riverpod** and decoupled database schema constraints on Supabase.
- **Tech Stack:** Flutter, Supabase, Azure Face API, Riverpod, PostgreSQL.

#### 👁️ [AuraSense](https://github.com/ankurrera/aurasense) — Camera-Based Activity Monitoring System
*A modern proof-of-concept employee engagement tracking system processing edge camera feeds in real time.*
- **Computer Vision Pipeline:** Built an OpenCV capture system that feeds frames into a **YOLOv8-Pose** keypoint estimator and filters individual tracking tracks using **ByteTrack**.
- **Engagement Classification:** Developed a state machine running Exponential Moving Average (EMA) landmark smoothing to classify subject states as Working, Idle, or Absent, translating to a daily productivity index.
- **API & Analytics:** Built a **FastAPI** web server (SQLAlchemy, MySQL) to stream telemetry to a glassmorphic dashboard (HTML/CSS/JS) styled with Chart.js.
- **Tech Stack:** Python, OpenCV, YOLOv8-Pose, ByteTrack, FastAPI, SQLAlchemy, MySQL, Chart.js.

#### 🎮 [Solo Leveling](https://github.com/ankurrera/SoloLeveling) — Gamified Fitness Tracker
*A web application that gamifies workouts, prompting users to log exercises and complete quests to level up.*
- **Interactive Interface:** Implemented a dark-themed, responsive dashboard using **React 18**, **Vite**, **TypeScript**, **Shadcn UI**, and **Tailwind CSS**.
- **Data Query Caching:** Leveraged **TanStack React Query** for server-state caching, minimizing redundant API roundtrips.
- **Tech Stack:** React, Vite, TS, Shadcn UI, TanStack Query, Supabase.

#### 💼 [Creative Portfolio & Content Management System](https://github.com/ankurrera/portfolio-v3-main)
*A high-performance personal web portal and headless CMS bridging software engineering with professional photography & fashion production.*
- **Next.js & Supabase Engine:** Built with Next.js App Router for low-latency server-side rendering (SSR) and dynamic routing.
- **Image Optimization:** Designed an on-the-fly media optimization pipeline converting raw imagery to highly compressed WebP formats, reducing LCP by **60%** for rich visual showcases.
- **Tech Stack:** Next.js, React 18, Tailwind CSS, Supabase, Vercel Serverless.

#### 🎓 ScholarX — Academic Resource & Prep Engine
*A web platform serving engineering students with academic resources, syllabus mappings, and examination prep tools.*


### 🤝 Let's Connect!

<p align="left">
  <a href="https://linkedin.com/in/ankurrera" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://x.com/ankurrera" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
  <a href="mailto:ankurr.era@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/>
  </a>
</p>

> "Disciplined systems design, clean architecture, and exceptional user experiences build products that last."
