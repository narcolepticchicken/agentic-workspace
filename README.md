# Agentic Workspace

Professional agentic coding setup with 68+ organized agents, MCP integrations, and portable configuration.

## Quick Setup

```bash
# Clone and use
git clone <your-repo-url> agentic-workspace
cd agentic-workspace
cc  # Start Claude Code with full agent setup
```

## Structure

- `agents/` - 68 specialized agents organized by function
- `.mcp.json` - MCP server configuration (shared with team)
- `CLAUDE.md` - Auto-loaded project context
- `.claude/commands/` - Custom slash commands

## Agent Categories

- **Architecture**: Backend, API, Cloud, Monorepo design
- **Development**: Language specialists, AI, Frontend, Data
- **Quality**: Code review, Testing, Security, Performance
- **Platform**: MLOps, Containers, Kubernetes, CI/CD
- **Data**: Scientists, RAG, Databases, Vector indexing
- **Product**: Strategy, Planning, Specs, Orchestration
- **Compliance**: Privacy, Regulatory, Contracts, Legal

## Usage

Start Claude Code in this directory to automatically load:
- All 68 agents via the Task tool
- MCP servers (GitHub, Sequential Thinking, File System, etc.)
- Project context and best practices

## Customization

Add your API keys to `.mcp.json`:
```json
{
  "mcpServers": {
    "github": {
      "env": {"GITHUB_TOKEN": "your_token_here"}
    }
  }
}
```