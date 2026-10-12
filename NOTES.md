# NOTES

- *MCP Server (.mcp.json en raiz - project scope)*: Conecte filesystem con npx @modelcontextprotocol/server-filesystem . . Permission rule: allow solo mcp__filesystem__read_file y mcp__filesystem__list_directory.

- *Skill (.claude/skills/api-route/SKILL.md)*: Flujo repetido de crear ruta API. Description dispara con "create API route".

- *Command (.claude/commands/review.md)*: /review para revision de codigo.

- *Hook (.claude/settings.json project scope)*: PostToolUse matcher Write ejecuta npm run lint. Reacciona despues del evento.

*Headless*: Ejecute claude -p "Revisa el proyecto y genera un reporte de calidad ejecutando lint" --allowedTools "Read, Write, Bash, mcp__filesystem__read_file, mcp__filesystem__list_directory" - Herramientas permitidas: Read, Write, Bash, mcp_filesystemread_file, mcpfilesystem_list_directory. Principio de minimo privilegio.
