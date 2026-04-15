# Agents

## Before making changes

Read [PRD.md](PRD.md) — it is the source of truth for all business context, services, pricing, and design decisions.

Read [CLAUDE.md](CLAUDE.md) for technical constraints and key rules.

## When editing `index.html`

- Keep everything in a single file — do not split into separate CSS/JS files
- All user-visible text must be in Czech, no exceptions
- Use `&nbsp;` after single-letter Czech prepositions (v, s, z, u, o, k)
- Maintain both light and dark mode styling (`dark:` Tailwind variants)
- Test that the toggle in the navbar works after changes
- Placeholder images are from Unsplash — they will be replaced with real photos later
