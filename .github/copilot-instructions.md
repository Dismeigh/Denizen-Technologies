# Copilot / AI Assistant Instructions

Purpose: Quick, actionable guidance so an AI coding assistant can be productive immediately in this repository.

- **Repo type:** Minimal static website. Current files at root: `index.html` (empty), `README.md` (project title only). No build system, package manifest, or CI detected.

- **Big picture:** This repo is a single-page static site. All site content should live in `index.html` or in files you add under new top-level folders (e.g., `css/`, `assets/`, `images/`). Keep changes minimal and explicit—there is no bundler or server-side component.

- **Where to make changes:**
  - **Content:** Edit `index.html` for page content and structure.
  - **Documentation:** Update `README.md` if you add site features, build steps, or hosting details.
  - **New assets:** If adding CSS/JS/images, create a clear folder (suggested: `css/`, `js/`, `assets/`) and reference them using relative paths from `index.html`.

- **No build/test commands:** None found. Do not add tooling without proposing it in a PR and documenting reasons in `README.md`.

- **Project-specific patterns / expectations:**
  - Keep changes atomic: small HTML edits or a single feature per PR.
  - If adding files, update `README.md` with brief usage/hosting notes.
  - Prefer plain, compatible HTML (avoid framework scaffolding unless requested).

- **PR & commit guidance (examples):**
  - Commit message: `Update index.html — add hero section`.
  - PR description: short summary, files changed, and any manual verification steps (e.g., open `index.html` in browser).

- **Examples from this repo:**
  - To add a hero section, modify `/index.html` near the top-level <body>; include any styles inline or in `css/styles.css` and link it.
  - If adding multiple images, create `/assets/images/` and reference as `<img src="assets/images/example.png">`.

- **When to ask the maintainers:**
  - If you need hosting/CI access details (e.g., GitHub Pages settings).
  - If you plan to introduce a build system (npm, webpack, etc.)—get approval first and document the new workflow.

- **Do not assume:** There's no existing CI, published package, or backend. Verify before adding integrations.

If anything here is unclear or you want conventions expanded (naming rules, branching model, hosting), tell me which areas to improve and I will iterate.
