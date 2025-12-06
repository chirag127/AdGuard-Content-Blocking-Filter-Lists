<div align="center">

  <img src="https://raw.githubusercontent.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/main/.github/assets/repository-hero.png" alt="AdGuard Content Blocking Filter Lists Banner" width="full">

  <h1>AdGuard-Content-Blocking-Filter-Lists</h1>

  <p>A curated collection of filter lists designed for ad blockers, enhancing browsing privacy and user experience by blocking unwanted content across various platforms and services.</p>

  <p>
    <a href="https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/actions/workflows/validate.yml">
      <img src="https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/actions/workflows/validate.yml/badge.svg?branch=main&event=push" alt="Validate Workflow Status" style="max-width: 100%;" />
    </a>
    <a href="https://img.shields.io/badge/Tech%20Stack-Filter%20Lists%20%7C%20AdGuard%20%7C%20uBlock-blueviolet?style=flat-square">
      <img src="https://img.shields.io/badge/Tech%20Stack-Filter%20Lists%20%7C%20AdGuard%20%7C%20uBlock-blueviolet?style=flat-square" alt="Tech Stack" style="max-width: 100%;" />
    </a>
    <a href="https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/actions/workflows/validate.yml">
      <img src="https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/actions/workflows/validate.yml/badge.svg?branch=main&event=push" alt="Filter List Validation" style="max-width: 100%;" />
    </a>
    <a href="https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey?style=flat-square" alt="License" style="max-width: 100%;" />
    </a>
    <a href="https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/stargazers">
      <img src="https://img.shields.io/github/stars/chirag127/AdGuard-Content-Blocking-Filter-Lists?style=flat-square&color=yellow" alt="GitHub Stars" style="max-width: 100%;" />
    </a>
  </p>

  <h3>Star ⭐ this Repo!</h3>

</div>

## 📖 Table of Contents

