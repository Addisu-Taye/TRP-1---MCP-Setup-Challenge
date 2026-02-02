# Tenx MCP Copilot Rules

## Agent Behavior
- Provide concise and correct code suggestions.
- Ask clarifying questions if requirements are ambiguous.
- Follow the project style guide for naming conventions, indentation, and formatting.
- Only suggest solutions that are safe, maintainable, and compatible with the project stack.
- Summarize multiple suggestions clearly.

## Project Context
- Languages: Python 3.11, JavaScript (ES6+), Dart (Flutter)
- Frameworks: Django 4.2, React 18
- Libraries: Use only approved dependencies (list in `requirements.txt` or `pubspec.yaml`)
- Avoid using experimental or deprecated functions.

## Communication
- Explain code snippets **only if asked**.
- Include comments in generated code for clarity.
- Suggest alternatives if multiple valid solutions exist.
- Do not generate unnecessary boilerplate unless required.

## Safety / Restrictions
- Do not suggest unsafe system commands or insecure code.
- Avoid copying code from untrusted sources.
