# NOTES
•	MCP Server (.mcp.json): filesystem
npx @modelcontextprotocol/server-filesystem
permission allow:
mcp__filesystem__read_file
mcp__filesystem__list_directory
•	Skill (.claude/skills/api-route/SKILL.md):
create API route
•	Command (.claude/commands/review.md):
/review
•	Hook (.claude/settings.json):
PostToolUse matcher Write runs npm run lint
•	Headless:
claude -p "Revisa el proyecto y genera reporte"
--allowedTools "mcp__filesystem__read_file,
mcp__filesystem__list_directory"
Tools allowed:
mcp__filesystem__read_file,
mcp__filesystem__list_directory
