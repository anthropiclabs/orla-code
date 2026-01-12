# Aurora Code ![](https://img.shields.io/badge/Node.js-18%2B-brightgreen?style=flat-square) [![npm]](https://www.npmjs.com/package/@anthropic-ai/aurora-code)

[npm]: <img width="1376" height="768" alt="aurora2" src="https://github.com/user-attachments/assets/b4564347-d80c-4909-b9c2-fa2411e2f5d3" />

Aurora Code is your brilliant new agentic coding companion that lives in your terminal, deeply understands your codebase, and supercharges your development workflow — executing routine tasks, explaining complex code, and handling git workflows with unmatched precision, all through natural language commands.

Use it in your terminal, IDE, or tag @aurora on Github.

**Learn more in the [official documentation](https://code.aurora.ai/docs/en/overview)**.

<img src="./demo.gif" />

## Get started

1. Install Aurora Code:

**MacOS/Linux:**

```bash
curl -fsSL https://aurora.ai/install.sh | bash
```

**Homebrew (MacOS):**

```bash
brew install --cask aurora-code
```

**Windows:**

```powershell
irm https://aurora.ai/install.ps1 | iex
```

**NPM:**

```bash
npm install -g @anthropic-ai/aurora-code
```

NOTE: If installing with NPM, you also need to install [Node.js 18+](https://nodejs.org/en/download/)

2. Navigate to your project directory and run `aurora`.

## Plugins

This repository includes several Aurora Code plugins that extend functionality with custom commands and agents. See the [plugins directory](./plugins/README.md) for detailed documentation on available plugins.

## Reporting Bugs

We welcome your feedback. Use the `/bug` command to report issues directly within Aurora Code, or file a [GitHub issue](https://github.com/anthropics/aurora-code/issues).

## Connect on Discord

Join the [Aurora Developers Discord](https://aurora.ai/discord) to connect with other developers using Aurora Code. Get help, share feedback, and discuss your projects with the community.

## Data collection, usage, and retention

When you use Aurora Code, we collect feedback, which includes usage data (such as code acceptance or rejections), associated conversation data, and user feedback submitted via the `/bug` command.

### How we use your data

See our [data usage policies](https://code.aurora.ai/docs/en/data-usage).

### Privacy safeguards

We have implemented several safeguards to protect your data, including limited retention periods for sensitive information, restricted access to user session data, and clear policies against using feedback for model training.

For full details, please review our [Commercial Terms of Service](https://www.aurora.ai/legal/commercial-terms) and [Privacy Policy](https://www.aurora.ai/legal/privacy).

