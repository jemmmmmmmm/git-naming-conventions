#### Branch Naming Convention

Use clear, descriptive branch names that reflect the type and scope of the change.

| Prefix       | Purpose                                           |
|--------------|--------------------------------------------------|
| `styles`     | Visual-only changes (Tailwind, layout, spacing, colors)  |
| `components` | Component structure or logic updates             |
| `feature`    | New features or user-facing functionality        |
| `pages`      | Page-level routing or layout changes             |
| `chore`      | Dev tooling, configs, scripts, dependencies      |
| `refactor`   | Code cleanup or re-org with no behavior changes  |
| `fix`        | Bug fixes                                        |

**Example:**
> **styles/sidenav-scrollbar components/input-validation feature/user-profile**


---

####Commit Message Convention

Follow the `<type>: <short description>` format for clarity and consistency.

| Type       | Purpose                                              |
|------------|------------------------------------------------------|
| `feat`     | New feature                                          |
| `fix`      | Bug fix                                              |
| `style`    | Visual changes only (CSS, Tailwind, spacing, colors) |
| `refactor` | Code cleanup/refactoring (no behavior change)        |
| `page`     | Page-level changes (Next.js-specific)                |
| `chore`    | Dev tool changes, config updates, maintenance        |
| `docs`     | Documentation updates                                |
| `test`     | Adding or updating tests                             |

**Examples:**
> **feat: add login modal fix: reset input on modal close style: update button hover effect refactor: simplify validation logic**


---


- Use **kebab-case** for branch names.
- Keep commit messages under **50 characters**.
- Write commit messages in **imperative mood** (e.g., "add", not "added").



