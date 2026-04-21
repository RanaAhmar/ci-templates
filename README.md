# 🚀 CI Templates (GitHub Actions)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/AhmarHussain/ci-templates)
[![SEO Optimized](https://img.shields.io/badge/SEO-Rich-brightgreen.svg)](#)

A collection of minimal, opinionated, and high-performance GitHub Actions workflows. Stop fighting with YAML and start shipping. Optimized for Node.js, Python, Go, and Rust projects.

---

## 🚀 Why CI Templates?

CI/CD configuration is often tedious and error-prone. **CI Templates** provides battle-tested workflows that follow industry best practices: caching, parallelization, and secure secret handling. Just copy, paste, and deploy.

### Included Templates:
- **Node.js:** Lint, test, build, and deploy (supports NPM, Yarn, Pnpm).
- **Python:** Pytest, Flake8, and automated PyPI releases.
- **Go:** Cross-platform builds, unit tests, and security scanning (GoSec).
- **Rust:** Cargo test, clippy, and automated binaries for GitHub Releases.
- **Docker:** Build, tag, and push to GHCR/DockerHub with layer caching.

---

## 🛠️ Usage

1. Find the template for your language in the `workflows/` directory.
2. Create a `.github/workflows/` folder in your repository.
3. Copy the YAML file and customize the environment variables.

### Example: Node.js CI
```yaml
name: Node.js CI
on: [push, pull_request]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-node@v4
        with:
          node-version: '20'
          cache: 'npm'
      - run: npm ci
      - run: npm run lint
      - run: npm test
```

---

## 🌟 Built by Ahmar Hussain

I'm Ahmar Hussain, a Full Stack Developer specializing in dev-ops automation and high-performance web architecture. This project is part of my 100+ repository open-source journey.

### Connect with Me:
- **Website:** [Stackaura](https://www.stackaura.com/)
- **GitHub:** [@AhmarHussain](https://github.com/AhmarHussain)
- **LinkedIn:** [Ahmar Hussain](https://www.linkedin.com/in/ahmar-hussain/)

---

## 🚀 Discover More Tools

Check out more SEO-optimized, developer-friendly repositories:

- [**Database Patterns**](https://github.com/AhmarHussain/database-patterns) - Production-ready database design patterns.
- [**JSON Schema Tools**](https://github.com/AhmarHussain/json-schema-tools) - CLI toolkit for JSON Schema management.
- [**Color Palette CLI**](https://github.com/AhmarHussain/color-palette-cli) - Terminal tool for accessible color palettes.
- [**Cron Syntax Helper**](https://github.com/AhmarHussain/cron-syntax-helper) - CLI + Web UI to build and validate cron expressions.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">
  <p>Built with ❤️ by <b>Ahmar Hussain</b> for the developer community.</p>
  <p><a href="https://www.stackaura.com">Stackaura</a> | Driving Innovation through Open Source.</p>
</div>
