# Boomi Companion

A [Claude Code plugin](https://www.anthropic.com/news/claude-code-plugins) marketplace for discovering and installing Boomi development tools. This repository serves as the official registry of plugins built for the Boomi platform.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [bc-integration](https://github.com/OfficialBoomi/bc-integration) | Skills, commands, and agents for building Boomi integrations |

## Installation

### Add the Marketplace

In Claude Code, use the `/plugin` command to add this marketplace:

```
/plugin marketplace add OfficialBoomi/boomi-companion
```

This registers the marketplace so Claude Code can discover all available Boomi plugins. The marketplace can also be managed through the VS Code extension by typing `/plugins` in the prompt box and selecting the **Marketplaces** tab.  After registering the markplace, you will be able to browse available plugins and install them.
