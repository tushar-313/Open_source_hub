# OpenSource Hub

A small beginner-friendly website created for the **Elevate Git & GitHub Workshop**.

The goal of this project is not to build a complicated application. The goal is to give workshop participants a realistic repository where they can practice the complete Open Source contribution workflow.

## Tech

- HTML5
- CSS3
- Minimal vanilla JavaScript for the footer year

No framework, package manager, or build step is required.

## Run locally

You can open `index.html` directly in a browser, or use a simple local server:

```bash
python -m http.server
```

Then visit `http://localhost:8000`.

## Contribution workflow

1. Fork this repository.
2. Clone your fork.
3. Create a new branch.
4. Pick an Issue.
5. Make the requested change.
6. Run/check the website locally.
7. Commit your change.
8. Push your branch.
9. Open a Pull Request to this repository.

Example branch:

```bash
git switch -c add-contributor-name
```

Example commit:

```bash
git commit -m "Add contributor name"
```

## Contribution guidelines

- Keep changes focused on the Issue you selected.
- Avoid unrelated formatting changes.
- Use clear commit messages.
- Test the website before opening a Pull Request.
- Keep the project beginner-friendly and accessible.
- If an Issue is unclear, ask before implementing a large change.

## Workshop note

This repository is designed for learning Git and GitHub through practice. Small contributions are welcome.
