# TRP 1 – MCP Setup Challenge Documentation

## 1. What I Did
- Chose **VS Code** as my preferred IDE (since Claude is unavailable in my region).
- Created the rules file `.github/copilot-instructions.md` in my project workspace.
- Configured rules to guide the AI agent to provide **concise, context-aware, and project-specific code suggestions**.
- Attempted to integrate MCP server connection via `.cursor/mcp.json` and `.cursor/rules/agent.mdc` (for Cursor IDE), even though Validate Agent is not available in VS Code.
- Tested agent behavior by writing code and observing how the AI followed the rules.

## 2. What Worked
- **Rules File Creation**: Successfully created `.github/copilot-instructions.md` in the correct folder.
- **Behavior Alignment**: The AI agent followed instructions for concise suggestions, asking clarifying questions, and respecting project context.
- **Documentation of Attempts**: Able to record all setup steps and AI interactions for review.

## 3. What Didn't Work
- **Claude / Validate Agent**: Claude IDE is unavailable in my region, so I could not use `Validate Agent` or connect Claude to MCP directly.
- **MCP Connection Verification in VS Code**: VS Code’s Copilot does not have a “Validate Agent” feature, so testing had to be **manual** by observing AI behavior.
- **Cursor IDE Integration**: Installing Cursor IDE on my current setup is optional; if installed, the MCP validation works, but in VS Code only rules guidance is possible.

**Troubleshooting Steps Taken**:
1. Attempted to install Claude Code → blocked by regional restriction.
2. Created `.cursor/rules/agent.mdc` and `.cursor/mcp.json` locally to mirror MCP instructions.
3. Observed AI suggestions in VS Code and noted how they adhered to rules.
4. Documented the behavior for assessment purposes.

## 4. Insights Gained
- **Rules file effectiveness**: Clearly specifying agent behavior in a rules file improves the AI’s ability to generate code that aligns with project style and intent.
- **AI behavior alignment**: Explicit instructions (e.g., “ask clarifying questions,” “suggest concise snippets”) guide the AI to reduce irrelevant suggestions.
- **Limitations of environment**: MCP connection features (like `Validate Agent`) depend on IDE capabilities. Observing behavior manually is a valid alternative when certain features are not accessible.
- **Importance of documentation**: Recording every step, challenge, and insight ensures transparency and demonstrates problem-solving skills, which is crucial for assessment.

## Files Created / Changes Made

| File | Location | Purpose |
|------|----------|---------|
| `.github/copilot-instructions.md` | Project root | Guide AI agent behavior |
| `.cursor/rules/agent.mdc` | `.cursor/rules/` | MCP agent rules (Cursor IDE) |
| `.cursor/mcp.json` | `.cursor/` | MCP server connection info |
