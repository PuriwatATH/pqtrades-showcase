# pqtrades-showcase
> ⚠️ **Notice:** This is an active showcase repository currently under documentation and refinement.  
> If you're a recruiter or hiring manager visiting early — thank you!  
> The platform itself is fully developed and deployed at [www.pqtrades.com](https://www.pqtrades.com),  
> and this repo will soon include architecture diagrams, API logic, and annotated code snippets.

Welcome to the official public showcase of **PQTradePlatform**, a full-stack trading simulation platform built to demonstrate scalable backend architecture, real-time infrastructure, and institutional-grade execution logic.

This project highlights my work as a full-stack Quant Developer with a focus on Python, trading system design, and backend-first infrastructure thinking.

> 🔗 Live site: [www.pqtrades.com](https://www.pqtrades.com)

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

---

## 🧰 Tech Stack

| Layer        | Technologies |
|--------------|--------------|
| **Backend**  | Python, Django, FastAPI, Celery, PostgreSQL, Redis |
| **Frontend** | React, Tailwind CSS, WebSocket |
| **Infrastructure** | Docker (optional), PM2, AWS EC2 (Ubuntu), Git |
| **Security** | JWT tokens, versioning, token blacklisting, idempotency keys |
| **Data Handling** | Pandas, NumPy, simulated OHLC streams |

---

## 🔐 Highlighted Modules

### Idempotency Middleware (Safe Re-Execution)

