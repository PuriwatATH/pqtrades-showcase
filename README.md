
---
> ⚠️ **Notice:** This is an active showcase repository currently under documentation and refinement.  
> If you're a recruiter or hiring manager visiting early — thank you!  
> The platform itself is fully developed and deployed at [www.pqtrades.com](https://www.pqtrades.com),  
> and this repo will soon include architecture diagrams, API logic, and annotated code snippets.

---
# PQTrades Showcase

Welcome to the official public showcase of **PQTrades Platform**, a full-stack trading simulation platform built to demonstrate scalable backend architecture, real-time infrastructure, and institutional-grade execution logic.

This project highlights my work as a full-stack Quant Developer with a focus on Python, trading system design, and backend-first infrastructure thinking.

> 🔗 Live site: [www.pqtrades.com](https://www.pqtrades.com/portfolio)

---

## 🚀 Project Overview

**PQTradePlatform** is a real-time quant trading simulator that mimics institutional trading systems. It supports market, limit, and stop orders, real-time PnL, margin tracking, and session-level access control. This platform was designed and developed from scratch over three months to demonstrate production-grade execution logic.

---

## 🧠 Key Features

- **Real-Time Price Feed Engine**  
  Simulated bid/ask pricing with OHLC candle generation (M1–D1), 8-week delayed configuration for backtesting

- **Trade Execution Engine**  
  Market, Limit, and Stop order handling with SL/TP enforcement, FIFO matching, and PnL calculation

- **Modular Backend Architecture**  
  Django + FastAPI APIs with token versioning, idempotency middleware, session-scoped authentication

- **Frontend Dashboard (SPA)**  
  React + Tailwind dashboard with role-based interfaces for Trader, Admin, and Observer (view-only)

- **Live WebSocket Data Layer**  
  WebSocket + Redis bridge for real-time price updates, execution sync, and background task distribution

- **Deployment Optimization**  
  Runs on AWS EC2 (t2.micro free-tier) with <10% idle CPU via SWAP memory tuning and service isolation


## ✅ Project Outcome

Delivered a full-stack MVP aligned to institutional-grade standards, enabling real-time model testing, execution simulation, and a robust Python backend infrastructure. Demonstrates fluency in system design, modern dev workflows, and real-world quant engineering.

---

## 🧠 Key Skills

| Category                      | Tools & Concepts                                                             |
|------------------------------|------------------------------------------------------------------------------|
| Programming Languages        | Python, JavaScript (React), SQL (PostgreSQL), Bash                          |
| Backend Frameworks           | Django, FastAPI, Celery, Redis, Node.js                                     |
| API & Integration            | RESTful APIs, WebSocket, JWT, Idempotency Middleware                        |
| Trading Logic & Simulation   | Market/Limit/Stop Orders, SLTP Validation, Margin Model, FIFO Matching      |
| Real-Time Infrastructure     | WebSocket Streaming, OHLC Generation (M1–D1), Spread Simulation              |
| Frontend Development         | React, TailwindCSS, Component Routing, Responsive UI                        |
| Security & Access Control    | Token Versioning, Role-Based Access, Portfolio Scoping, Blacklisting        |
| Asynchronous Processing      | Redis Pub/Sub, Celery Task Queues, Background Workers                       |
| System Design & Architecture | Modular Design, Clean Code, Microservices via PM2                          |
| Deployment & DevOps          | AWS EC2 (t2.micro), SWAP Optimization, Git, PM2                             |
| Engineering Practices        | Agile Workflow, Version Control, Unit Testing Ready                         |

---

## 🔐 Highlighted Modules
> ⚠️ **Notice:** This is an active showcase repository currently under documentation and refinement.  

---

## ✅ Project Outcome

Delivered a full-stack MVP aligned to institutional-grade standards, enabling real-time model testing, execution simulation, and a robust Python backend infrastructure. Demonstrates fluency in system design, modern dev workflows, and real-world quant engineering.

---

## ✅ Meta Checklist for Publishing PQTradePlatform
- [x] Project Title & Role Label
- [x] Live Site URL (pqtrades.com)
- [x] Project Summary / Purpose
- [x] Technologies Used (Python, Django, FastAPI, etc.)
- [x] System Architecture Overview
- [x] Key Features (Trading, Order Lifecycle, Real-time Pricing)
- [x] Deployment Strategy (AWS EC2 + Optimization)
- [x] Project Outcome (Impact, Goals Achieved)
- [x] Skills Matrix Table (Grouped by category)
- [ ] GitHub Project Showcase - Document, Code Snippet, System Architecture, etc.
- [ ] Future Scope / What's Next (AI Signal Engine, Backtesting)
- [ ] Contribution Guidelines (optional)
- [ ] License section (MIT / Proprietary if private)
