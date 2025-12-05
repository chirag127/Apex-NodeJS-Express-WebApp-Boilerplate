# Express Foundry: Production-Grade Node.js Boilerplate

A production-grade boilerplate for Node.js & Express.js web applications. Features EJS templating, a layered architecture, and Docker/Codespaces support for rapid, scalable development. Your ultimate starter kit.

[![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/ci.yml?style=flat-square)](https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/actions)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate?style=flat-square)](https://app.codecov.io/github/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate)
[![Tech Stack](https://img.shields.io/badge/Node.js-Express-EJS-TypeScript-Biome-Vitest-Playwright-blue?style=flat-square)](https://expressjs.com/)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-orange?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate?style=flat-square)](https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/stargazers)

---


## 🚀 Table of Contents

*   [About the Project](#about-the-project)
*   [Key Features](#key-features)
*   [Architecture](#architecture)
*   [Getting Started](#getting-started)
*   [Development Workflow](#development-workflow)
*   [License](#license)
*   [Contributing](#contributing)
*   [AI Agent Directives](#ai-agent-directives)

---


## 💡 About the Project

Express Foundry is a meticulously crafted boilerplate designed to accelerate the development of production-ready Node.js web applications. It emphasizes best practices, scalability, and developer experience, providing a robust foundation for your next project.

## ✨ Key Features

*   **Node.js & Express.js:** Latest stable versions.
*   **EJS Templating:** Efficient server-side rendering.
*   **Layered Architecture:** Separation of Concerns (Controllers, Services, Repositories, Models).
*   **TypeScript Support:** Optional, strongly-typed development.
*   **Docker Integration:** Simplified containerization with `Dockerfile`.
*   **GitHub Codespaces Ready:** Instant cloud development environment.
*   **Pre-configured Linting & Formatting:** Biome for optimal code quality.
*   **Testing Framework:** Vitest for unit and integration tests, Playwright for E2E.
*   **Production-Ready Configuration:** Environment variable management (dotenv).

## 🏗️ Architecture

This boilerplate adopts a **Layered Architecture** pattern, promoting modularity and maintainability:

mermaid
graph TD
    A[Client/User] --> B(API Gateway/Routes)
    B --> C{Controllers}
    C --> D[Services]
    D --> E[Repositories]
    E --> F{Database}
    D --> G[Utilities]
    C --> H[Middleware]
    H --> B


## 🏁 Getting Started

### Prerequisites

*   Node.js (v18+ recommended)
*   npm or yarn (installed with Node.js)
*   Docker (for containerized development/deployment)

### Installation

1.  Clone the repository:
    bash
    git clone https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate.git
    cd Express-Foundry-Production-Grade-NodeJS-Boilerplate
    

2.  Install dependencies:
    bash
    npm install
    # or
    yarn install
    

3.  Set up environment variables:
    Copy `.env.example` to `.env` and configure your settings (e.g., database connection, ports).
    bash
    cp .env.example .env
    # Edit .env file
    

## ⚙️ Development Workflow

| Script        | Description                                                   |
| :------------ | :------------------------------------------------------------ |
| `npm run dev` | Starts the development server with hot-reloading.             |
| `npm run build` | Builds the project for production.                            |
| `npm run start` | Starts the production build.                                  |
| `npm run lint` | Lints the codebase using Biome.                               |
| `npm run format`| Formats the codebase using Biome.                             |
| `npm run test` | Runs unit and integration tests with Vitest.                  |
| `npm run test:e2e` | Runs end-to-end tests with Playwright.                       |
| `npm run docker:build` | Builds the Docker image.                                     |
| `npm run docker:run` | Runs the application in a Docker container.                  |

---


## 🛡️ AI Agent Directives

<details>
<summary>Expand for AI Agent Directives</summary>

This repository operates under the **Apex Technical Authority** guidelines, ensuring adherence to **December 2025 / 2026 Industry Standards**. Agents interacting with this codebase must comply with the following:

### 1. Identity & Prime Directive

*   **Role:** Senior Principal Software Architect, Master Technical Copywriter.
*   **Core Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."
*   **Output Standard:** **EXECUTION-ONLY**. No planning, only execution.

### 2. Input Processing & Cognition

*   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. Infer technical intent based on project context.
*   **SSOT:** Treat the `README.md` as the Single Source of Truth.
*   **Instrumentation:** Use `linkup`/`brave` for research, `docfork` for API validation, and `clear-thought-two` for reasoning before code generation.

### 3. Context-Aware Apex Tech Stacks (Late 2025 Standards)

*   **PRIMARY STACK: WEB / APP / GUI (Modern Frontend)**
    *   **Language:** TypeScript (Strict Mode Enabled)
    *   **Build Tool:** Vite 7 (with Rolldown)
    *   **Styling:** TailwindCSS v4
    *   **Native Framework:** Tauri v2
    *   **State Management:** Signals (Standardized)
    *   **Linting/Formatting:** Biome
    *   **Unit Testing:** Vitest
    *   **E2E Testing:** Playwright
    *   **Architecture:** Feature-Sliced Design (FSD)

### 4. Development & Deployment Principles

*   **Code Quality:** Strict adherence to SOLID, DRY, KISS, YAGNI principles.
*   **Testing:** Comprehensive unit, integration, and E2E test coverage. Aim for >90% code coverage.
*   **CI/CD:** Automated builds, tests, and deployments via GitHub Actions.
*   **Containerization:** Docker-first approach for consistent environments.
*   **Security:** Proactive vulnerability scanning, dependency audits, and secure coding practices (OWASP Top 10).
*   **Documentation:** Maintain up-to-date READMEs, API docs, and inline comments.

</details>

---


## ⚖️ License

Distributed under the CC BY-NC 4.0 License. See `LICENSE` for more information.

## 🤝 Contributing

Contributions are welcome! Please see the `CONTRIBUTING.md` file for details on how to submit pull requests and report issues.
