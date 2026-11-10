# TrueReturn for Claude Code and Cursor

Rewrite drafts so they sound like you. Adds three commands and connects the
[TrueReturn](https://checktruereturn.com) MCP server.

| Command | What it does |
|---|---|
| `/rewrite <text>` | Rewrites a draft in your voice, keeping names, numbers and dates |
| `/train <text>` | Adds writing you wrote yourself so rewrites sound like you |
| `/voice` | Describes how you write |

## Claude Code

```
/plugin marketplace add truereturnhq/truereturn-plugin
/plugin install truereturn@truereturn
```

Then run `/mcp` and sign in to TrueReturn.

## Cursor

Install from the Cursor plugin marketplace, or add the MCP server from
https://checktruereturn.com/developers.

Docs: https://checktruereturn.com/developers
