# Maintenance guide

Harbor & Hearth is a deliberately small static site. Keep changes easy to review and safe to host on GitHub Pages.

## Before opening a pull request

- Preview the site through a local HTTP server so relative links and the 404 page can be checked.
- Test every form with keyboard-only navigation and confirm each control has a visible label.
- Check that page titles, descriptions, headings, and navigation links still describe the page accurately.
- Update `CHANGELOG.md` when a change affects customers, contributors, or hosting.
- Keep the site free of build steps, tracking scripts, and dependencies unless the project direction changes intentionally.

## Content conventions

Use sentence case for headings, plain language for customer-facing copy, and stable fragment IDs for links shared in support answers.
