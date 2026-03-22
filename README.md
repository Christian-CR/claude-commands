# Create Slash Commands

Custom slash commands for Claude Code.

## Commands

- **`/commit-code`** - Review changed files and create a commit with a summary message

## Adding New Commands

1. Create a new markdown file in `.claude/commands/` directory
2. Start with a heading (e.g., `# Command Name`)
3. Add description and instructions
4. The file will be available as a slash command with the filename (without .md extension)

## File Structure

```
.claude/commands/
├── commit-code.md
└── [your-command].md
```
