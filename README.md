<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1200&color=22C55E&center=true&vCenter=true&width=620&lines=Santiago+Guerra+%E2%9A%A1;Backend+%26+Database+Architecture;Co-Founder+%40+MetaLevel+Code;Building+Real+Production+Software;Construyendo+Software+a+la+Medida" alt="Santiago Guerra Typing SVG" />
</p>

<p align="center">
  <a href="https://wa.me/573017505981" target="_blank">
    <img src="https://img.shields.io/badge/MetaLevel_Code-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp MetaLevel Code" />
  </a>
  <a href="https://instagram.com/sguerram16" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-%40sguerram16-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Santiago Guerra" />
  </a>
  <a href="mailto:santiguerrapuertas@gmail.com">
    <img src="https://img.shields.io/badge/Email-Directo-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Santiago" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Pereira%2C_Colombia_%F0%9F%87%A8%F0%9F%87%B4-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/Age-18_y%2Fo-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/Education-UTP_Systems_Engineering-0f172a?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Backend_%7C_Databases_%7C_Applied_AI-0f172a?style=flat-square" />
</p>

---

### 🧬 The Essence / La Esencia

> 🇺🇸 *"I don't build toy tutorial projects or paper ideas. I am obsessed with what truly powers a digital product: bulletproof server architecture, absolute database integrity, and applied AI automation that solves real bottlenecks."*
> 
> 🇪🇸 *"No construyo prototipos de tutorial ni ideas en papel. Me obsesiona lo que realmente sostiene a un producto digital: arquitectura de servidor sólida, integridad absoluta en bases de datos y automatización con IA que resuelve cuellos de botella reales."*

<details open>
<summary><b>🇺🇸 English Overview</b></summary>
<br/>

I taught myself to code long before entering university. Today, at 18, I study Systems Engineering at **Universidad Tecnológica de Pereira (UTP)** and I'm the co-founder of **MetaLevel Code**. We build and deliver custom enterprise software featuring real financial transactions, atomic permissions, multi-role dashboards, and offline capabilities.
</details>

<details>
<summary><b>🇪🇸 Resumen en Español</b></summary>
<br/>

Aprendí a programar de forma autodidacta antes de entrar a la universidad. Hoy tengo 18 años, curso Ingeniería de Sistemas en la **Universidad Tecnológica de Pereira (UTP)** y soy cofundador de **MetaLevel Code**. Desarrollamos y entregamos software empresarial a la medida con transacciones financieras reales, permisos atómicos, dashboards multi-rol y tolerancia offline.
</details>

---

### ⏱️ Live Coding Activity / Actividad en Vivo (Hackatime)

<p align="center">
  <a href="https://heatmap.shymike.dev?id=4123&timezone=America/Bogota&standalone=true" title="Click to view detailed daily data / Click para ver datos diarios">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://heatmap.shymike.dev?id=4123&timezone=America/Bogota&theme=dark&labels=true">
      <img alt="Hackatime activity heatmap" src="https://heatmap.shymike.dev?id=4123&timezone=America/Bogota&theme=light&labels=true">
    </picture>
  </a>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=santiguerra&theme=github-dark-blue&hide_border=true&ring=22C55E&fire=22C55E&currStreakLabel=22C55E" alt="GitHub Streak" />
</p>

---

### 🚀 Production Projects & Architecture / Proyectos en Producción

#### 🏋️‍♂️ [Faros Training Center](https://github.com/santiguerra)
> **Enterprise Sports Club Management & Booking PWA / PWA de gestión integral para club deportivo**
- **Stack:** `Next.js 15 (App Router)` `React 19` `Firebase Auth / Firestore / Storage` `Zustand` `Tailwind v4` `PWA`
- 🇺🇸 **Architecture:** 3-tier role system (Student, Coach, Admin). Sensitive financial workflows, subscription quotas, and class limits are calculated strictly server-side using **Firebase Admin SDK** (clients never declare amounts). Hardened Firestore security rules with strict atomic validations. Includes offline attendance taking with offline queue synchronization.
- 🇪🇸 **Arquitectura:** Sistema de 3 roles (Estudiante, Profesor, Admin). Flujo financiero y de suscripciones calculado 100% en el servidor mediante **Firebase Admin SDK** (el cliente nunca declara montos). PWA instalable con funcionamiento offline para toma de asistencia y sincronización automática.

