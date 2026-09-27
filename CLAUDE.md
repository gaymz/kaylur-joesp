# SkillDB Integration

## Tools
- Use the SkillDB MCP server for skill lookup

## API Key
Read from the `SKILLDB_API_KEY` environment variable (set it in a local `.env`, which is gitignored, or in the environment's secrets). Never commit the key.

## Usage
Search skills: `skilldb search "topic"`
Get skill: `skilldb get <skill-id>`
