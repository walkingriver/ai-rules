# AI Rules 

Welcome to the **AI Rules**, a community-driven repository for sharing and
refining configuration files that guide AI coding assistants like GitHub
Copilot, Windsurf, and others.

Our goal is to create a centralized collection of high-quality, reusable rules
files—such as `.windsurfrules` and `.github/copilot-instructions.md`—that help
developers customize AI tools to align with their coding standards, project
requirements, and team workflows.

Whether you're a solo developer tweaking your AI assistant or a team looking to
standardize AI-generated code, this repo is your go-to resource for discovering,
sharing, and improving AI rules files.

## Quick Start

Want to grab a rules file and get coding? Follow these steps:

### Browse and Use Rules Files

1. **Browse Files:** Explore the repository to find rules files such as
   `.windsurfrules` (for Windsurf) or `.github/copilot-instructions.md` (for
   GitHub Copilot).

2. **Download a File:**

   - Click on the file you want.
   - Use the "Raw" button to view the plain text.
   - Copy the content or download the file directly to your project.

3. **Add to Your Project:**

   - For `.windsurfrules`, place it in your project’s root directory (or as
     specified by Windsurf).
   - For `.github/copilot-instructions.md`, place it in the `.github/` folder of
     your repository.
   - Adjust the file to match your coding style or project needs if necessary.

4. **Test It Out:** Open your IDE with the AI tool enabled (e.g., GitHub Copilot
   in VS Code) and see how the rules guide the AI’s suggestions.

5. **Contribute Back:** Found a great file or made improvements? Please
   [contribute back to the repo](#how-to-contribute)!

---

## Why This Repo?

AI coding assistants are powerful, but they shine brightest when guided by
clear, project-specific instructions. Rules files like `.windsurfrules` (for
Windsurf) and `.github/copilot-instructions.md` (for GitHub Copilot) let you
define coding styles, preferred tools, and best practices, ensuring AI outputs
are consistent and relevant.

However, crafting these files can be time-consuming, and finding good examples
is often a challenge.

**That’s where AI Rules Hub comes in! We aim to:**

- Collect well-crafted rules files for various AI tools, languages, and
  frameworks.
- Share best practices to help developers get the most out of their AI
  assistants.
- Collaborate with the community to refine and expand our collection.

---

## What’s in the Repo?

Currently, the repo includes:

- **.windsurfrules**: Configuration files for Windsurf, defining how the AI
  should generate or review code.
- **.github/copilot-instructions.md**: Custom instructions for GitHub Copilot,
  tailoring its suggestions to specific coding standards or project needs.

### File Structure

Here is how we envision structuring the repo.

```
ai-rules-hub/
├── copilot/                            # GitHub Copilot rules files
│   ├── angular-copilot-instructions.md
│   ├── react-copilot-instructions.md   # Still needed
│   └── node-copilot-instructions.md    # Still needed
│   └── your-contribution
├── windsurf/                           # Windsurf rules files
│   ├── angular.windsurfrules
│   └── react.windsurfrules             # Still needed
│   └── your-contribution
└── README.md                           # You’re reading it!
```

---

## How to Contribute

We’re thrilled to have you contribute to AI Rules Hub! Whether you’re adding a
new rules file, improving an existing one, or suggesting better documentation,
your input is valuable.

### Contribution Steps

1. **Fork the Repository:**

   - Click the "Fork" button at the top-right of this page to create a copy of
     the repo under your GitHub account.

2. **Clone Your Fork:**

   ```bash
   git clone https://github.com/walkingriver/ai-rules.git
   cd ai-rules
   ```

3. **Create a Branch:**

   ```bash
   git checkout -b your-branch-name
   ```

4. **Add or Update Files:**

   - Add your rules file (e.g., `.windsurfrules`,
     `.github/copilot-instructions.md`) to the repo.
   - Update the `README.md` or other documentation if needed.

5. **Commit Your Changes:**

   ```bash
   git add .
   git commit -m "Add .windsurfrules for Python Flask projects"
   ```

6. **Push to Your Fork:**

   ```bash
   git push origin your-branch-name
   ```

7. **Submit a Pull Request (PR):**

   - Go to the original repo and click "New Pull Request."
   - Select your branch and provide a detailed description of your changes.
   - Link any relevant issues (e.g., `Closes #123`) if applicable.
   - Submit the PR and wait for feedback from maintainers.

8. **Respond to Feedback:**
   - We’ll review your PR and may suggest changes. Update your branch as needed
     and push new commits.

---

## Contribution Guidelines

To keep the repo organized and high-quality, please follow these guidelines:

- **File Naming:** Use descriptive names for rules files (e.g.,
  `python-flask.windsurfrules` or `react-copilot-instructions.md`).
- **Documentation:** Include a brief comment or section in your rules file
  explaining its purpose, target AI tool, and any specific context (e.g.,
  language, framework).
- **Formatting:** For Markdown files like `.github/copilot-instructions.md`, use
  clear, concise Markdown. For other formats, follow the AI tool’s conventions.
- **No Sensitive Data:** Ensure rules files don’t contain sensitive information
  (e.g., API keys, passwords).
- **Test Your Rules:** If possible, test your rules file with the target AI tool
  to confirm it works as intended. interactions.

---

## Ideas for Contributions

Not sure where to start? Here are some ideas:

- Share a `.windsurfrules` file tailored to a specific language (e.g., Go, Rust)
  or framework (e.g., Django, Spring).
- Add a `.github/copilot-instructions.md` for a niche use case, like embedded
  systems or data science.
- Create rules files for other AI tools (e.g., Cursor, Tabnine).
- Write example prompts in `docs/examples.md` showing how to use rules files
  effectively.
- Improve this README with clearer instructions or a FAQ section.

---

## Security Note

Rules files can influence AI behavior, so we take security seriously. Malicious
rules files could introduce vulnerabilities (e.g., via hidden Unicode
characters). To protect our community:

- We scan PRs for suspicious content.
- We encourage contributors to review their rules files for unintended effects.
- If you spot a security issue, report it privately via GitHub Security.

---

## Why Contribute?

By contributing to AI Rules Hub, you:

- Help developers worldwide improve their AI-assisted coding workflows.
- Showcase your expertise in AI tools and coding standards.
- Build a collaborative community around AI-driven development.
- Get your work featured in a growing, open-source project!

---

## Get in Touch

Have questions or ideas? Reach out:

- **Issues:** Report bugs or suggest features via GitHub Issues.
- **Discussions:** Share ideas or ask questions in GitHub Discussions.
- **X:** Follow me on X at [@WalkingRiver](https://x.com/walkingriver) for
  updates and community highlights.

---

## License

This project is licensed under the MIT License (`LICENSE`). Feel free to use,
modify, and share the rules files, but please give credit to the contributors.

---

## Acknowledgments

A huge thank you to all contributors who make AI Rules Hub possible! Special
shoutout to the open-source community for inspiring this project and to tools
like GitHub Copilot and Windsurf for pushing the boundaries of AI-assisted
coding.

---
