# test-repo

## Claude Code skills

- **banana** (`.claude/skills/banana`) — AI image generation Creative Director powered by Google's Gemini Nano Banana models. Source: [AgriciDaniel/banana-claude](https://github.com/AgriciDaniel/banana-claude).
  - Use `/banana generate <idea>`, `/banana edit <path> <instructions>`, `/banana chat`, `/banana inspire`, `/banana batch`, `/banana preset`, and `/banana cost` from Claude Code.
  - Before first use, run `/banana setup` (or `python3 .claude/skills/banana/scripts/setup_mcp.py`) to configure the MCP server with a free [Google AI Studio](https://aistudio.google.com/apikey) API key.
  - Includes the `brief-constructor` subagent (`.claude/agents/brief-constructor.md`) used internally to construct prompts.
