# Webiodd-Network
WEBioDD Network: AI-Driven Automated Playout System

# 🚀 WEBioDD Network: AI-Driven Automated Playout System

![Status](https://img.shields.io/badge/Status-Live_&_Operational-success)
![Architecture](https://img.shields.io/badge/Architecture-Microservices-blue)
![AI](https://img.shields.io/badge/AI_Engine-Gemini_Pro-orange)

🌐 **Live Website:** [WEBioDD.com](https://webiodd.com)

> 🔒 **Note:** This is a showcase repository. The source code is private due to commercial and proprietary architecture constraints. This README serves as a technical overview of the system's architecture and capabilities.

## 📝 Project Overview
**WEBioDD** is an exclusive Arabic-language technology news platform. It is not just a CMS, but a **fully automated, end-to-end playout system** that operates entirely without human intervention. 

Architected to mirror a broadcast Master Control Room (MCR), the system utilizes autonomous AI agents to handle content ingestion, editorial processing, graphic design, and scheduling 24/7.

## 🏗️ System Architecture & Workflow
The platform is powered by four synchronized background engines running on a Linux infrastructure:

1. ⏱️ **Scheduler Agent:** Automatically generates empty "broadcast slots" in the database at predefined daily intervals.
2. 📡 **Ingest Agent:** Scans global RSS feeds to extract the latest, unpublished technology news.
3. 🧠 **AI Processing Engine:** 
   * Translates and rewrites raw data into SEO-optimized professional Arabic articles.
   * Extracts metadata (Tags, Categories, Excerpts).
   * Triggers the **Dynamic Image Engine** (Prompt Engineering) to generate unique cover images using randomized art styles (Cinematic, Cyberpunk, Isometric, etc.).
4. 📺 **Playout Engine:** Continuously monitors the timeline. Once a scheduled slot is reached, it updates the asset status to 'Published', instantly broadcasting it to the frontend.

## 🎛️ The MCR Dashboard (Admin Panel)
The system is managed via a custom-built, highly secure Admin Dashboard featuring:
* **Live Pipeline Monitor:** An `As-Run` logging system that records every action of the AI agents and the playout engine for maximum traceability.
* **Infrastructure Health:** Real-time server telemetry tracking CPU, RAM, and Disk usage via Python's `psutil`.
* **Ad Orchestration:** A dynamic module to inject and manage ad scripts across the platform.

## 💻 Tech Stack

### Backend & Automation Engines
* **Python 3** & **FastAPI** (High-performance API)
* **SQLAlchemy** (ORM)
* **APScheduler** (Cron Jobs & Playout synchronization)
* **Feedparser** & **Google GenAI API**

### Frontend
* **Next.js (App Router)** & **React**
* **TypeScript**
* **Tailwind CSS**

### DevOps & Infrastructure
* **Docker** & **Docker Compose** (Containerized microservices)
* **Linux (Ubuntu)**
* **Reverse Proxy** (Nginx/Caddy)

---
*Developed & Engineered by Tarik Salih*
