# Programming-Laboratory-SEM2

![Status: Learning](https://img.shields.io/badge/status-learning-blue)
![License: BSD-3-Clause](https://img.shields.io/badge/license-BSD--3--Clause-green)

Practical C exercises from the FE260 Programming Laboratory. This repository is maintained as a learning portfolio rather than a production project.

## Intent and scope
- Learning-focused: solutions are written for coursework and experimentation, not for deployment.
- Lightweight review: code favors clarity over optimization; breaking changes are expected while learning.
- Secrets policy: no credentials, API keys, or private data should ever be committed; keep all config values as placeholders.

## Repository layout
- Assignment 1/: first set of lab programs.
- Expt 3/ through Expt 12/: follow-on experiments grouped per lab.
- self cloning C/: small self-replication exercise.

## Getting started
1) Install a C toolchain (GCC/Clang). On Windows, MinGW works well with the provided VS Code build task.
2) Open a source file in VS Code and run the default build task “C/C++: gcc.exe build active file”, or compile manually:

```bash
gcc -Wall -Wextra -pedantic -g expt1.c -o expt1.exe
```

3) Run the produced executable from the same directory.

## Development notes
- Use warning flags (`-Wall -Wextra -pedantic`) and `-g` while iterating; strip `-g` for release builds if needed.
- Keep binaries and editor artifacts out of version control; see the updated ignore rules.
- Add small comments only where logic is non-obvious; prefer self-explanatory code.

## Security and compliance
- This is an educational repository; do not reuse credentials or proprietary assets here.
- Run a secret scan (e.g., GitGuardian CLI) before pushing if you edit files that may touch tokens or environment values.
- Review diffs to ensure only source changes are committed; binaries, logs, and local settings should remain untracked.

## License
Code is available under the BSD 3-Clause License; see [LICENSE](LICENSE).
