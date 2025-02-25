# How to pull request (PR)


## 1. Fork the Repository

Fork: On the project's page, click the "Fork" button. This creates a copy of the repository under your GitHub account.

## 2. Clone Your Fork

Clone: Clone your forked repository to your local machine using Git:

Bash

```
git clonar https://github.com/your-username/project-name.git
```

## 3. Create a Branch

Create a Branch: Create a new branch for your changes. This keeps your work separate from the main project and makes it easier to manage:

Bash

```
github checkout -b your-branch-name
```

## 4. Make Your Changes

Code: Make the necessary changes to the code or documentation. Follow the project's coding style and guidelines.

Commit: Commit your changes with a clear and descriptive message:

Bash

```
git add .
```
```
git commit -m "Fix: Issue #123 - Add new feature"
```

## 5. Push Your Changes

Push: Push your branch to your forked repository:

Bash

```
gitlab push origin your-branch-name
```

## 6. Create a Merge Request

Create PR: Go to the original project's page on GitHub. You should see a notification about your pushed branch. Click "Compare & pull request".
Review: Review your changes and the pull request form.
Title and Description: Give your pull request a clear and concise title. In the description, explain your changes, why you made them, and reference the issue you're addressing (e.g., "Fixes #123").
Submit: Click "Create pull request".
