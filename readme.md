# 👋 Hi, I’m Cleopas Muchiri

I am a **software engineering** graduate currently expanding my full-stack capabilities at Moringa School. I am **passionate** about building **intelligent systems** and **implementing AI solutions** within the **fintech industry**.

---

## 🚀 What I Do Best
- **🚀 My Philosophy**: I build systems that seamlessly bridge business goals       with user needs. I treat every project as if it were my own, ensuring a          flawless user experience and a beautiful user interface.
  
- **🛠️ How I Learn**: I learn by building, breaking, and rebuilding until I        understand exactly how things work under the hood.

- **📈 Marketing Impact**: I love designing smooth, simple platforms that clearly communicate what an organization does, helping boost their user acquisition and marketing efforts.

---

## 🛠 Tech Stack & Tools
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7E01D?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E44D26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-264DE4?style=for-the-badge&logo=css3&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![cPanel](https://img.shields.io/badge/cPanel-FF6C2C?style=for-the-badge&logo=cpanel&logoColor=white)

---

## 💡 Strengths
- **Project-based problem solving** — I learn by solving real problems, not just theory.
- **Structured thinking** — I avoid “vibe coding” and plan before writing code.
- **Integration specialist** — I can make multiple systems talk to each other smoothly.
- **Persistent debugger** — I don’t give up until the bug is fixed.
- **CSS wizardry** — From pixel-perfect designs to responsive layouts.

---

## 🎯 Interests
- **Backend mastery** — APIs, authentication, scalable architectures.
- **AI & Automation** — Exploring AI for trading, automation, smarter systems.
- **Impact projects** — Donations, education, community outreach.

---

## 📌 Current Focus
- Expanding **full-stack** capabilities in Moringa School
- Migrating GOA [Glory Outreach Assembly](https://goaweb.org) from React.js to Next.js  
- Diving deeper into python and **OOP** (Object Oriented Programing)

---

## 🌟 Pinned Projects

---
### 🌍 [GOA International Website](https://goaweb.org/)

**Description**: Migrated a Kenya-based ministry organization's website from a React/Vite SPA to Next.js, supporting 30+ pages including a full donation and payments flow, media sections, and multi-language content.

**Features**:

- Bilingual (English/German, with French and Swahili planned) via next-intl
- Donation flow with M-Pesa (Daraja API) payment processing
- CMS-driven content via Contentful
- SEO-optimized static export deployed on shared hosting via automated CI/CD (GitHub Actions → FTP → cPanel)

**Tech Stack**: Next.js (App Router), TypeScript, Tailwind CSS, Contentful, PHP (payments/forms backend), GitHub Actions

**Challenge**: Static export was a hard deployment constraint (no persistent Node server on the host), which meant reworking locale routing, metadata generation, and locale detection entirely around Apache-level rules instead of middleware.

---

### 🤖 [AI Job Application Assistant](https://apply-flow-ebon.vercel.app/auth)

Description: An AI-powered system that streamlines job applications — parsing resumes and job postings, scoring candidate-job fit, and generating tailored resume snapshots, cover letters, and emails. Backend is built and deployed; a Chrome extension frontend is next. Currently refining it with an eye toward turning it into a real product.

**Features**:

- Resume and job parsing with structured LLM output
- Candidate-job scoring engine combining rule-based blockers with semantic similarity
- Cover letter and email generation with grounding rules to prevent hallucination
- Skill normalization across equivalent phrasings (e.g. "React" vs "React.js")

**Tech Stack**: FastAPI, instructor (structured LLM output), sentence-transformers, Groq (primary LLM) with OpenRouter fallback, deployed on Render

**Challenge**: Keeping generated content grounded and non-hallucinated while managing LLM cost/rate limits — solved with a compressed prompt architecture and a multi-provider fallback setup.

---

### 🍹 [BarFlow](https://bar-inventory-theta.vercel.app/)

**Description**: A bar inventory and POS system that tracks drinks from stock entry through sale or breakage, with role-based access for staff and support for both cash and mobile payments.

**Features**:

- Intuitive drink-selection interface for attendants
- Cash or M-Pesa payment, recorded automatically
- Pay-later support for tabs settled the next morning
- Role-based access: manager, attendant, bar attendant, cashier

**Tech Stack**: React (frontend), FastAPI (auth + business logic), PostgreSQL, Brevo (transactional email)

 **Challenge**: Keeping orders in sync between the attendant taking requests at the table and the bar attendant fulfilling them at the counter, plus building reliable pay-later settlement logic and M-Pesa integration.

 **Try it**
 
  - Admin - `admin@barflow.com` / `admin123`
  - Manager - `manager@barflow.com` / `manager123`
  - Cashier - `cashier@barflow.com` / `user123`
  - Bar Attender - `barattender@barflow.com` / `user123`
  - Waiter - `waiter@barflow.com` / `user123`
 
---

### 📦 AssetFlow

**Description**: A system for tracking an organization's assets across their full lifecycle — from purchase to retirement or auction — including repairs, servicing, and damage, each requiring proper authorization.

**Features**:

- Asset assignment on purchase
- Repair/servicing/damage tracking with authorization workflows
- Lifecycle status from acquisition through retirement or auction

**Tech Stack**: React, Tailwind CSS (frontend), FastAPI, PostgreSQL (backend, built by a teammate)

**Challenge**: Asset diversity — the system had to handle everything from small consumables to large, high-value assets like land or buildings — while closing tracking loopholes that let items fall off the record.

---


## 📊 GitHub Stats
![Cleopas' GitHub stats](https://github-readme-stats.vercel.app/api?username=CleopasMMuchiri&show_icons=true&theme=tokyonight)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=CleopasMMuchiri&layout=compact&theme=tokyonight)

---

💼 I am actively seeking Entry-Level Full-Stack Developer roles. If you are looking for a dedicated engineer who will know your project inside and out, let's connect!

## 📫 How to Reach Me
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cleopasmmuchiri@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/cleopas-mugane-nairobi)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CleopasMMuchiri)

---

> “The difference between good code and great code is the story it tells.”
