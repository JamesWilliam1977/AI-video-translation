```markdown
# AI-video-translation Development Patterns

> Auto-generated skill from repository analysis

## Overview

This skill teaches the core development patterns, coding conventions, and collaborative workflows used in the `AI-video-translation` Python codebase. You'll learn how to update documentation, optimize and refactor code, fix bugs, develop GUI features with PyQt5, and add new features via the configuration module. The guide provides step-by-step instructions, code style examples, and suggested commands to streamline your contributions.

## Coding Conventions

- **File Naming:** Use `snake_case` for Python files and directories.
  - Example: `cli.py`, `sp.py`, `test.py`, `configure/baidu.py`
- **Import Style:** Use relative imports within the package.
  - Example:
    ```python
    from .tools import some_function
    ```
- **Export Style:** Use named exports; avoid wildcard imports.
  - Example:
    ```python
    def translate_video(...):
        ...
    __all__ = ["translate_video"]
    ```
- **Commit Messages:** Freeform, no strict prefix, average length ~17 characters.

## Workflows

### Update README Files
**Trigger:** When you need to update documentation or reflect new features/changes in the README files.  
**Command:** `/update-readme`

1. Edit `README.md` and/or `README_ENG.md` to document changes.
2. Optionally update or add related images in the `images/` directory.
3. Optionally update `requirements.txt` if dependencies are affected.

---

### Codebase Optimization
**Trigger:** When you want to refactor, optimize, or improve the codebase.  
**Command:** `/optim`

1. Edit core Python files: `cli.py`, `config.py`, `sp.py`, `tools.py`, `test.py`.
2. Optionally update README files to reflect improvements.

---

### Bugfix Across Multiple Core Files
**Trigger:** When you need to fix a bug that impacts multiple parts of the application.  
**Command:** `/bugfix`

1. Identify and fix bugs in core files: `cli.py`, `config.py`, `sp.py`, `tools.py`, `test.py`.
2. Update README files if necessary to document the fix.

---

### GUI Feature Development (PyQt5)
**Trigger:** When you want to add or improve GUI functionality.  
**Command:** `/add-gui-feature`

1. Edit or add `.py` and `.ui` files for the GUI (e.g., `cn.py`, `en.py`, `cn.ui`, `en.ui`).
2. Update README files to describe new or changed GUI features.
3. Update or add images for the GUI in the `images/` directory.
4. Update `requirements.txt` if dependencies change.

---

### Add New Feature with Configure Module
**Trigger:** When you want to add a new translation or configuration feature.  
**Command:** `/add-configure-feature`

1. Create or update files in the `configure/` directory (e.g., `baidu.py`, `chatgpt.py`, `language.py`, `.ui` files).
2. Edit core scripts as needed: `cli.py`, `sp.py`, `test.py`.
3. Update README files to document the new feature.
4. Update `requirements.txt` if new dependencies are introduced.

---

## Testing Patterns

- **Framework:** Unknown (not explicitly detected).
- **File Pattern:** Test files are named with the `.test.ts` extension, suggesting some TypeScript-based tests may exist alongside Python code.
- **Best Practice:** Place tests in files matching `*.test.ts` and ensure they cover both core logic and new features.

## Commands

| Command                | Purpose                                               |
|------------------------|-------------------------------------------------------|
| /update-readme         | Update documentation and related images/requirements. |
| /optim                 | Refactor or optimize codebase and update docs.        |
| /bugfix                | Fix bugs across multiple core files.                  |
| /add-gui-feature       | Add or improve GUI features using PyQt5.              |
| /add-configure-feature | Add new features via the configure module.            |
```
