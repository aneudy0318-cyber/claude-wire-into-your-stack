# NOTES

- *.mcp.json*: Servidor filesystem configurado en project scope (raiz). Command: npx, args: ["-y", "@modelcontextprotocol/server-filesystem", "."], env: {}. Da acceso seguro solo al proyecto.

- *Skill api-route*: Creada en .claude/skills/api-route/SKILL.md. Define como crear una nueva ruta API con validacion y manejo de errores.

- *Command /review*: Creado en .claude/commands/review.md. Ejecuta revision de codigo buscando bugs y problemas de calidad.

- *Hook PostToolUse*: Configurado en .claude/settings.json. Matcher: Write, tipo: command, ejecuta npm run lint despues de cada Write para validar.

- *Tarea headless ejecutada*: Ejecute claude -p "Revisa el proyecto y genera un reporte de calidad ejecutando lint" en modo headless con allowedTools limitado a Read, Write, Bash y permissions.allow solo con mcp__filesystem__read_file y mcp__filesystem__list_directory para principio de minimo privilegio.
