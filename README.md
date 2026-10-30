# .github

This repository contains the **default community health files** and the **organization profile content**. GitHub automatically applies them to every repository that does not have its own version of the respective file.

> **Note:** This repository must be public and named exactly `.github` for the default files to take effect.

## Contents

| File / Folder | Description |
| --- | --- |
| `profile/README.md` | Organization profile landing page (publicly visible) |
| `CONTRIBUTING.md` | Contribution guidelines |
| `ISSUE_TEMPLATE/` | Default issue templates (incl. `config.yml`) |
| `PULL_REQUEST_TEMPLATE.md` | Default pull request template |
| `img/` | Images |

## How inheritance works

If a repository in the organization has no file of its own, GitHub shows the version from this repository. If a repository defines its own file, that one takes precedence.
