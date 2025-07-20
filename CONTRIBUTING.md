# Contributing to Reflexionary

Welcome, Reflexionary team member! We're building the AI financial co-pilot that's redefining personal finance. Your contributions are vital to making this project a success.

**Our motto:** "Our code's pristine, and so are our terminals." We believe in clean, impactful code that drives real value.

---

## How to Contribute

This guide outlines our internal development practices to ensure smooth collaboration and efficient progress on Tacit.

###Initial Setup

- **Set up Your Environment:**

  - Ensure you have Python 3.9+ installed.
  - Create and activate a virtual environment:

    - macOS/Linux:

      ```sh
      python -m venv .venv
      source .venv/bin/activate
      ```

    - Windows PowerShell:

      ```sh
      python -m venv .venv
      .\.venv\Scripts\activate
      ```

  - Install dependencies:

    ```sh
    pip install -r requirements.txt
    ```

  - **Firebase Setup:** If your feature requires Firebase, ensure you've downloaded your `firebase-adminsdk.json` and set the `GOOGLE_APPLICATION_CREDENTIALS` environment variable locally.

- **Understand the Vision:** Familiarize yourself with Tacit's core mission and the specific features we're targeting (Goal-Based Planning, Anomaly Detection, Memory Management, Mathematical Intelligence).

### Making Changes

- **Branching:** Always create a new branch for your work:

  ```sh
  git checkout -b feature/your-feature-name
  # or
  git checkout -b bugfix/issue-description
  ```

- **Commit Messages:** Write clear, concise commit messages. Start with a verb (e.g., "Feat: Add anomaly detection logic," "Fix: Correct data preprocessing bug").

- **Code Style:** We aim for clean, readable Python code. Follow PEP 8 guidelines. Prioritize clarity and maintainability.

- **Testing:** If you're adding new functionality, include simple tests (even if just local script tests for a hackathon) to verify your changes.

### Submitting Your Work (Pull Requests)

- **Push Your Branch:**

  ```sh
  git push origin feature/your-feature-name
  ```

- **Open a Pull Request (PR):**

  - Go to the GitHub repository page and open a new PR.
  - Provide a clear title and description of your changes.
  - Reference any related issues.
  - Explain what problem your PR solves and how it was implemented.

- **Code Review:** Be open to feedback! We're all here to learn and make the project better.

### Reporting Bugs & Suggesting Enhancements (Internal)

- **Issues:** If you find a bug or have an idea for an enhancement, please open an issue on the GitHub repository. Provide as much detail as possible.

### Hackathon-Specific Notes (30-Hour Sprint!)

- **Prioritize MVP:** Focus on getting core functionality working. Polish comes second.

- **Mock Data:** Don't get stuck on live API integrations. Use well-structured mock data for demos.

- **Communication:** Over-communicate with your team! Use GitHub issues, discussions, or your preferred chat platform.

- **Demo Focus:** Think about how your contribution will be showcased in the final demo.

---
