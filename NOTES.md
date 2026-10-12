# NOTES

- .mcp.json: servidor filesystem en project scope con npx, acceso seguro al proyecto.
- Skill api-route: en .claude/skills/api-route/SKILL.md para crear rutas.
- Command /review: en .claude/commands/review.md para revisión de código.
- Hook PostToolUse: en .claude/settings.json con matcher "Write" que ejecuta npm run lint.
- Seguridad: Task con allowedTools limitado a Read, Write, Bash.
