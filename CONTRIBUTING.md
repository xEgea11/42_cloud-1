# Contributing to Cloud-1

Thank you for contributing to this project!

This repository is part of the 42 School **Cloud-1** project and is also used as a practical learning environment for GitHub best practices and preparation for the **GitHub Foundations (GH-900)** certification.

Our objective is not only to build a functional cloud infrastructure, but also to follow a professional software development workflow.

---

# Development Workflow

The project follows a simplified Git Flow model.

* `main` contains the stable version of the project.
* `develop` is the integration branch.
* All new work starts from a branch created from `develop`.
* Changes are merged through Pull Requests.

Example:

```text
main
│
└── develop
     ├── feature/docker
     ├── feature/ansible
     ├── feature/nginx
     └── fix/firewall
```

---

# Branch Naming

Use descriptive branch names with one of the following prefixes:

| Prefix      | Purpose                                         |
| ----------- | ----------------------------------------------- |
| `feature/`  | New functionality                               |
| `fix/`      | Bug fixes                                       |
| `docs/`     | Documentation                                   |
| `chore/`    | Repository maintenance or configuration         |
| `refactor/` | Improve existing code without changing behavior |
| `test/`     | Testing-related work                            |

Examples:

* `feature/docker`
* `feature/github-actions`
* `docs/readme`
* `fix/nginx-config`

---

# Commit Messages

This repository follows the **Conventional Commits** specification.

Format:

```text
<type>: <short description>
```

Supported commit types include:

* `feat`
* `fix`
* `docs`
* `refactor`
* `test`
* `chore`

Examples:

```text
feat: add Docker Compose configuration
fix: correct MariaDB credentials
docs: update deployment guide
chore: configure GitHub Actions
```

Keep commit messages concise, descriptive, and written in the imperative mood.

---

# Pull Requests

Every change should be submitted through a Pull Request.

Before opening a Pull Request:

* Ensure the work satisfies the associated GitHub Issue.
* Synchronize your branch with `develop` if necessary.
* Link the related GitHub Issue.
* Write a clear description of the changes.
* Request a review from your teammate.

Each Pull Request should focus on a single objective whenever possible.

---

# Code Reviews

Code reviews are intended to improve the quality and maintainability of the project.

Reviewers should:

* Verify correctness.
* Suggest improvements where appropriate.
* Ensure consistency with the project's architecture.
* Ask questions when clarification is needed.

Authors should:

* Address review comments.
* Resolve discussions before merging.
* Treat feedback as part of the development process.

---

# Project Management

All work should begin with a GitHub Issue.

Each Issue should:

* Belong to a milestone.
* Be assigned to one owner.
* Include the appropriate labels.
* Clearly define its objective.
* Include a Definition of Done.

Work progresses through the GitHub Project board using the following workflow:

```text
Ideas
↓
Backlog
↓
In Progress
↓
Review
↓
Done
```

---

# Definition of Done

A task is considered complete when:

* The implementation satisfies the requirements described in the GitHub Issue.
* The work has been committed and pushed to the corresponding branch.
* A Pull Request has been opened.
* The Pull Request has been reviewed and approved.
* Any requested changes have been addressed.
* The Pull Request has been merged into `develop`.
* The related GitHub Issue has been closed.

---

# Questions

If you are unsure how to proceed, discuss the approach with your teammate before making significant architectural or workflow changes.