#### 🍽️ [FoodSistem](https://github.com/santiguerra)
> **Real-time Table QR Ordering & Kitchen Operations SaaS / SaaS de pedidos QR en mesa y cocina en tiempo real**
- **Stack:** `React 19 + TypeScript` `Vite` `React Router 7` `Firestore Real-time` `Tailwind v4` `Playwright / Vitest`
- 🇺🇸 **Architecture:** Zero-backend architecture with pure real-time event-driven Firestore synchronization. Domain-driven structure (`client`, `kitchen`, `cashier`, `admin`). Real-time order state machine (pending → prep → ready → served), waiter alerts, and daily cash closing reports adapted for local Colombian currency (COP).
- 🇪🇸 **Arquitectura:** Arquitectura sin servidor intermedio sincronizada en tiempo real mediante Firestore. Estructura modular por dominios (`cliente`, `cocina`, `caja`, `admin`). Máquina de estados para pedidos en tiempo real, alertas de mesero y arqueos de caja diarios (COP).

#### 🤖 [WhatsApp AI Ecosystem](https://github.com/santiguerra)
> **Applied LLM Pipelines & Automated Agent Workflows / Automatización e IA aplicada sobre WhatsApp**
- **Automated Resume & Talent Screener (`filtro_hv_wpp`):**
  - 🇺🇸 End-to-end recruitment bot that processes incoming resumes, extracts candidate parameters, and evaluates fit against job vacancy criteria using multi-LLM orchestration (**Gemini**, **Groq**, **Qwen**, and **xAI**).
  - 🇪🇸 Bot de selección de personal que extrae datos de hojas de vida y califica candidatos contra matrices de vacantes en tiempo real con orquestación multi-modelo (**Gemini**, **Groq**, **Qwen** y **xAI**).
- **Style Persona Cloning Engine:**
  - 🇺🇸 Dynamic prompt engineering engine that parses years of chat exports, computes statistical metrics (burst frequency, length distributions, lexical habits), and feeds an LLM with custom output guardrails to replicate a specific personal writing style without raw data dumps.
  - 🇪🇸 Motor de ingeniería de prompts que analiza años de chats, calcula estadísticas de habla (ráfagas, longitud, muletillas) y alimenta un LLM con filtros de salida para replicar un estilo personal auténtico.

#### ✈️ [Flight Tracker](https://github.com/santiguerra/flight-tracker)
> **Automated Airfare Scraper & Price Monitor / Rastreador y monitor de tarifas aéreas**
- 🇺🇸 Python scraping engine that continuously queries flight availability, tracks pricing volatility, and triggers automated alerts.
- 🇪🇸 Motor en Python para monitoreo recurrente de vuelos y alertas automáticas de mejores tarifas.

---

### 🛠️ Technical Arsenal / Arsenal Técnico

<table>
  <tr>
    <td valign="top" width="25%">
      <strong>Backend & Databases</strong><br><br>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/Firebase_Admin-FFCA28?style=flat-square&logo=firebase&logoColor=black" /><br>
      <img src="https://img.shields.io/badge/Cloud_Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black" /><br>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <strong>Frontend & PWA</strong><br><br>
      <img src="https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" /><br>
      <img src="https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/Zustand-443e38?style=flat-square&logo=react&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/PWA_Offline-5A0FC8?style=flat-square&logo=pwa&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <strong>Applied AI & Tooling</strong><br><br>
      <img src="https://img.shields.io/badge/Google_Gemini-8E75C2?style=flat-square&logo=googlegemini&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/Groq_Cloud-F55036?style=flat-square&logo=fastapi&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/Prompt_Engineering-22C55E?style=flat-square&logo=openai&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/WhatsApp_Web.js-25D366?style=flat-square&logo=whatsapp&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <strong>Testing & Systems</strong><br><br>
      <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/Git_&_GitHub-181717?style=flat-square&logo=github&logoColor=white" /><br>
      <img src="https://img.shields.io/badge/Linux_/_macOS-FCC624?style=flat-square&logo=linux&logoColor=black" />
    </td>
  </tr>
</table>

---

### 🏢 MetaLevel Code

<p>
  <strong>🇺🇸 MetaLevel Code:</strong> We design and build bespoke software solutions: from point-of-sale and administrative systems to full-scale web platforms with online payments, role-based workflows, and AI automation.
  <br><br>
  <strong>🇪🇸 MetaLevel Code:</strong> Diseñamos y desarrollamos soluciones de software a la medida: desde sistemas administrativos y puntos de venta hasta plataformas completas con pasarelas de pago, roles y flujos automatizados con IA.
</p>

- 📱 **WhatsApp (MetaLevel Code):** [+57 301 7505981](https://wa.me/573017505981)
- 📸 **Instagram (Personal):** [@sguerram16](https://instagram.com/sguerram16)
- ✉️ **Direct Email:** [santiguerrapuertas@gmail.com](mailto:santiguerrapuertas@gmail.com)

<p align="center">
  <sub>Built with real code, terminal hours, and passion for solid engineering. • Construido con código real y pasión por la ingeniería bien hecha.</sub>
</p>
