# Contributing to Cosmic Observatory

Thank you for your interest in contributing to Cosmic Observatory. We welcome contributions from astronomers, web developers, educators, designers, and science enthusiasts.

Please review this document carefully to ensure a smooth contribution process.

---

## Code of Conduct

By participating in this project, you agree to uphold a welcoming, respectful, inclusive, and professional environment for everyone. Discriminatory, harassment, or abusive behavior will not be tolerated.

---

## How You Can Contribute

1. **Reporting Bugs**: Found a layout glitch, broken link, or JavaScript error? Open an issue detailing the steps to reproduce.
2. **Feature Requests**: Suggest new astronomy tools, interactive charts, or scientific data visualizations.
3. **Content Enhancements**: Improve scientific descriptions, add new astronomical facts, or update space mission milestones.
4. **Code Improvements**: Optimize CSS animations, improve accessibility (a11y), clean up JavaScript DOM handlers, or refactor layouts.

---

## Workflow & Pull Request Process

### 1. Fork and Clone

Fork the repository to your GitHub account and clone it locally:

```bash
git clone https://github.com/your-username/cosmic-observatory.git
cd cosmic-observatory
```

### 2. Create a Feature Branch

Create a descriptive branch for your proposed changes:

```bash
git checkout -b feature/add-exoplanet-chart
```

### 3. Make and Verify Changes

Ensure your changes follow the project standards:
- All HTML files must remain valid and semantic.
- CSS changes should utilize existing root custom variables (`css/style.css`).
- JavaScript additions should avoid global scope pollution and handle DOM queries safely.
- No emojis should be added to documentation or core system files if strictly specified.

### 4. Test Locally

Run tests and manually verify:
- Test responsive layouts on mobile, tablet, and desktop viewports.
- Check the browser console for zero JavaScript warnings or errors.
- Ensure all relative navigation links function across sub-pages in `pages/`.

### 5. Submit Pull Request

Push your feature branch and open a Pull Request (PR):

```bash
git push origin feature/add-exoplanet-chart
```

In your PR description, provide:
- A clear summary of the changes made.
- References to any related issue numbers (e.g., `Fixes #12`).
- Screenshots or video captures of visual UI updates if applicable.

---

## Coding Guidelines

### HTML Style Guide
- Use 2-space or 4-space consistent indentation.
- Maintain semantic elements (`<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- Include appropriate `aria-*` attributes and image `alt` tags for accessibility.

### CSS Style Guide
- Define theme colors using CSS Custom Properties (`var(--primary-color)`).
- Ensure smooth CSS transitions adhere to `--transition` variables.
- Maintain responsive break points aligned with Bootstrap 5 grid utilities.

### JavaScript Style Guide
- Write clean ES6+ syntax (`const`, `let`, arrow functions, array methods).
- Wrap DOM initializations inside `DOMContentLoaded` event handlers.
- Document complex calculations (such as astronomical unit conversions) with clear inline comments.

---

## Questions & Support

If you have questions about contributing, feel free to open a discussion or bug report issue in the project repository.
