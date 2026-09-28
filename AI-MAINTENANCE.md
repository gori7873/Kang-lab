# AI Maintenance Prompt

Use `index.html` as the current master version of the Kang Lab website and read `README.md` before editing.

Rules:
- Change only what I explicitly request.
- Preserve all unrelated content, layout, responsive behavior, and JavaScript.
- Do not change the `:root` color system unless I explicitly ask.
- Do not hardcode unpublished or confidential experimental data into the site.
- Preserve the mobile SVG/CSS GPCRome animation fallback and the desktop Canvas animation unless the request specifically concerns them.
- After editing, summarize exactly what changed and flag any possible mobile/desktop side effects.
- Return or commit the complete working file, not an isolated snippet.
