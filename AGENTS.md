# Repository Guidelines

## Project Structure & Module Organization
- Current contents are minimal: only `README.md` exists at the repository root.
- As the project grows, keep source code under `src/` and tests under `tests/` (or `test/`), and document any new top-level directories here.

## Build, Test, and Development Commands
- No build or run scripts are present yet (no `CMakeLists.txt`, `Makefile`, or `scripts/`).
- When you add a build system, list the exact commands here (for example, a CMake flow like `cmake -S . -B build` and `cmake --build build`).
- If you add a local run target or server launch command, include the exact invocation and required flags.

## Coding Style & Naming Conventions
- No coding style configuration is tracked yet.
- If you introduce formatting or linting tools (e.g., clang-format), add the config files to the repo and document the enforced rules here (indentation, brace style, naming).
- Keep naming consistent and descriptive; prefer `snake_case` for files and `CamelCase` for types once conventions are established.

## Testing Guidelines
- No tests or testing framework are present yet.
- When tests are added, document:
  - The framework used.
  - The naming pattern (for example, `*_test.cpp`).
  - The command(s) to run tests locally.

## Commit & Pull Request Guidelines
- Commit messages follow a Conventional Commits style as seen in history (e.g., `chore: initial commit`).
- Use the same pattern: `type: short summary` (examples: `feat: add request parser`, `fix: handle empty headers`).
- Pull requests should include:
  - A concise description of the change.
  - Any relevant issue links.
  - Notes on testing (or why tests are not applicable).

## Security & Configuration Tips
- Do not commit secrets or local machine paths.
- If configuration becomes necessary, prefer example files (e.g., `config.example.json`) and document required fields.
