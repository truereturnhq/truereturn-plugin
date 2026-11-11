# TrueReturn for Claude Code and Cursor

Rewrite drafts so they sound like you. Adds three commands and connects the
[TrueReturn](https://checktruereturn.com) MCP server.

| Command | What it does |
|---|---|
| `/rewrite <text>` | Rewrites a draft in your voice, keeping names, numbers and dates |
| `/train <text>` | Adds writing you wrote yourself so rewrites sound like you |
| `/voice` | Describes how you write |
| `/like <who> <text>` | Rewrites a draft so it sounds like someone you name |
| `/voices` | Lists the voices you can rewrite in |
| `/history` | Shows your recent rewrites |
| `/edit <text>` | Saves the version you sent so your voice learns from it |
| `/account` | Shows your plan and usage |

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
