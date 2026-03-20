# Nic's Claude Code Plugins

A curated marketplace of Claude Code plugins for developer productivity and AI-powered workflows.

## Install

Add this marketplace to Claude Code:

```
/plugin marketplace add YOUR_USERNAME/claude-plugins-marketplace
```

Then browse and install plugins:

```
/plugin install claude-focus@nic-claude-plugins
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **[claude-focus](https://github.com/YOUR_USERNAME/claude-focus)** | Auto-focuses VS Code when Claude Code needs input, finishes a task, or hits an error |

## Adding Plugins

As new plugins are added, update `.claude-plugin/marketplace.json` and users can refresh with:

```
/plugin marketplace update
```

## For Teams

Auto-install this marketplace for your team by adding to your project's `.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": {
    "nic-claude-plugins": {
      "source": {
        "source": "github",
        "repo": "YOUR_USERNAME/claude-plugins-marketplace"
      }
    }
  }
}
```

## License

MIT
