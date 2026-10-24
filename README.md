# Podshare

**Group work, rebuilt for AI.**

[Podshare](https://podshare.ai) is where your team builds web pages and small apps together. A landing page, a pricing page, a class project, a client proposal, a feedback form: one person starts it, and everyone else picks it up from there. Each person works from the AI app they already use, in a shared pod, with comments, history, and nothing public until a person makes it live.

This repository is Podshare's plugin for **Claude Code** and **Cursor**. It connects Podshare's MCP server and adds a skill on how to work in a pod.

## Install

**Claude Code**

```
/plugin marketplace add cafe-software/podshare-plugin
/plugin install podshare@podshare
```

**Cursor:** install Podshare from the Cursor marketplace.

**Any other app:** add `https://mcp.podshare.ai/mcp` as a custom connector. See [podshare.ai/docs](https://podshare.ai/docs) for the steps in each app.

The first time you use it, you sign in to Podshare. Personal pods are free.

## What you can ask

- "What pods do I have in Podshare, and what changed since I last looked?"
- "Add a short FAQ section to the end of the welcome artifact."
- "Take care of the open comments on pricing and tell me what you changed."
- "Save a version of release-notes, then make it live."
- "What has been sent through the feedback form?"

## What is in it

| Path | For |
|---|---|
| `.claude-plugin/plugin.json`, `.claude-plugin/marketplace.json` | Claude Code |
| `.mcp.json` | Claude Code: the MCP server |
| `.cursor-plugin/plugin.json`, `mcp.json` | Cursor: the plugin and the MCP server |
| `skills/podshare/SKILL.md` | Both: how to work in a pod |
| `rules/podshare.mdc` | Cursor: the same, as a rule |

## Support and policies

- Documentation: https://podshare.ai/docs
- Support: https://podshare.ai/support, or support@podshare.ai
- Privacy: https://podshare.ai/privacy
- Terms: https://podshare.ai/terms

Made by Cafe Software LLC.
