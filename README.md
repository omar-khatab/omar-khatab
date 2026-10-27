<div align="center">

# 👋 Omar Khatab

### Software Developer | Python & JavaScript | React / Next.js

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=22C55E&center=true&vCenter=true&width=800&lines=Software+Developer+%7C+Python+%26+JavaScript;Frontend+Engineer+%7C+React+%2F+Next.js;Automation+Tools+%2B+Modern+Web+Apps;Mechanical+Power+Engineering+Background" />

<br>

<a href="https://portfolio-upgrade-wr9n.vercel.app/"><img src="https://img.shields.io/badge/💼_Portfolio-Live-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/omar-essam-319c/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" /></a>
<a href="mailto:omaressam0870@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail" /></a>

<br>

**Cairo, Egypt • Ain Shams University — Mechanical Power (2024) • NAT - HVAC Systems**

</div>

---

## 🔧 Featured Project — HVAC Engineering Suite [100% Tested]

<div align="center">

### Live: https://hvac-calculator-ebon.vercel.app/

[Next.js](https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=next.js)
[TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?style=flat-square&logo=typescript&logoColor=white)
[Tailwind](https://img.shields.io/badge/Tailwind-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white)
[Tests](https://img.shields.io/badge/tests-8%20passing-brightgreen?style=flat-square)
[Coverage](https://img.shields.io/badge/coverage-100%25-brightgreen?style=flat-square)
[Vitest](https://img.shields.io/badge/tested%20with-vitest-6E9F18?style=flat-square)
[Playwright](https://img.shields.io/badge/E2E-Playwright-2EAD33?style=flat-square&logo=playwright)

</div>

**What it is:** Production-grade HVAC toolkit translating real engineering formulas into a testable, traceable web interface.

**Engineering Highlights:**
- **Separated Logic:** Core formulas isolated in `libs/formulas.ts` for unit testability - no UI coupling
- **100% Coverage:** Stmts, Branch, Funcs, Lines - edge cases `velocity=0`, `cfm=0`, `toBeCloseTo` for float conversions
- **E2E & CI/CD Automation:** 28 Playwright E2E tests, GitHub Actions CI running tests and Lighthouse reporting on every push.
- **Duct Sizing:** Continuity Equation `A = Q / V` + SMACNA-aligned rectangular selection
- **BTU Load:** Field method with sun exposure factors + occupant heat load logic

**[🌐 Live Demo](https://hvac-calculator-ebon.vercel.app/) • [💻 Source Code](https://github.com/omar-khatab/HVAC-Calculator)**

---

## 🐍 Featured Project — File Organizer [Python Desktop App]

<div align="center">

[Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
[PySide6](https://img.shields.io/badge/GUI-PySide6-41CD52?style=flat-square&logo=qt&logoColor=white)
[SQLite](https://img.shields.io/badge/DB-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
[Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
[Version](https://img.shields.io/badge/Version-v3.0-orange?style=flat-square)

</div>

**What it is:** A real-world Windows utility I built to solve my own messy Downloads / Desktop problem. It started as a CLI script and became a full desktop product anyone can use.

**Product Highlights:**
- **Smart Organizing:** Automatically sorts any folder by file type (Images, Docs, Videos, etc.) with duplicate handling and no overwrites
- **Full Desktop GUI:** Dark-theme PySide6 app with live folder watching, preview before organize, undo, drag & drop, and Arabic/English toggle
- **Built for Safety:** Dry-run mode, confirmation prompts, protected-path check, and right-click context menu integration
- **Persistence:** Complete file history and operation log stored in SQLite
- **Two Versions:** CLI version with `argparse` for power users + GUI version for everyone

**[💻 Source Code](https://github.com/omar-khatab/File-Organizer)**

---

## 🛍 Shopify Custom Theme Sections

**Code:** https://github.com/omar-khatab/shopify-custom-sections

- Translated Figma designs into custom Dawn theme sections (Banner + Product Grid with Quick View) using Liquid and Vanilla JS.
- Implemented O(1) hash-map variant selector, Black+Medium cross-sell auto-add, and no-reload header cart refresh.
- Handled async race conditions by locking popups during requests using a feature-branch + PR workflow.

`Liquid` `JavaScript` `Shopify CLI` `Dawn Theme`

---

## 🛒 E-Commerce Store — React

**Live:** https://e-commerce-three-coral-58.vercel.app/ | **Code:** https://github.com/omar-khatab/e-commerce

- Full-featured responsive storefront built with React, React Router, and Context API.
- Integrated live product data from REST API (DummyJSON) with robust error boundaries and skeleton loading states.
- Persisted cart/favorites with `localStorage` and enriched UI with Framer Motion and mobile-first design.

`React` `React Router` `Context API` `Framer Motion` `REST API`

---

## 🛠 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind,python,qt,sqlite,git,github,vercel,vscode" />

<br><br>

**Frontend:** React.js • Next.js • TypeScript • Tailwind CSS • Material UI • Framer Motion  
**Python & Desktop:** Python • PySide6 • SQLite • pathlib / shutil / argparse  
**Testing & Quality:** Vitest • React Testing Library • Playwright • GitHub Actions • Lighthouse CI  
**E-Commerce & Tools:** Shopify (Liquid, Ajax Cart) • Git • GitHub • Vercel

</div>

---

## 🧭 My Journey

```mermaid
graph TD
    A[🌱 HTML CSS JS] --> B[📚 5 Responsive Pages & Admin Dashboard]
    B --> C[⚛ React.js + Context API]
    C --> D[🛒 E-Commerce Store - REST API]
    D --> E[▲ Next.js + TypeScript Strict]
    E --> F[🔧 HVAC Suite - 100% Test Coverage]
    F --> G[🐍 Python Tool - CLI to Desktop GUI]
    G --> H[🚀 Production Ready + Automation + Web]
    
    style A fill:#22C55E,stroke:#000,color:#fff
    style F fill:#22C55E,stroke:#000,color:#fff
    style G fill:#3776AB,stroke:#000,color:#fff
    style H fill:#111827,stroke:#22C55E,color:#fff