- [Introduction](#introduction)
- [Key Features](#key-features)
- [Getting Started](#getting-started)
  - [Installation/Usage](#installationusage)
- [Repository Structure](#repository-structure)
- [AI Agent Directives](#ai-agent-directives)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🚀 Introduction

`AdGuard-Content-Blocking-Filter-Lists` is a meticulously maintained repository providing highly effective filter lists to enhance your online privacy and browsing experience. It serves as a central hub for blocking advertisements, trackers, annoying elements, and other unwanted content across various web browsers and applications supported by popular ad blockers like uBlock Origin and AdGuard.

This project aims to deliver robust, regularly updated, and categorized filter lists that empower users with greater control over their digital environment, ensuring a cleaner, faster, and more secure internet experience.

## ✨ Key Features

*   **Comprehensive Blocking:** Targets a wide array of content including ads, social media widgets, tracking scripts, and malicious domains.
*   **Categorized Lists:** Filters are organized into logical categories (e.g., general ads, social media, regional) for easier management and specific use-cases.
*   **Broad Compatibility:** Designed to work seamlessly with leading content blockers such as uBlock Origin, AdGuard, AdBlock Plus, and compatible browsers.
*   **High Performance:** Optimized lists to minimize impact on browsing speed while maximizing blocking efficiency.
*   **Community-Driven:** Open for contributions to continuously improve and expand the effectiveness of the filter lists.
*   **Automated Validation:** CI/CD workflows ensure that new submissions and updates adhere to syntax rules and maintain high quality.

## ⚙️ Getting Started

To start using these filter lists, you generally need to import the raw `.txt` files into your preferred ad blocker. Below are common methods for popular blockers.

### Installation/Usage

#### uBlock Origin (Recommended)

1.  Open uBlock Origin's dashboard (click the uBlock icon -> ⚙️).
2.  Go to the `Filter lists` tab.
3.  Scroll down to `Custom` and check `Import...`.
4.  Paste the URL of the desired filter list (e.g., `https://raw.githubusercontent.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/main/src/general-ads/default.txt`).
5.  Click `Apply changes`.

#### AdGuard (Desktop / Browser Extension)

1.  Open AdGuard settings.
2.  Navigate to `Filters` -> `Custom filters`.
3.  Click `Add filter`.
4.  Paste the URL of the desired filter list (e.g., `https://raw.githubusercontent.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/main/src/social-media/facebook.txt`).
5.  Click `Subscribe`.

#### Manual Integration

You can clone this repository to inspect the lists or contribute:

bash
git clone https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists.git
cd AdGuard-Content-Blocking-Filter-Lists


## 🌳 Repository Structure

The project maintains a clear and intuitive structure, primarily organizing filter lists within the `src/` directory.


AdGuard-Content-Blocking-Filter-Lists/
├── src/
│   ├── general-ads/           # Core lists for general ad blocking
│   │   └── default.txt
│   ├── social-media/          # Lists targeting social media widgets and trackers
│   │   └── facebook.txt
│   ├── trackers/              # Dedicated lists for privacy-invasive trackers
│   │   └── google-trackers.txt
│   └── regional/              # Region-specific filter lists
│       └── eu-specific.txt
├── .github/                   # GitHub Actions workflows and templates
│   ├── workflows/
│   │   └── validate.yml       # Workflow for filter list syntax validation
│   └── ...
├── .gitignore                 # Files and directories to ignore in Git
├── LICENSE                    # Project license (CC BY-NC 4.0)
├── README.md                  # This README file
├── AGENTS.md                  # AI Agent Directives for repository management
└── ...


## 🤖 AI Agent Directives

<details>
<summary>Click to view AI Agent Directives</summary>

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
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**.

*   **PRIMARY SCENARIO: FILTER LISTS / CONTENT BLOCKING (TXT/DAT)**
    *   **Stack:** This project primarily manages and curates filter lists in formats compatible with `uBlock Origin`, `AdGuard`, and similar content blockers. Key technologies involve standardized filter list syntaxes (e.g., Adblock Plus filter syntax, uBlock Origin specific rules), automated validation tools, and a structured repository for easy consumption.
    *   **Architecture:** Follows a **Structured Resource Repository** pattern, organizing filter lists by category (e.g., general ads, social media, trackers) and platform specificity. Emphasis on clarity, modularity of lists, robust version control, and ease of integration.
    *   **Validation:** Utilizes static analysis (e.g., custom scripts, `AdGuard Home` / `uBlock Origin` parsers) via GitHub Actions to ensure syntax correctness, minimize false positives, and optimize list performance. This involves checking for invalid rules, potential conflicts, and common errors.
    *   **Delivery:** Optimized for direct consumption via raw GitHub URLs, with clear documentation for seamless integration into popular content blockers. Automated processes ensure lists are always accessible and up-to-date.

*   **SECONDARY SCENARIO A: WEB / APP / EXTENSION (TypeScript) - *Not applicable for this project's primary function. Reference only for potential future web-based extensions.***
    *   **Stack:** TypeScript 6.x (Strict), Vite 7 (Rolldown), Tauri v2.x (Native), WXT (Extensions).
    *   **State:** Signals (Standardized).
    *   **Lint/Test:** Biome (Speed) + Vitest (Unit) + Playwright (E2E).
    *   **Architecture:** Feature-Sliced Design (FSD).

*   **SECONDARY SCENARIO B: SYSTEMS / PERFORMANCE (Low Level) - *Not applicable for this project. Reference only for future system-level tooling.***
    *   **Stack:** Rust (Cargo) or Go (Modules).
    *   **Lint:** Clippy / GolangCI-Lint.
    *   **Architecture:** Hexagonal Architecture (Ports & Adapters).

---

## 4. ARCHITECTURAL PATTERNS & PRINCIPLES
**Core Directives:**
*   **Modularity:** Each filter list category (`general-ads`, `social-media`, `trackers`, `regional`) must be self-contained and independently manageable.
*   **Clarity:** Filter list syntax must be clean, readable, and follow established conventions (e.g., Adblock Plus filter rules).
*   **Effectiveness:** Prioritize rules that deliver maximum blocking with minimal false positives.
*   **Maintainability:** Easy to update, verify, and extend the filter lists. Automated tools and clear contribution guidelines are paramount.
*   **Single Responsibility Principle (SRP):** Each filter list or section within a list should ideally focus on a single type of blocking or a specific domain set.
*   **Don't Repeat Yourself (DRY):** Avoid redundant rules across different filter lists where a shared rule can be maintained more efficiently.

**Verification Commands (Conceptual):**
Agents should be able to verify the integrity and effectiveness of the filter lists. While direct execution isn't always possible for passive lists, conceptual checks are vital:

*   `validate-list:src/general-ads/default.txt` - Simulates running the GitHub Actions validation script on a specific filter list to check for syntax errors or malformed rules.
*   `preview-blocking:example.com` - (Conceptual) Simulates how a given filter list would affect a specific domain, highlighting blocked elements based on the rules.
*   `lint-all-lists` - Executes the `validate.yml` workflow to perform a full syntax and best-practice check across all filter lists in the repository.
*   `generate-stats:src/trackers/google-trackers.txt` - (Conceptual) Provides metrics on the number of rules, unique domains, and type of blocking rules within a specific list.

---

## 5. DEVELOPMENT STANDARDS & QUALITY ASSURANCE
**Agent Mandate:** Always adhere to the highest standards of quality, security, and performance.

*   **Code Quality (N/A for filter lists, but applies to scripts/tools):** Any accompanying scripts (e.g., for validation, generation) must be robust, well-documented, and follow best practices for their respective languages.
*   **Security (Critical):** All filter lists must be vetted to prevent accidental blocking of legitimate content or malicious rule injection. The `validate.yml` workflow plays a key role here by flagging suspicious patterns.
*   **Performance:** Filter lists should be optimized for efficient parsing by ad blockers. Avoid overly complex regexes or extremely long lists that could degrade browser performance.
*   **Documentation:** Clear and concise documentation for each filter list, explaining its purpose, coverage, and any known limitations.

</details>

## 🤝 Contributing

We welcome contributions to improve and expand these filter lists! Please refer to our [CONTRIBUTING.md](https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/blob/main/.github/CONTRIBUTING.md) for detailed guidelines on how to submit pull requests, report issues, and suggest improvements.

### Contribution Guidelines

*   **Issue Reporting:** Use the provided [bug report template](https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/blob/main/.github/ISSUE_TEMPLATE/bug_report.md).
*   **Pull Requests:** Follow the [pull request template](https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/blob/main/.github/PULL_REQUEST_TEMPLATE.md) and ensure your changes pass the automated validation checks.
*   **Rule Format:** Adhere to the Adblock Plus filter syntax for compatibility.

## 📄 License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License](https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/blob/main/LICENSE).

## 📧 Contact

For any inquiries, suggestions, or collaborations, please open an issue in this repository or contact the maintainer via their GitHub profile [@chirag127](https://github.com/chirag127).