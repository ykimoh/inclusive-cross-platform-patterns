# Inclusive Cross-Platform Patterns

A field-facing reference for designers who practice inclusive cross-platform UX. Twelve patterns organized by the practitioner journey, Empathize, Design, Annotate, Validate.

Live at [ykimoh.github.io/inclusive-cross-platform-patterns](https://ykimoh.github.io/inclusive-cross-platform-patterns/). Indexed from [ykimoh.github.io](https://ykimoh.github.io).

## What's here

- `index.html`, library home page (pattern index)
- `styles.css`, site styles (matches the hub)
- `patterns/<pattern>/`, one directory per pattern, each with its own `index.html` and assets

Plain HTML and CSS, no build step. Served via GitHub Pages from the repo root.

## Accessibility

WCAG 2.1 AA target. Semantic landmarks, skip-link, visible focus indicators, Newsreader display + Public Sans body via Google Fonts, dark-mode via `prefers-color-scheme`. The library's own conformance is part of its evidence, it is tested with axe DevTools, WAVE, and manual keyboard navigation before each push.

## Contributing

Open issues and PRs welcome. For new patterns, follow the entry template documented in the rfe-niw inventory (private). The short version: nine sections, Title, Problem, Pattern, Visual examples, Code snippet, Annotation, WCAG mapping, Related patterns, Further reading.

## License

Content (text, illustrations, prose explanations): [CC BY 4.0](LICENSE-CONTENT.md).
Code samples (HTML, CSS): [MIT](LICENSE-CODE).
