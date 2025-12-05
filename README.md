# Express Foundry: Production-Grade Node.js Boilerplate

<!-- Badges Block -->
[![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/ci.yml?label=Build&logo=githubactions&style=flat-square)](https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate?label=Coverage&logo=codecov&style=flat-square)](https://codecov.io/gh/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate)
[![Node.js Version](https://img.shields.io/badge/Node.js-20.x%2B-blue?logo=nodedotjs&style=flat-square)](https://nodejs.org/)
[![Express.js Version](https://img.shields.io/badge/Express.js-5.x-green?logo=express&style=flat-square)](https://expressjs.com/)
[![EJS Version](https://img.shields.io/badge/EJS-3.x-orange?logo=ejs&style=flat-square)](https://ejs.co/)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-red.svg?style=flat-square)](http://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate?style=flat-square&logo=github)](https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/stargazers)

<!-- Social Proof -->
<p align="center">
  <a href="https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/fork">
    <img src="https://img.shields.io/github/forks/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate?style=social" alt="GitHub Forks">
  </a>
  <a href="https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/watchers">
    <img src="https://img.shields.io/github/watchers/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate?style=social" alt="GitHub Watchers">
  </a>
  <a href="https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/issues">
    <img src="https://img.shields.io/github/issues/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate?style=social" alt="GitHub Issues">
  </a>
</p>

<p align="center">
  ✨ Star ⭐ this Repo to accelerate your next Node.js project! ✨
</p>

---

## 🚀 Express Foundry: The Ultimate Node.js Production Starter Kit

Express Foundry provides a meticulously crafted, production-grade boilerplate for building robust and scalable Node.js web applications with Express.js and EJS templating. It is designed for rapid, high-velocity development, incorporating best practices, a layered architecture, and seamless integration with Docker and GitHub Codespaces.

---

## 🌳 Project Structure (Layered Architecture)


.                                       # Root Directory
├── src/
│   ├── config/                         # Application Configuration
│   │   └── index.ts
│   ├── controllers/
│   │   └── exampleController.ts
│   ├── middlewares/
│   │   └── exampleMiddleware.ts
│   ├── models/
│   │   └── exampleModel.ts
│   ├── routes/
│   │   └── index.ts
│   ├── services/
│   │   └── exampleService.ts
│   ├── utils/
│   │   └── logger.ts
│   └── app.ts                          # Express Application Setup
├── public/
│   ├── css/
│   └── js/
├── views/
│   └── pages/
│       └── index.ejs
├── tests/
│   └── unit/
│       └── example.test.ts
├── .env.example
├── .eslintrc.js
├── .gitignore
├── Dockerfile
├── LICENSE
├── README.md
├── tsconfig.json
└── package.json


---

## 🧾 Table of Contents

*   [🚀 Express Foundry: The Ultimate Node.js Production Starter Kit](#-express-foundry-the-ultimate-nodejs-production-starter-kit)
*   [🌳 Project Structure (Layered Architecture)](#-project-structure-layered-architecture)
*   [🧾 Table of Contents](#-table-of-contents)
*   [✨ Core Features](#-core-features)
*   [⚙️ Technology Stack](#-technology-stack)
*   [📦 Getting Started](#-getting-started)
*   [🐳 Docker & Codespaces](#-docker--codespaces)
*   [🚀 Development Scripts](#-development-scripts)
*   [🏗️ Architecture Principles](#-architecture-principles)
*   [🔐 Security Best Practices](#-security-best-practices)
*   [🤝 Contributing](#-contributing)
*   [📄 License](#-license)

---

## ✨ Core Features

*   **Production-Ready:** Pre-configured for robust, scalable deployments.
*   **Layered Architecture:** Promotes separation of concerns (Controllers, Services, Models, Middlewares).
*   **EJS Templating:** Powerful server-side rendering with a clean templating engine.
*   **TypeScript Support:** Integrated TypeScript for enhanced code quality and maintainability.
*   **ESLint & Prettier:** Strict linting and formatting rules for consistent code style.
*   **Testing Framework:** Built with Vitest for fast unit and integration tests.
*   **Docker Support:** Dockerfile included for containerized development and deployment.
*   **Codespaces Ready:** `.devcontainer` configuration for seamless cloud development.
*   **Environment Variables:** Managed via `.env` files.

---

## ⚙️ Technology Stack

*   **Runtime:** Node.js (v20.x+)
*   **Framework:** Express.js (v5.x)
*   **Templating:** EJS (v3.x)
*   **Language:** TypeScript (v5.x)
*   **Bundler/DevServer:** Vite (v5.x)
*   **Testing:** Vitest (v1.x)
*   **Linting/Formatting:** ESLint (v8.x) & Prettier (v3.x)
*   **Containerization:** Docker
*   **CI/CD:** GitHub Actions

---

## 📦 Getting Started

### Prerequisites

*   Node.js (v20.x or higher) installed.
*   npm or yarn package manager.

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate.git
    cd Express-Foundry-Production-Grade-NodeJS-Boilerplate
    

2.  **Install dependencies:**
    bash
    npm install
    # or
    yarn install
    

3.  **Set up environment variables:**
    Copy the example environment file and populate it with your settings:
    bash
    cp .env.example .env
    
    Edit the `.env` file to configure your application settings (e.g., database connections, API keys).

---

## 🐳 Docker & Codespaces

### Docker

Build and run the application using Docker:

bash
# Build the Docker image
docker build -t express-foundry .

# Run the Docker container
docker run -p 3000:3000 express-foundry


### GitHub Codespaces

This repository includes a `.devcontainer` configuration. You can directly open this project in GitHub Codespaces for an instant, fully configured development environment without any local setup.

---

## 🚀 Development Scripts

Run the following commands using `npm` or `yarn`:

| Script       | Description                                                    |
| :----------- | :------------------------------------------------------------- |
| `npm run dev`  | Start the development server with hot-reloading.               |
| `npm run build`| Compile TypeScript and prepare for production deployment.      |
| `npm run start`| Start the production server.                                   |
| `npm run test` | Run unit and integration tests using Vitest.                   |
| `npm run lint` | Run ESLint to check code style and identify potential errors.  |
| `npm run format`| Format code using Prettier.                                    |

---

## 🏗️ Architecture Principles

This boilerplate adheres to fundamental software design principles to ensure maintainability, scalability, and robustness:

*   **SOLID Principles:** (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion) are encouraged within service and controller implementations.
*   **DRY (Don't Repeat Yourself):** Abstract common logic into reusable services, utilities, and middlewares.
*   **YAGNI (You Ain't Gonna Need It):** Focus on current requirements; avoid over-engineering for future, unconfirmed needs.
*   **Layered Architecture:** Clear separation of concerns between presentation (controllers, views), business logic (services), and data access (models).

---

## 🔐 Security Best Practices

*   **Input Validation:** Always validate and sanitize user input to prevent injection attacks (e.g., XSS, SQL injection).
*   **Environment Variables:** Store sensitive information (API keys, secrets) in `.env` files and never commit them to version control.
*   **Rate Limiting:** Implement rate limiting on sensitive API endpoints.
*   **Helmet.js:** Consider integrating Helmet.js for setting various HTTP headers for security.
*   **Dependency Management:** Regularly update dependencies to patch security vulnerabilities.

---

## 🤝 Contributing

Contributions are welcome! Please read our [CONTRIBUTING.md](https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/blob/main/.github/CONTRIBUTING.md) guidelines for details on how to submit pull requests, report issues, and suggest features.

---

## 📄 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**. See the [LICENSE](https://github.com/chirag127/Express-Foundry-Production-Grade-NodeJS-Boilerplate/blob/main/LICENSE) file for more details.

---

## 🤖 AI AGENT DIRECTIVES

<details>
<summary>Click to expand AI Agent Directives</summary>

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
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the **Apex Toolchain**. This repository, `Express-Foundry-Production-Grade-NodeJS-Boilerplate`, is a Node.js backend project.

*   **PRIMARY SCENARIO A: WEB / APP / GUI (Modern Frontend/Backend)**
    *   **Stack:** This project leverages **TypeScript 6.x (Strict Mode)**. The backend utilizes **Node.js 20.x+** with **Express.js 5.x**. For frontend templating, **EJS 3.x** is employed. **Vite 5.x** serves as the bundler and development server. For testing, **Vitest 1.x** is the chosen framework.
    *   **Linting/Formatting:** **ESLint 8.x** and **Prettier 3.x** are configured for code quality and consistency.
    *   **Architecture:** Adheres to a **Layered Architecture** pattern, promoting clear separation of concerns.

*   **SECONDARY SCENARIO B: SYSTEMS / PERFORMANCE (Low Level) - *Not applicable for this project's primary function.***
    *   **Stack:** Rust (Cargo) or Go (Modules).
    *   **Lint:** Clippy / GolangCI-Lint.
    *   **Architecture:** Hexagonal Architecture (Ports & Adapters).

*   **TERTIARY SCENARIO C: DATA / AI / SCRIPTS (Python) - *Not applicable for this project's primary function.***
    *   **Stack:** uv (Manager), Ruff (Linter), Pytest (Test).
    *   **Architecture:** Modular Monolith or Microservices.

---

## 4. DEVELOPMENT WORKFLOW & STANDARDS

*   **Version Control:** Git is mandatory. Utilize feature branching strategies (e.g., Gitflow).
*   **Package Management:** npm or Yarn.
*   **Code Quality:** Strict adherence to TypeScript best practices, ESLint, and Prettier rules. Strive for 100% code coverage with Vitest.
*   **Testing:** All new features must include comprehensive unit and integration tests. End-to-end tests should be considered for critical user flows.
*   **Build Process:** Vite is used for efficient bundling and optimization for production.
*   **Deployment:** Docker is the standard for containerization. CI/CD pipelines (GitHub Actions) automate build, test, and deployment processes.

---

## 5. AI AGENT PROTOCOL

*   **Code Generation:** Generate TypeScript code adhering to the specified stack and architecture.
*   **Documentation:** Maintain comprehensive `README.md`, `CONTRIBUTING.md`, and other relevant documentation.
*   **Testing:** Generate Vitest test cases for all new logic.
*   **Security Audits:** Proactively identify and suggest mitigations for common web vulnerabilities.
*   **Performance Optimization:** Analyze and recommend optimizations for Node.js, Express.js, and Vite configurations.

</details>
