# Best-Practice .github Template

This repository is a **GitHub Template** that provides a professional, best-practice set of files for your project's `.github` directory.

When you use this template, you will get:
* **Modern Issue Forms:** YAML-based, structured forms for "Bug Reports" and "Feature Requests."
* **Pull Request Template:** A checklist that appears every time someone (or you) opens a Pull Request.
* **Basic CI Workflow:** A simple GitHub Action that runs a "linter" (code-cleanliness check) and "tests" on every push.

## How to Use

1.  Click the green "**Use this template**" button above.
2.  Choose "**Create a new repository**".
3.  Give your new repository its own name (e.g., `my-new-python-project`).
4.  All the files from this template's `.github` folder will be copied into your new project, instantly giving it professional tooling!

## How to Customize

1.  **Issue Forms (`.github/ISSUE_TEMPLATE/`):**
    * You can edit the `.yml` files to add, edit, or remove fields.
    * [Link to GitHub's documentation on issue forms](httpsis://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)
2.  **Pull Request Template (`.github/pull_request_template.md`):**
    * Edit this Markdown file to change the checklist.
3.  **Workflow (`.github/workflows/lint-and-test.yml`):**
    * This is a "demo" workflow. You **must** edit it for your project's specific language (e.g., Python, Node.js, etc.).
    * Replace the placeholder `run: echo "Testing..."` steps with your actual test commands.
