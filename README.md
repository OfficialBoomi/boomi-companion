# Boomi Companion

A [Claude Code plugin](https://www.anthropic.com/news/claude-code-plugins) marketplace for discovering and installing Boomi development tools. This repository serves as the official registry of plugins built for the Boomi platform.

> **Important:** Boomi Companion is a publicly available developer offering, not an officially supported Boomi product. It is provided as-is and is not covered by Boomi support agreements or SLAs. Boomi curates and maintains this tool on a best-effort basis — treat it as a self-service resource. Boomi reserves the right to modify or discontinue it at any time without notice.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [bc-integration](https://github.com/OfficialBoomi/bc-integration) | Skills, commands, and agents for building Boomi integrations |
| [bc-marketplace](https://github.com/OfficialBoomi/bc-marketplace) | Skill for searching and installing Boomi Marketplace recipes |

## Installation

### Add the Marketplace

In Claude Code, use the `/plugin` command to add this marketplace:

```
/plugin marketplace add OfficialBoomi/boomi-companion
```

This registers the marketplace so Claude Code can discover all available Boomi plugins. The marketplace can also be managed through the VS Code extension by typing `/plugins` in the prompt box and selecting the **Marketplaces** tab.  After registering the markplace, you will be able to browse available plugins and install them.

## Feedback & Issues
Found a bug or have a feature idea? Email solutions@boomi.com with a clear description, steps to reproduce, and any relevant error messages.
