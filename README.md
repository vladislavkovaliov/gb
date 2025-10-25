# Git Branch Helper (`gb`)

A Bash helper script to create and switch Git branches with optional interactive branch type selection. Designed to streamline Git workflow and enforce consistent branch naming conventions.

---

## Features

- Create feature branches with type prefixes (`fix/`, `feat/`, `refactor/`, `ci/`, `chore/`, etc.)
- Switch to existing branches without creating duplicates
- Supports standard branches like `main`, `dev`, `staging` without prompts
- Compatible with remote branches on `origin`
- Interactive branch type selection using [gum](https://github.com/charmbracelet/gum)
- Works in the current terminal session when sourced

---

## Requirements

- `bash`
- `git`
- [gum](https://github.com/charmbracelet/gum)

Install `gum`:

**macOS:**

```bash
brew install charmbracelet/tap/gum
```

**Ubunbu:**

```bash
sudo apt install gum
```

---

## Installation

```
brew tap vladislavkovaiov/gb

brew install vladislavkovaiov/gb/gb
```

Follow instruction after Installation.

---

## Usage

```bash
gb feature
# or
gb main
```
