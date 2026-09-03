# 👋 Hi, I'm Aslan Yusuf Zeybek; (EN)

### 🎓 About Me

I'm a Computer Engineering student at **Galatasaray University** (GPA: 3.38/4.00) with a strong passion for full-stack software engineering, applied artificial intelligence (LLMs & RAG), systems design, and digital hardware architecture. 

During my software engineering internship, I designed and developed an enterprise-grade internal portal and employee management system. I am also an alumnus of the **Akbank Generative AI Bootcamp** (Global AI Hub). I am trilingual, fluent in Turkish, English, and French (DELF B2 certified).

---

### 💡 Technologies I Know

- **Programming Languages:** Python, Java, C, Verilog, JavaScript/TypeScript, SQL, HTML5/CSS3
- **AI & LLM Engineering:** LangChain, Google Gemini API (Gemini 2.0 Flash), Chroma DB, RAG (Retrieval-Augmented Generation), Text Embeddings, Prompt Engineering
- **Backend & Web Frameworks:** FastAPI, Spring Boot (Spring Security, Spring Data JPA, Hibernate), Streamlit, Uvicorn, RESTful APIs
- **Frontend & UI Engineering:** React (Vite), TradingView Lightweight Charts, CustomTkinter, Jinja2, Responsive Glassmorphism UI
- **Systems, Networking & Hardware:** Basys 3 FPGA, Vivado, P2P LAN Streaming, PostgreSQL, SQLite, Pandas, NumPy, MSS, Pillow, pynput
- **Tools & DevOps:** Git, GitHub, VS Code, IntelliJ IDEA, Maven, Docker, Docker Compose, Linux / Bash

---

### 🚀 Projects

#### 1. 🏢 Enterprise Portal — Full-Stack Corporate Operations & Workforce Suite
*A comprehensive, multi-tiered enterprise management platform engineered to centralize workforce directory operations, meeting room allocations, equipment inventory, and administrative workflows.*
- **Three-Tier Architecture:** Built on a decoupled stack featuring a **Spring Boot** REST API, a responsive **React (Vite)** single-page application, and a **PostgreSQL** relational database.
- **Adaptive RBAC & Governance:** Dual-layer Role-Based Access Control (`ADMIN`, `MANAGER`, `EMPLOYEE`) with automatic administrative view unlocking and strict self-approval prevention rules for leave/hardware requests.
- **Resource Collision Engine:** Interactive meeting room scheduler (09:00–18:00) with client-side real-time conflict checking (`useMemo`) paired with strict server-side transaction validation.
- **Business Rule Automation:** Working-day leave calculator with automatic weekend exclusion, dynamic hierarchical organizational tree directory, and corporate announcement boards with cascading database integrity (`orphanRemoval = true`).

#### 2. 📚🤖 Türkçe Kitap Chatbot — AI-Powered Semantic Book Discovery Assistant
*A personalized literary recommendation and conversational advisor driven by Retrieval-Augmented Generation (RAG) over a large-scale Turkish literature database.*
- **Domain-Specific Dataset:** Ingests and indexes over **60,000+ curated Turkish books** sourced from the YTÜ COSMOS Turkish Book Dataset.
- **Semantic Vector Pipeline:** Built with **Chroma DB** and **Google Text Embedding 004** to enable low-latency semantic search and contextual genre matching.
- **GenAI Conversational Engine:** Powered by **Google Gemini 2.0 Flash** via **LangChain**, featuring multi-turn conversation memory, category filtering, and contextual book synthesis.
- **User Interface:** Clean, interactive **Streamlit** dashboard delivering instant query responses and categorized book suggestions.

#### 3. 📈⚡ Stock Viewer — Institutional Financial Terminal & Market Intelligence Engine
*A high-performance equity analytics workstation, institutional technical charting canvas, and automated market intelligence engine.*
- **Hardware-Accelerated Charting:** 60 FPS candlestick canvas powered by **TradingView Lightweight Charts v4**, optimized with `requestAnimationFrame` render gating, frustum culling, and HiDPI Retina scaling.
- **Technical Drawing Tools:** Magnetic wick snapping, support/resistance trendlines, parallel regression channels, Fibonacci retracement levels (0.0%–100.0%), Elliott impulse waves, and translucent supply/demand zones with a multi-step Undo/Redo history stack.
- **Market Intelligence & Automation:** Configurable trigger engine (price breakouts, stop-losses, RSI 14 overbought/oversold limits) with real-time SMTP email notifications, plus a background cron daemon dispatching scheduled daily/weekly PDF and HTML market intelligence reports.
- **Dual Interface:** Full-stack architecture combining a modern **FastAPI** web workstation and an interactive terminal CLI.

#### 4. 🕷️🔍 Scrape Agent — Autonomous Web Data Extraction & Pattern Recognition Suite
*A zero-config scraping utility that automatically discovers repeating DOM structures (cards, tables, listings) and converts unstructured web pages into CSV/JSON datasets without manual selectors.*
- **Dual Scraping Engines:** Integrates a fast, lightweight HTTP engine (`requests`) for static HTML and a headless Chromium engine (**Playwright**) for JavaScript-rendered Single Page Applications (SPAs).
- **Automated Pattern Detection:** Heuristic DOM parser that identifies repeating structural clusters without needing hard-coded XPath or CSS rules.
- **Modern Desktop GUI & CLI:** Built with **CustomTkinter** featuring light/dark themes, live table search/filtering, and one-click exports, alongside an interactive terminal CLI.

