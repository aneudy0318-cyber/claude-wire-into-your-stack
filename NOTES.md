# NOTES

- MCP Server (.mcp.json project scope) filesystem server npx @modelcontextprotocol/server-filesystem . permission allow mcp__filesystem__read_file and mcp__filesystem__list_directory
- Skill (.claude/skills/api-route/skill.md): repeated flow create API route. Description triggers on "create API route"
- Command (.cloude/commands/review.md): /review code review shortcut
- Hook (.cloude/settings.json project score): postToolUse matcher write runs npm run lint, reacts after write
- Headless: claude -p "Revisa el proyecto y genera reporte de calidad ejecutando lint" --allowedTools "Read, Write, Bash, mcp__filesystem__read_file, mcp__filesystem__list_directory" Tools allowed: Read, Write, Bash, mcp__filesystem__read_file, mcp__filesystem_list_directory
