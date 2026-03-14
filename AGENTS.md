# AGENTS.md

Instructions for AI coding agents working in this repository.

## Code style

- Match the existing code style, patterns, and conventions in the file you are editing.
- Keep changes minimal and focused on the task at hand.
- Do not refactor unrelated code unless explicitly asked.
- Prefer readability over cleverness.

## Commits

- Use [Conventional Commits](https://www.conventionalcommits.org/) format: `type(scope): description`.
- Keep commit messages concise (under 72 characters for the subject line).
- Each commit should represent a single logical change.

## Testing

- Run the test suite before considering work done.
- Do not delete or skip failing tests without explaining why.
- Add tests for new functionality and bug fixes.
- Verify that existing tests still pass after your changes.

## Error handling

- Do not silently swallow errors.
- Prefer explicit error handling over broad catch-all blocks.
- Include meaningful error messages that help with debugging.

## Dependencies

- Do not add new dependencies without justification.
- Prefer the standard library when it covers the use case adequately.
- Pin dependency versions when adding them.

## Security

- Never commit secrets, credentials, API keys, or tokens.
- Never disable security features or linting rules without explicit approval.
- Treat user input as untrusted.

## Documentation

- Update documentation when changing public APIs or user-facing behavior.
- Do not generate unnecessary documentation files unless asked.
- Prefer inline code comments only where the *why* is not obvious from the code.

## Communication

- Ask for clarification when requirements are ambiguous rather than guessing.
- Explain your reasoning when making non-obvious decisions.
- When multiple valid approaches exist, briefly state the tradeoffs before proceeding.
