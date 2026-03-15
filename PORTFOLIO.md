# GitHub Portfolio — ShiningDespair

> Full-stack developer with experience across web, mobile, desktop, and game development.
> Comfortable working across TypeScript, C#, Java, Python, and R ecosystems.

---

## Commercial & Freelance Projects

### [MijnButik E-Commerce Platform](https://github.com/ShiningDespair/MijnButik-Publish)
`Next.js` `React` `TypeScript`

Custom e-commerce storefront built for MijnButik. Focused on performance, SEO optimization, and customer experience. Includes a separate [admin panel](https://github.com/ShiningDespair/MijnButik-Admin-Publish) built with Next.js.

---

### Mijn Sistem — Business Management Software
`TypeScript` `C#` `Next.js`

Full-stack business management platform developed for Mijn Sistem. Consists of multiple services:
- [`Mijn-Sistem-Frontend`](https://github.com/ShiningDespair/Mijn-Sistem-Frontend) — Customer-facing frontend
- [`mijn-sistem-backend`](https://github.com/ShiningDespair/mijn-sistem-backend) — C# backend API
- [`Mijn-Sistem-AdminPaneli`](https://github.com/ShiningDespair/Mijn-Sistem-AdminPaneli) — Admin panel

---

### Mijn Kitap Evi — Online Bookstore
`TypeScript` `C#` `Next.js`

Full-stack bookstore platform with separate frontend, backend, and admin panel:
- [`Mijn-KitapEvi-FrontEnd`](https://github.com/ShiningDespair/Mijn-KitapEvi-FrontEnd) — Customer frontend
- [`Mijn-KitapEvi-Backend`](https://github.com/ShiningDespair/Mijn-KitapEvi-Backend) — C# REST API
- [`Mijn-Kitap-Evi-AdminPaneli`](https://github.com/ShiningDespair/Mijn-Kitap-Evi-AdminPaneli) — Admin dashboard

---

### [Desibona OpenCart](https://github.com/ShiningDespair/Desibona-OpenCart)
`PHP` `Docker`

E-commerce infrastructure for Desibona, built on OpenCart. Configured to run on Docker with a focus on performance, security, and scalability. Includes a companion [BirFatura API integration](https://github.com/ShiningDespair/desibona-birfatura-api) for invoicing.

---

### [DHS Yazılım Website](https://github.com/ShiningDespair/DhsWebsite)
`Next.js` `TypeScript`

Marketing and sales website for DHS Yazılım, built to showcase and sell SaaS products. Based on a premium Next.js startup template, customized for the team's brand.

---

### Proaktif24 — Brand Monitoring & Reputation Management Platform
`Java 21` `Spring Boot 4` `MySQL` `React Native` `Expo` `TypeScript`

A full SaaS platform for real-time brand and reputation monitoring across digital media and social platforms. Built across two repos under the `proaktif24-group` org.

**Backend — [`proaktif24-app-spring`](https://github.com/proaktif24-group/proaktif24-app-spring)**
`Java 21` `Spring Boot 4.0` `MySQL` `Flyway` `Spring Security` `JWT` `OpenAI SDK` `Caffeine Cache` `Swagger/OpenAPI`

- REST API with Spring Security + JWT authentication
- Flyway-managed database migrations
- **OpenAI integration** for AI-driven content and semantic analysis
- **Scheduled keyword analysis** — automated risk scoring and semantic aggregation via Spring scheduler
- **Early warning system** — risk dashboard with per-platform risk levels, radar view, and trend feeds
- Bot campaign management (create, track, and update automated content campaigns)
- Customer profile management and subscription handling
- Caffeine caching layer for performance-sensitive endpoints
- Spring Actuator for health monitoring, Swagger UI for API docs

**Mobile — [`GSB-Marka-Yonetimi`](https://github.com/ShiningDespair/GSB-Marka-Yonetimi)** *(app name: Proaktif 24)*
`Expo 54` `React Native 0.81` `TypeScript` `Redux Toolkit` `NativeWind` `Victory Native`

- Cross-platform mobile app (iOS + Android) built with Expo Router
- **Digital media analytics** — category performance, hourly/weekly analysis, sentiment analysis, source activity heatmaps, peak hour detection, tone maps
- **Instagram analytics** — account activity, behavior diversity, daily/monthly trends, activity heatmaps
- **Feature modules** — anomaly detection, crime detection, monitoring, reputation status/recovery, risk analysis, scenario analysis, semantic analysis
- **AI Chatbot** screen for natural language interaction with brand data
- Projects dashboard with per-project analytics drill-down
- Secure token storage with `expo-secure-store`, JWT auth, PDF/Excel export support

---

## Sustainability & Environmental Projects

### [ATIS-KATIS](https://github.com/ShiningDespair/ATIS-KATIS) — Industrial & Hazardous Waste Tracking System · [Demo](https://github.com/ShiningDespair/atis-katis-demo)
`ASP.NET Core 9` `PostgreSQL` `Redis` `Next.js 16` `React Native` `Expo` `Docker`

Full-stack monorepo for tracking and managing industrial/hazardous waste across multiple organizations and sites. Three separate platforms share a single backend API. Deployed via Docker Compose with 8 containerized services.

**Backend**
`ASP.NET Core 9.0` `Entity Framework Core` `PostgreSQL 16` `Redis` `SignalR` `SeaweedFS (S3)` `JWT`

- 25 REST controllers covering the full domain: waste codes, packaging types, waste units, firms, institutions, users, approvals, statistics, file uploads, notifications, support tickets, and more
- 40+ database tables managed with EF Core migrations
- **SignalR `NotificationHub`** for real-time push notifications to connected clients
- **SeaweedFS** (S3-compatible) for distributed file storage
- **Redis** caching layer for performance
- JWT-based auth with role-based access control (6 roles)
- Email templating with Handlebars.Net
- Swagger/OpenAPI documentation auto-generated

**Web Frontend**
`Next.js 16` `React 19` `TypeScript` `Tailwind CSS 4` `shadcn/Radix UI` `Redux Toolkit + RTK Query` `Recharts` `SignalR`

- Role-based views: Admin, Sender (SahaPersoneli), Receiver, Security (GuvenlikPersoneli), Company Manager
- Real-time notifications via SignalR client
- 16 RTK Query API slices for data fetching and cache management
- Data export to PDF (jsPDF) and Excel (ExcelJS)
- Fully responsive, dark-mode aware UI with Radix primitives

**Mobile**
`Expo 54` `React Native 0.81` `NativeWind` `Redux Toolkit` `Expo Router`

- Native iOS and Android app with file-based routing via Expo Router
- Shared Redux store with RTK Query API slices mirroring the web client
- Axios interceptors for auth token injection and refresh

**Domain**
Tracks 6 waste form types: Solid Waste (KatıAtık), Wastewater (AtıkSu), Drinking Water (İçmeSuyu), Machinery (İşMakinesi), Lab Wastewater Analysis, Field Wastewater Analysis.

Each form follows a multi-step approval lifecycle: Draft → Awaiting Security Approval → Awaiting Firm Approval → Approved → Completed (or Rejected at any step).

**Infrastructure**
Docker Compose orchestrates 8 services: backend, frontend, PostgreSQL, Redis, SeaweedFS, pgAdmin, Portainer, Netdata.

---

### [ESG Final Project](https://github.com/ShiningDespair/ESG-Final-Project)
`TypeScript`

Final project focused on ESG (Environmental, Social, Governance) reporting and tracking.

---

### [EcoTrack Enterprise](https://github.com/ShiningDespair/EcoTrack-Enterprise)

Enterprise-level sustainability tracking application.

---

### [SustainView App](https://github.com/ShiningDespair/sustain-view-app)
`TypeScript`

Sustainability data visualization app built with Lovable.

---

## AI & Machine Learning

### [Skin Cancer Detection — Meta Analysis](https://github.com/ShiningDespair/Skin-Cancer-Detection-Meta-Analysis)
`Python` `Jupyter Notebook`

**Graduation project.** Analyzes and compares different skin cancer detection algorithms. A meta-analysis approach to benchmarking ML models for medical imaging classification.

---

### [Brain Cancer Classification](https://github.com/ShiningDespair/BrainCancerClassification)
`Python` `Jupyter Notebook`

Machine learning project for classifying brain cancer from data/imaging using Jupyter Notebook.

---

## Web & Full-Stack Applications

### [UniSkor Remake](https://github.com/ShiningDespair/UniSkor-Remake)
`ASP.NET Core` `Vite.js`

Modernized rebuild of the UniScore university scoring application using ASP.NET Core backend and Vite.js frontend.

---

### [UniScore](https://github.com/ShiningDespair/UniScore)
`JavaScript`

Original university scoring application. Allows users to score and compare Turkish universities using a custom dataset.

---

### [Llama Chat App](https://github.com/ShiningDespair/Llama-Chat-App)
`C#` `.NET` `React`

Chat application powered by a local Llama LLM, with a .NET backend and React frontend.

---

### Soundchart
`TypeScript` `C#` `JavaScript`

Software Architecture course project, split across:
- [`Soundchart`](https://github.com/ShiningDespair/Soundchart) — TypeScript frontend
- [`sound-chart`](https://github.com/ShiningDespair/sound-chart) — JavaScript frontend (earlier version)
- [`sound-chart-backend`](https://github.com/ShiningDespair/sound-chart-backend) — C# backend API

---

### [Turkey Map React](https://github.com/ShiningDespair/turkey-map-react)
`JavaScript` `React`

Open-source React component providing an interactive city map of Turkey. Drop-in ready for React applications.

---

## Tools & Rapid Prototypes

### [Dinamik Rapor Oluşturucu](https://github.com/ShiningDespair/v0-dinamik-rapor-olusturucu)
`TypeScript` · Deployed on Vercel

Dynamic report generator built with v0.app and deployed on Vercel. Synced with v0 deployments automatically.

---

### [Stats to Stories](https://github.com/ShiningDespair/stats-to-stories)
`TypeScript`

Converts statistical data into narrative stories. Built with Lovable.

---

### [Dice Roll Studio](https://github.com/ShiningDespair/dice-roll-studio)
`TypeScript`

Dice rolling utility/studio application. Built with Lovable.

---

### [Project Harmony](https://github.com/ShiningDespair/project-harmony)
`TypeScript`

Collaborative project management tool. Built with Lovable.

---

## Academic & Course Projects

### [ShinyApp — Business Data Dashboard](https://github.com/ShiningDespair/ShinyApp)
`R` `Shiny`

Interactive business analytics dashboard built for a Data Analysis in Business course. Uses the Chinook sample database for visualizations.

---

### [Ecommerce Stock App](https://github.com/ShiningDespair/Ecommerce_Stock)
`Java` `Java Swing` `MySQL`

Desktop e-commerce and stock management application built for an Algorithm Design and Analysis course. GUI built with Java Swing, data layer with MySQL.

---

## Game Development

### [DuckTale](https://github.com/ShiningDespair/DuckTale)
`C#` `Unity`

Main game project by Duckheads Development team. ⭐ 1 star.

---

### [DuckTale — Global Game Jam](https://github.com/ShiningDespair/DuckTaleGGJ)
`C#` `Unity`

Game jam entry submitted to Global Game Jam (GGJ03) by the Duckheads team.

---

### [ClickyCrates](https://github.com/ShiningDespair/ClickyCrates)
`C#` `Unity`

Game project built as part of Unity's "Create With Code" learning program.

---

### [Metapiens Brackeys Tutorial](https://github.com/ShiningDespair/Metapiens-Brackeys-Tutorial)
`C#` `Unity`

Tutorial follow-along project (Brackeys) for building Unity skills for the Metapiens project.

---

## Open Source Contributions / Forks

### [docker-minecraft-server](https://github.com/ShiningDespair/docker-minecraft-server)
`Shell` `Docker`

Fork of the popular Docker image that runs a Minecraft Java Edition server with automatic version and modpack management at startup.

---

*Last updated: March 2026*
