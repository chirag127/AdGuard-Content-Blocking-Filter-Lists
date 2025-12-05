# Contributing to AdGuard-Content-Blocking-Filter-Lists

Thank you for considering contributing to the `AdGuard-Content-Blocking-Filter-Lists` repository! This project aims to maintain a high-quality, curated collection of filter lists for enhanced browsing privacy and user experience.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. Please ensure your contributions are respectful and inclusive. For more details, see [CODE_OF_CONDUCT.md](https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/blob/main/CODE_OF_CONDUCT.md).

## 2. How to Contribute

We welcome various forms of contribution, including:

*   **Reporting Bugs:** If you find a bug in an existing filter list or a general issue with the project, please submit a detailed bug report via the [GitHub Issues](https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/issues) page.
*   **Suggesting Enhancements:** Propose new filter lists, improvements to existing ones, or new features for the project. Use the [GitHub Issues](https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/issues) page for suggestions.
*   **Submitting Pull Requests:** The most direct way to contribute is by submitting code or filter list updates. Please follow the guidelines below.

## 3. Submission Guidelines

### 3.1. Feature Branches

*   Create a feature branch for your contribution from the `main` branch:
    bash
    git checkout main
    git pull origin main
    git checkout -b feature-your-contribution-name
    

### 3.2. Filter List Updates

*   **Best Practices:** When modifying or adding filter lists, ensure they adhere to standard filter list syntax and best practices for ad blocking.
*   **Clarity:** Add comments to explain complex rules or the purpose of a new list/entry.
*   **Testing (Conceptual):** While automated testing for filter lists is complex, manually verify the impact of your changes by applying them in a test environment (e.g., uBlock Origin, AdBlock Plus).

### 3.3. Code Contributions (If Applicable)

*   **Language:** This project is primarily a collection of declarative filter lists. If any scripting or tooling is introduced, it will likely be in **Python**, adhering to the Apex Technical Authority standards.
*   **Linting & Formatting:** Ensure your code adheres to **Ruff** standards. Run `ruff format .` and `ruff check .` before committing.
*   **Testing:** Write comprehensive tests using **Pytest** for any new functionalities.

### 3.4. Committing Changes

*   **Conventional Commits:** Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification for commit messages. This helps in automating changelog generation.
    *   Examples:
        
        feat: Add new filter list for blocking common trackers

        Adds a new list to block tracking scripts from XYZ service.
        
        
        fix: Correct faulty rule in social-media-blockers.txt

        The rule `#123` was incorrectly blocking legitimate content. Adjusted to `#456`.
        
        
        chore: Update README with contribution guidelines
        
*   **Commit Your Changes:**
    bash
    git add .
    git commit -m "<conventional-commit-message>"
    

### 3.5. Submitting a Pull Request

1.  Ensure your branch is up-to-date with `main`:
    bash
    git checkout feature-your-contribution-name
    git rebase main
    
2.  Push your branch to your fork:
    bash
    git push origin feature-your-contribution-name
    
3.  Open a Pull Request on the `chirag127/AdGuard-Content-Blocking-Filter-Lists` repository.
4.  Provide a clear and concise description of your changes.
5.  Link to any relevant issues.

## 4. Project Standards & Directives

This project adheres to the Apex Technical Authority standards, focusing on professionalism, clarity, and maintainability. Key principles include:

*   **Zero-Defect, High-Velocity, Future-Proof:** Strive for quality and efficiency.
*   **Professional Archival:** Even retired products maintain dignity and clarity.
*   **AI Agent Directives:** Understand the role of AI agents in maintaining and enhancing the repository as outlined in [AGENTS.md](https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/blob/main/AGENTS.md).

## 5. Questions & Support

If you have any questions or need clarification, please open an issue on the [GitHub Issues](https://github.com/chirag127/AdGuard-Content-Blocking-Filter-Lists/issues) page.

Thank you for contributing!
