# Contributing

Thanks for your interest. This repository is a learning portfolio for Programming Laboratory (FE260) exercises and is not intended for production use.

## Ground rules
- Keep the learning focus: clarity over optimization; small, readable changes are preferred.
- Do not commit secrets, tokens, proprietary datasets, or generated binaries. Run a secret scan (e.g., GitGuardian CLI) before pushing.
- Follow the existing build flow (GCC/Clang) and keep `.gitignore` clean.
- Add concise comments only where logic is non-obvious.

## How to contribute
1. Fork or create a branch for your experiment.
2. Make your change in a single exercise file when possible to keep diffs small.
3. Build with warnings enabled (`-Wall -Wextra -pedantic`) and fix issues you introduce.
4. Run a secret scan and review your diff before opening a pull request or merging.

## Code of conduct
Be respectful and constructive. This is a space for learning and collaboration.
