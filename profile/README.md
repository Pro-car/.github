<div align="center">
  <img src="https://procar.kr/images/logo.svg" alt="PROCAR Logo" width="120" />
  <h1>PROCAR — Korean Export & Auction Platform</h1>
  <p><b>Advanced multi-source aggregation, normalization, and analytics platform for South Korean vehicle auctions.</b></p>
  
  <p>
    <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" alt="Status">
    <img src="https://img.shields.io/badge/Architecture-Microservices-blue?style=flat-square" alt="Architecture">
    <img src="https://img.shields.io/badge/Stack-TypeScript%20%7C%20NestJS%20%7C%20Next.js-informational?style=flat-square" alt="Tech Stack">
  </p>
</div>

---

## 🚗 About PROCAR

**PROCAR** is a high-performance, automated platform designed to aggregate, translate, and process vehicle inventories from major South Korean automotive auction platforms (including Hyundai Glovis, AutoHub, KCar, Lotte Auto Auction, SKCar, Encar, and HappyCar). 

The system handles real-time data ingestion, background job processing, multi-source normalization, and a lightning-fast client interface for seamless vehicle selection and export tracking.

---

## 🏗️ Core Ecosystem & Repositories

PROCAR is built using a decoupled microservices and modular architecture distributed across our organization repositories:

* **[`pro-car-api`](https://github.com/Pro-car/pro-car-api)** — Core backend API service built with NestJS, handling business logic, authentication, and client data delivery.
* **[`pro-car-parser`](https://github.com/Pro-car/pro-car-parser)** — High-throughput web scraping engine utilizing Playwright, Axios, Redis, and BullMQ with advanced proxy rotation.
* **[`pro-car-web-client`](https://github.com/Pro-car/pro-car-web-client)** — Modern frontend user application built with Next.js, React, and custom MUI UI components.
* **[`pro-car-admin`](https://github.com/Pro-car/pro-car-admin)** — Internal dashboard for inventory management, auction monitoring, and system control.
* **[`pro-car-db`](https://github.com/Pro-car/pro-car-db)** — Centralized database schemas, Prisma ORM migrations, and shared data models.
* **[`pro-car-infrastructure`](https://github.com/Pro-car/pro-car-infrastructure)** — DevOps configurations, Docker Compose setups, Nginx reverse proxies, SSL automation, and server monitoring scripts.

---

## ⚡ Tech Stack

* **Backend:** TypeScript, Node.js, NestJS, Fastify, BullMQ, Playwright
* **Frontend:** Next.js, React, TypeScript, Material-UI (MUI)
* **Databases & Storage:** PostgreSQL, Redis, ScyllaDB, DuckDB, Prisma ORM, Cloudflare R2
* **DevOps & Tooling:** Docker, Docker Compose, GitHub Actions CI/CD, Nginx, Certbot, Tailscale

---

<div align="center">
  <sub>PROCAR Organization • Built with precision for high-load vehicle auction processing.</sub>
</div>