#### 5. 📑🧠 AI PDF Question Answering & Multi-Document Comparative Synthesis Engine
*A document intelligence application that ingests single or multiple PDF documents to provide conversational Q&A, cross-document comparison, and factual synthesis.*
- **Context Fusion & Attribution:** Streams and extracts text using `pypdf`, marks document boundaries, and performs comparative cross-document analysis using **LangChain** and **Google Gemini**.
- **Source Citation:** Accurately cites exact document origins for each generated finding.
- **Dual Delivery Modes:** Operates both as a terminal CLI tool and as an interactive drag-and-drop **Streamlit** web application.

#### 6. ⚡📲 LAN Share — Zero-Config AirDrop-Style Local P2P File Transfer System
*An app-less local network file transfer hub that allows any device on the same Wi-Fi network (iOS, Android, Windows, macOS, Linux) to securely exchange multi-gigabyte files at maximum LAN speeds.*
- **QR Discovery & PIN Gate:** Host terminal displays an ASCII QR code and 4-digit PIN on startup; enforces cryptographically signed session cookies (`itsdangerous`) to block unauthorized LAN clients.
- **Flat 1 MB RAM Footprint:** Streams uploads in 1 MB chunks directly to disk, maintaining steady ~1 MB RAM consumption whether transferring small documents or 4 GB 4K video files.
- **Security & UI:** Built-in path traversal protection (`resolve_upload_path`), two-way upload/download capabilities, and a responsive mobile-first glassmorphism dashboard with live progress indicators.

#### 7. ⚙️ Basys 3 8-Bit Arithmetic Logic Unit (ALU) & Display Controller (Verilog)
*An 8-bit digital ALU and custom control unit implemented in Verilog for the Xilinx Basys 3 FPGA development board.*
- **Architecture & Instruction Set:** Connects a 16-bit instruction decoder (`control_unit.v`), 16 internal 8-bit registers, and a 256-byte internal RAM block to execute 16 arithmetic, logic, and memory operations.
- **Hardware Signal Processing:** Features a clock-counter debouncer algorithm (~1M cycles on the 100 MHz clock) to eliminate tactile button contact bounce and metastability.
- **Display Subsystem:** Binary-to-BCD conversion module and a high-speed optical multiplexer for the 4-digit 7-segment display, complete with Two's Complement signed negative number rendering.

#### 8. 🔍 Zachary Karate Club Modularity Optimization & Community Detection (C)
*A graph analytics and community detection suite developed in C to uncover natural community clustering within social networks.*
- **Algorithmic Implementations:** Benchmarks three distinct strategies: **Fast Greedy** modularity optimization, the multi-phase **Louvain** algorithm, and a custom seed-based neighborhood proximity heuristic.
- **Graph Mathematics:** Computes and outputs modularity scores ($Q$) and node assignment vectors across the 34-node, 78-edge Zachary Karate Club graph.

#### 9. ⚔️ SoulReaper — Terminal-Based Fantasy Tactical RPG Engine (Java OOP)
*An interactive terminal-based RPG developed in Java, architected to demonstrate advanced Object-Oriented Software Design patterns.*
- **OOP Architecture:** Deep inheritance hierarchies (`BaseSoul`, `Shinigami`, `Enemy`, `VastoLorde`), polymorphism through specialized interfaces (`Attack`, `Usable`, `Lootable`, `Saveable`), and encapsulation across game entities.
- **Resilience & Modular Design:** Custom multi-layered exception handling (`InsufficientBudgetException`, `OverLoopException`) to safeguard turn-based combat loops, dynamic inventory states, and external file-based story/state persistence.

#### 10. 📸 ScreenSnap Studio — Desktop Screen Capture & Annotation Suite (Python)
*A modular desktop screen capture and markup tool built with Python, Tkinter, MSS, and Pillow.*
- **Global Hotkey Subsystem:** Global background listener for instant fullscreen captures (`F1`) and interactive freeze-screen rectangular snips (`F2`) with live pixel dimension guidelines.
- **Integrated Annotation Canvas:** Vector drawing tools (arrows, rectangles, ellipses, highlight brushes, text labels, and privacy blur/pixelation) with an Undo/Redo history stack.
- **Cloud Dispatch:** One-click anonymous cloud upload with automatic clipboard link synchronization.

---

### 📚 Currently Learning & Exploring

- Distributed Systems & Cloud-Native Architectures
- Autonomous Agentic Workflows & Multi-Agent Frameworks
- Database Internals, Query Optimization & High-Throughput Indexing
- Containerization & CI/CD Pipelines (Docker, Kubernetes, GitHub Actions)
- Microservices Architecture with Spring Cloud

---

### 🎯 Goals

- Deepen expertise in high-concurrency backend architecture and distributed systems
- Build production-ready, data-intensive GenAI applications
- Contribute actively to prominent open-source repositories
- Regularly write technical articles and architectural breakdowns

---

### 📫 Contact

- **LinkedIn:** [linkedin.com/in/aslan-yusuf-zeybek](https://www.linkedin.com) *(LinkedIn profil linkini buraya ekleyebilirsin)*
- **Email:** aslan.yusuf.zeybek@gmail.com *(Kendi e-postanı buraya ekleyebilirsin)*
- **GitHub:** [github.com/AslanRunner](https://github.com/AslanRunner)

⭐ *Thanks for visiting my profile!*
