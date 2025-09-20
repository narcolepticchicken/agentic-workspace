# Agentic Workspace Configuration

## Project Structure
- `agents/` - Organized by function (architecture, development, quality, etc.)
- `workflows/` - Common task sequences
- `templates/` - Reusable configurations

## Agent Categories
- **Architecture**: System design, API planning, cloud architecture
- **Development**: Language-specific coding, frontend, AI engineering
- **Quality**: Code review, testing, security, performance
- **Platform**: Infrastructure, DevOps, containerization
- **Data**: Analytics, ML, databases, RAG systems
- **Product**: Strategy, specifications, roadmaps
- **Compliance**: Legal, privacy, regulatory requirements

## Usage Patterns
- Use `/` commands for common workflows
- Agents collaborate via handoff notes
- Keep secrets out of prompts and configs
- Prefer minimal, reversible changes

## MCP Integrations
- GitHub for version control
- Sequential thinking for complex planning
- File system for local operations
- Memory bank for session continuity
- PostgreSQL for database operations

## Best Practices
- Start with essential agents for your immediate needs
- Test agent chains before complex workflows
- Regular cleanup of unused configurations
- Version control all agent definitions and workflows