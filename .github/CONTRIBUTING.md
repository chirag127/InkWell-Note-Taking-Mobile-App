# Contributing to InkWell-Note-Taking-Mobile-App

Thank you for considering contributing to InkWell! We welcome all contributions, from bug reports and feature requests to code contributions and documentation improvements.

This project adheres to the Apex Technical Authority standards. All contributions must align with these principles, ensuring high quality, velocity, and future-proofing.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. Please review the [CODE_OF_CONDUCT.md](https://github.com/chirag127/InkWell-Note-Taking-Mobile-App/blob/main/CODE_OF_CONDUCT.md) file for details on expected behavior.

## 2. How to Contribute

### 2.1 Reporting Bugs

1.  **Search Existing Issues:** Before reporting a bug, please check our existing [Issues](https://github.com/chirag127/InkWell-Note-Taking-Mobile-App/issues) to see if it has already been reported.
2.  **Create a New Issue:** If your bug is not already reported, please create a new issue using the **Bug Report** template. Provide as much detail as possible, including:
    *   A clear and concise description of the bug.
    *   Steps to reproduce the bug.
    *   The expected behavior vs. the actual behavior.
    *   Your environment (OS, device, InkWell version).
    *   Relevant screenshots or error logs.

### 2.2 Suggesting Enhancements

If you have an idea for a new feature or an improvement to an existing one, please create a new issue using the **Feature Request** template.

### 2.3 Submitting Pull Requests (Code Contributions)

We encourage you to submit pull requests (PRs) for bug fixes and new features.

1.  **Fork the Repository:** Create a fork of the `chirag127/InkWell-Note-Taking-Mobile-App` repository.
2.  **Clone Your Fork:** Clone your forked repository to your local machine:
    bash
    git clone https://github.com/chirag127/InkWell-Note-Taking-Mobile-App.git
    cd InkWell-Note-Taking-Mobile-App
    
3.  **Create a New Branch:** Create a descriptive branch for your changes:
    bash
    git checkout -b feature/your-new-feature
    # or
    git checkout -b fix/bug-description
    
4.  **Make Your Changes:** Implement your bug fix or new feature. Follow the architectural guidelines and coding standards outlined in the project's documentation (refer to `AGENTS.md` for specific tech stack directives).
5.  **Install Dependencies:**
    bash
    npm install
    # or
    yarn install
    
6.  **Run Linters and Tests:** Ensure your changes pass all automated checks:
    bash
    npm run lint
    npm run test
    
    *Note: Consult `AGENTS.md` for specific commands if they differ.* 
7.  **Commit Your Changes:** Write clear and concise commit messages.
    bash
    git add .
    git commit -m "feat: Add intuitive note editing functionality"
    
8.  **Push to Your Fork:** Push your branch to your fork on GitHub:
    bash
    git push origin feature/your-new-feature
    
9.  **Open a Pull Request:** Navigate to the original repository (`chirag127/InkWell-Note-Taking-Mobile-App`) and open a new pull request from your branch. Ensure your PR description is clear and references any related issues.

### 2.4 Development Environment Setup (React Native & Expo)

Refer to the main `README.md` for detailed setup instructions. Typically, this involves:

*   **Node.js and npm/yarn:** Ensure you have a compatible version installed.
*   **Expo CLI:** Install globally: `npm install -g expo-cli`.
*   **Native Dependencies:** Follow Expo's documentation for setting up Android Studio or Xcode if needed for device testing.

## 3. Project Structure & Architecture

This project follows the **Feature-Sliced Design (FSD)** pattern to maintain a scalable and maintainable codebase. Please familiarize yourself with FSD principles before making significant architectural changes.

Refer to the `AGENTS.md` file for specific technical stack details, linter configurations, and testing frameworks used.

## 4. Coding Standards & Guidelines

*   **Language:** TypeScript (Strict mode enabled).
*   **Formatting & Linting:** Utilize **Biome** for code formatting and linting. The configuration is managed in `biome.json`.
*   **Testing:** Employ **Vitest** for unit tests and **Playwright** for end-to-end (E2E) tests. All new code should be accompanied by relevant tests.
*   **SOLID Principles:** Adhere to SOLID principles (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion) to ensure robust and maintainable code.
*   **DRY (Don't Repeat Yourself):** Avoid redundant code by abstracting common functionalities.
*   **YAGNI (You Ain't Gonna Need It):** Implement features based on current needs rather than anticipating future requirements.

## 5. Versioning & Releases

This project uses Semantic Versioning (SemVer). Please ensure your contributions align with the established versioning strategy. Major changes or features should be discussed before implementation.

## 6. Questions & Support

If you have any questions or need clarification on the contribution process, please open an issue.

We appreciate your efforts in making InkWell a better tool for everyone!
