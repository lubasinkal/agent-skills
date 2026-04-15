# OpenCode Agent Skills

A collection of useful skills for the opencode AI assistant.

## Skills

### caveman
Ultra-compressed communication mode. Cuts token usage ~75% by speaking like a caveman while keeping full technical accuracy. Supports intensity levels: lite, full, ultra, and wenyan variants.

**Usage:** Say "caveman mode", "talk like caveman", or invoke `/caveman`

### find-docs
Retrieves up-to-date documentation, API references, and code examples for any developer technology using Context7.

**Usage:** Automatically activated when asking about libraries, frameworks, or needing code examples.

### find-skills
Helps discover and install agent skills from the open agent skills ecosystem.

**Usage:** Ask "how do I do X", "find a skill for X", or "is there a skill for X"

### context7-mcp
Wrapper skill for Context7 MCP server integration.

## Installation

These skills are installed via the opencode skills system. To add more skills:

```bash
npx skills find <query>
npx skills add <owner/repo@skill>
```

## License

MIT