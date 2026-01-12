# Aurora Code

![](https://img.shields.io/badge/Node.js-18%2B-brightgreen?style=flat-square)
[![npm]](https://www.npmjs.com/package/aurora-code)

[npm]: https://img.shields.io/npm/v/aurora-code.svg?style=flat-square

Aurora Code is an agentic coding companion that runs in your terminal. It understands your entire codebase, executes multi-step development tasks, and helps you build faster using natural language commands.

Aurora goes beyond traditional coding assistants by reasoning across files, managing workflows, and handling real development tasks end-to-end.

---

## Features

- Deep understanding of large, multi-file codebases
- Natural language commands for common dev tasks
- Automated refactors, explanations, and fixes
- Git-aware workflows (commits, branches, PR prep)
- Extensible plugin and agent system
- Works in terminal, IDEs, and GitHub

---

## Requirements

- Node.js 18+
- macOS, Linux, or Windows

---

## Installation

### macOS / Linux

```bash
curl -fsSL https://aurora.dev/install.sh | bash

Homebrew (macOS)
brew install --cask aurora-code

Windows
irm https://aurora.dev/install.ps1 | iex

NPM
npm install -g aurora-code


If installing via NPM, make sure Node.js 18+ is installed.

Usage

Navigate to your project directory and start Aurora:

aurora


Aurora will analyze your repository and begin assisting immediately.

Example commands:

explain this file
refactor this module
find bugs in the auth flow
prepare a commit for these changes

Plugins

Aurora Code supports plugins to extend functionality with custom commands and agents.

Plugins can be used to:

Add project-specific workflows

Automate repetitive tasks

Integrate internal tooling

Create specialized agents

See plugins/README.md for more details.

Bug Reports & Feedback

You can report issues in two ways:

Use the /bug command inside Aurora Code

Open a GitHub issue:
https://github.com/aurora-dev/aurora-code/issues

Community

Discord: https://aurora.dev/discord

Share plugins, workflows, and feedback with other developers.

Data Usage & Privacy

Aurora Code may collect limited usage data to improve reliability and user experience. This may include:

Anonymous usage signals (e.g. accepted or rejected suggestions)

Minimal session context for debugging

Feedback submitted via the /bug command

Aurora does not train models on your private code.

See:

https://aurora.dev/docs/data-usage

https://aurora.dev/legal/privacy

https://aurora.dev/legal/terms

License

MIT License © Aurora
