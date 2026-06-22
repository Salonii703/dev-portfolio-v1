# Contributing to Dev Portfolio v1

Thank you for considering contributing to this project! Here's how to get started.

## How to Contribute

1. Fork this repository
2. Clone your fork locally:
```bash
   git clone https://github.com/<your-username>/dev-portfolio-v1.git
```
3. Create a new branch for your feature or fix:
```bash
   git checkout -b feat/your-feature-name
```
4. Make your changes and test them locally by opening `index.html` in your browser
5. Commit your changes using the commit message convention below
6. Push to your fork and open a Pull Request

## Commit Message Convention

Use these prefixes for clear commit history:

| Prefix   | Use case                              |
|----------|----------------------------------------|
| `feat:`  | New feature (e.g., `feat: add contact form validation`) |
| `fix:`   | Bug fix (e.g., `fix: correct dark mode toggle on mobile`) |
| `docs:`  | Documentation changes (e.g., `docs: update README`) |
| `style:` | Code formatting, no logic change (e.g., `style: fix indentation`) |

## Code Guidelines

- Keep all CSS in `css/style.css` — no inline styles
- Keep all JavaScript in `js/script.js`
- Use semantic HTML5 tags (`header`, `main`, `section`, `footer`, `nav`)
- Test responsiveness on mobile before committing
- Remove any commented-out or dead code before pushing

## Reporting Issues

If you find a bug, please open an issue describing:
- What you expected to happen
- What actually happened
- Steps to reproduce