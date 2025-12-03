# 🚀 RapidStart: Express.js & NodeJS Web App Template

<div align="center">

[
![Build Status](https://github.com/chirag127/RapidStart-Express-NodeJS-WebApp-Template/actions/workflows/ci.yml/badge.svg?style=flat-square)
](https://github.com/chirag127/RapidStart-Express-NodeJS-WebApp-Template/actions/workflows/ci.yml)
[
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/RapidStart-Express-NodeJS-WebApp-Template?style=flat-square&token=YOUR_CODECOV_TOKEN)
](https://codecov.io/gh/chirag127/RapidStart-Express-NodeJS-WebApp-Template)
[
![Formatted with Biome](https://img.shields.io/badge/formatted_with-Biome-60A5FA?style=flat-square&logo=biome)
](https://biomejs.dev/)
[
![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg?style=flat-square)
](https://creativecommons.org/licenses/by-nc/4.0/)
[
![GitHub Stars](https://img.shields.io/github/stars/chirag127/RapidStart-Express-NodeJS-WebApp-Template?style=flat-square&logo=github)
](https://github.com/chirag127/RapidStart-Express-NodeJS-WebApp-Template/stargazers)

</div>

<div align="center">

[
![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?style=flat-square&logo=nodedotjs)
](https://nodejs.org/)
[
![Express.js](https://img.shields.io/badge/Express.js-5.x-000000?style=flat-square&logo=express)
](https://expressjs.com/)
[
![EJS](https://img.shields.io/badge/EJS-3.x-A91E50?style=flat-square&logo=ejs)
](https://ejs.co/)
[
![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=flat-square&logo=docker)
](https://www.docker.com/)

</div>

<p align="center">
  <a href="https://github.com/chirag127/RapidStart-Express-NodeJS-WebApp-Template/stargazers"><strong>Star ⭐ this Repo</strong></a> to support its development!
</p>

This is a production-ready Express.js boilerplate designed for the rapid development of modern web applications. It comes pre-configured with EJS templating, Docker support, and a secure, scalable architecture to help you launch your projects faster and with confidence.

---

## Table of Contents

- [Key Features](#key-features)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Available Scripts](#available-scripts)
- [Guiding Principles](#guiding-principles)
- [🤖 AI Agent Directives](#-ai-agent-directives)
- [Contributing](#contributing)
- [License](#license)

---

## Key Features

-   **Production-Ready:** Built with security, performance, and scalability in mind from day one.
-   **Modern Tech Stack:** Utilizes Node.js (LTS), Express 5.x, and EJS for efficient server-side rendering.
-   **Dockerized:** Includes a multi-stage `Dockerfile` for lightweight, secure, and consistent production builds.
-   **Developer Experience:** Pre-configured with Biome for blazing-fast linting and formatting, ensuring code quality and consistency.
-   **Structured Logging:** Integrated middleware for clear, contextual request logging.
-   **Secure by Default:** Comes with `helmet` for setting crucial security headers and `cors` for managing cross-origin requests.
-   **Environment-Aware Configuration:** Easily manage configuration for development, testing, and production environments using `.env` files.

## Architecture

This template follows a clean and scalable Model-View-Controller (MVC) architecture to enforce separation of concerns.


/
├── .github/              # GitHub Actions, issue templates, etc.
├── .vscode/              # Recommended VSCode settings and extensions.
├── public/               # Static assets (CSS, JS, images).
├── src/
│   ├── config/           # Environment configuration.
│   ├── controllers/      # Business logic handlers.
│   ├── middleware/       # Custom Express middleware.
│   ├── models/           # Data models (if applicable).
│   ├── routes/           # API and view routes.
│   ├── services/         # Services for external APIs or complex logic.
│   └── views/            # EJS templates.
│       └── partials/     # Reusable EJS partials.
│
├── .dockerignore
├── .env.example          # Example environment variables.
├── .gitignore
├── Dockerfile            # Multi-stage production Dockerfile.
├── biome.json            # Biome linter/formatter configuration.
├── package.json
└── server.js             # Main application entry point.


## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

-   [Node.js](https://nodejs.org/) (v20.x or later recommended)
-   [npm](https://www.npmjs.com/) (v10.x or later)
-   [Docker](https://www.docker.com/get-started) (optional, for containerization)

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/RapidStart-Express-NodeJS-WebApp-Template.git
    cd RapidStart-Express-NodeJS-WebApp-Template
    

2.  **Install dependencies:**
    bash
    npm install
    

3.  **Set up environment variables:**
    Create a `.env` file by copying the example and customize it as needed.
    bash
    cp .env.example .env
    

4.  **Run the development server:**
    bash
    npm run dev
    

The application will be available at `http://localhost:3000`.

## Available Scripts

| Script               | Description                                            |
| -------------------- | ------------------------------------------------------ |
| `npm run dev`        | Starts the server in development mode with hot-reloading. |
| `npm start`        | Starts the server in production mode.                  |
| `npm run lint`       | Lints and formats the codebase using Biome.          |
| `npm test`         | Runs tests using Vitest (setup required).              |
| `npm run build:docker` | Builds the production Docker image.             |

## Guiding Principles

-   **SOLID:** Code is structured to be understandable, flexible, and maintainable.
-   **DRY (Don't Repeat Yourself):** Reusable components and logic are abstracted into services and middleware.
-   **YAGNI (You Ain't Gonna Need It):** The boilerplate includes essentials without unnecessary bloat, keeping it lean and focused.

## 🤖 AI Agent Directives

This section provides operational directives for AI agents, ensuring alignment with the project's architecture and standards as of **December 2025**.

<details>
<summary><strong>Click to Expand: Agent Operational Directives</strong></summary>

### SYSTEM: APEX TECHNICAL AUTHORITY (DECEMBER 2025 EDITION)

#### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter. You operate with absolute precision, enforcing FAANG-level standards.
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

#### 2. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
This repository, `RapidStart-Express-NodeJS-WebApp-Template`, is a modern Node.js web application boilerplate.

*   **PRIMARY SCENARIO: WEB / APP / GUI (Node.js Backend)**
    *   **Stack:** This project is built on **Node.js (LTS v20+)** and **Express.js (5.x)**. It uses **TypeScript 5.x (Strict)** for type safety and maintainability. Views are rendered server-side using **EJS**.
    *   **Development Server:** Use `tsx` or a similar tool for efficient, hot-reloading development workflows.
    *   **Lint/Test/Format:** **Biome.js** is the single source of truth for all linting and formatting. Enforce its rules strictly. Unit and integration tests are managed with **Vitest**.
    *   **Architecture:** Adheres to a strict **Model-View-Controller (MVC)** pattern.
        *   **Controllers (`src/controllers`):** Contain business logic. They orchestrate interactions between routes, services, and models.
        *   **Views (`src/views`):** EJS templates responsible only for presentation logic.
        *   **Routes (`src/routes`):** Define API endpoints and connect them to controller methods.
        *   **Services (`src/services`):** Abstract complex business logic or third-party API interactions away from controllers.
    *   **Containerization:** The project is fully containerized using a multi-stage `Dockerfile`. All production deployments must use the Docker image built from this file.

*   **Verification Commands:**
    *   To verify code quality and formatting before any commit, run: `npm run lint`
    *   To run the test suite, execute: `npm test`

</details>

---

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](.github/CONTRIBUTING.md) file for guidelines on how to submit pull requests.

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/). See the [LICENSE](LICENSE) file for details.
