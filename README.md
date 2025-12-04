# Apex-NodeJS-Express-WebApp-Boilerplate

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate/ci.yml?style=flat-square&label=Build)](https://github.com/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate/actions/workflows/ci.yml)
[![Coverage](https://img.shields.io/codecov/c/github/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate?style=flat-square)](https://codecov.io/gh/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate)
[![Language](https://img.shields.io/github/languages/top/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate?style=flat-square&color=3498DB)](https://github.com/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate)
[![License](https://img.shields.io/github/license/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate?style=social)](https://github.com/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate)

> This repository provides an enterprise-grade, production-ready Node.js/Express boilerplate, meticulously architected for rapid application deployment and utilizing EJS templating.
> It establishes the foundation for scalable web services, complete with essential DevOps tooling via Docker and optimized for immediate use within GitHub Codespaces.


<p align="center">
  <a href="https://github.com/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate">
    <img src="https://img.shields.io/badge/Star%20⭐%20this%20Repo-ff69b4?style=for-the-badge&logo=star" alt="Star this Repo">
  </a>
</p>

---

## Table of Contents
1. [Architectural Overview](#-architectural-overview)
2. [Apex Directives & AI Alignment](#-apex-directives--ai-alignment)
3. [Development Standards](#-development-standards)
    * [Prerequisites](#prerequisites)
    * [Setup Guide](#setup-guide)
    * [Execution Scripts](#execution-scripts)
4. [Key Features](#-key-features)
5. [License](#-license)


## 🚀 Architectural Overview

This boilerplate adheres to a **Modular Monolith** pattern optimized for the Node.js runtime, ensuring high cohesion within modules and low coupling between services, leveraging Express.js routing conventions.

ascii
/Apex-NodeJS-Express-WebApp-Boilerplate
├── .github/                # CI/CD, Templates, Security Policies
├── config/                 # Environment configuration (e.g., dotenv setup)
├── src/
│   ├── controllers/        # Request handling and business logic orchestration
│   ├── middleware/         # Cross-cutting concerns (Auth, Logging, Error Handling)
│   ├── models/             # Data schema definitions (if using ORM/ODM)
│   ├── routes/             # Endpoint definitions mapping URLs to controllers
│   └── views/              # EJS Templates (Presentation Layer)
│       ├── layouts/
│       └── partials/
├── Dockerfile              # Containerization definition
├── .env.example            # Example environment variables
└── package.json            # Project dependencies and scripts


<details>
<summary><strong>🤖 AI Agent Directives (CRITICAL)</strong></summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs. Use `linkup`/`brave` to search for **December 2025 Industry Standards**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** This repository is a **Node.js/Express Web Application** utilizing EJS.

*   **PRIMARY SCENARIO: WEB / APP / GUI (Modern Frontend/Server)**
    *   **Stack:** **TypeScript (Strict)** is the baseline expectation for all new Node.js projects; legacy JavaScript should be minimized or linted aggressively. **Vite 7** (for any static assets), **Express.js 5.x**, **EJS** (as mandated template engine).
    *   **Lint/Test:** **Biome** (Linter/Formatter) for speed, **Vitest** (Unit), **Playwright** (E2E).
    *   **Architecture:** Enforce **SOLID Principles** (especially Single Responsibility and Dependency Inversion) within Controllers and Middleware. Maintain **DRY** standards rigorously.

## 4. VERIFICATION & RECONCILIATION
*   **Codebase Health:** Ensure all handlers are stateless where possible.
*   **Security Posture (2026 Focus):** Validate input against OWASP Top 10 (Injection, Broken Access Control) *before* rendering EJS templates or passing data to the database layer.
*   **Containerization:** Ensure `Dockerfile` adheres to multi-stage builds for minimal final image size.

</details>

---

## ⚙️ Development Standards

This project is structured for **Zero-Defect, High-Velocity** development, leveraging modern tooling.

### Prerequisites
To work locally, you must have the following installed:
*   Node.js (LTS, preferably version 20+)
*   npm or Yarn/pnpm (npm is default)
*   Docker (for containerized development environment)

### Setup Guide

1.  **Clone Repository:**
    bash
    git clone https://github.com/chirag127/Apex-NodeJS-Express-WebApp-Boilerplate.git
    cd Apex-NodeJS-Express-WebApp-Boilerplate
    

2.  **Install Dependencies (Node):**
    bash
    npm install
    

3.  **Environment Setup:**
    Create a `.env` file by copying the template:
    bash
    cp .env.example .env
    # Edit .env with your specific secrets and configuration
    

4.  **Run Locally (Development Mode):**
    This command starts the server, typically watching for file changes.
    bash
    npm run dev
    

5.  **Containerized Setup (Recommended for Consistency):**
    bash
    docker compose up --build
    

### Execution Scripts

| Script | Command | Description |
| :--- | :--- | :--- |
| `dev` | `npm run dev` | Starts the application in development mode with hot-reloading. |
| `start` | `npm start` | Starts the production-optimized application. |
| `test:unit` | `npm run test:unit` | Executes unit tests (Vitest). |
| `test:e2e` | `npm run test:e2e` | Executes end-to-end tests (Playwright). |
| `lint` | `npm run lint` | Runs Biome to check code style and format violations. |
| `docker:build` | `docker build -t apex-web .` | Builds the production Docker image. |

## ✨ Key Features

*   **Production Ready:** Pre-configured with robust error handling middleware.
*   **EJS Templating:** Clear separation of concerns between server logic and view presentation.
*   **Docker Integration:** Single-stage or Multi-stage Dockerfile for standardized deployment.
*   **Codespaces Optimized:** Configuration (`.devcontainer/`) ensures instant, consistent development environments.
*   **Scalability Focus:** Architecture designed to easily transition routing/controllers to microservices if scaling demands.

## ⚖️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**. See the [LICENSE](LICENSE) file for details.
