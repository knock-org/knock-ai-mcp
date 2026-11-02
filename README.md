# Knock AI MCP

Connect your AI assistant to your [Knock](https://knock-ai.com) workspace. Ask about your chats with leads and read their messages, see the meetings booked with them, and explore your accounts and contacts with their activity: filtered, counted and broken down the way your Knock dashboard shows them.

This repository is a plugin that points your assistant at Knock's hosted MCP server. There is nothing to install or run:

```
https://app.knock-ai.com/mcp
```

## Connect

**Claude Code**

```bash
claude mcp add --transport http knock-ai https://app.knock-ai.com/mcp
```

Then run `/mcp`, select `knock-ai` and sign in.

**Claude (claude.ai and Claude Desktop)**

Settings › Connectors › Add custom connector, and paste `https://app.knock-ai.com/mcp`.

**Other MCP clients**

Add `https://app.knock-ai.com/mcp` as a remote (HTTP) MCP server. Your client opens Knock's sign-in page the first time you use it.

## Sign in and permissions

The first time you connect, you sign in with your Knock account, choose the workspace, and approve the connection. The assistant then sees only what your role in that workspace can see. You can disconnect at any time.

## What you can ask

- "Which leads with buying intent chatted with us this week?"
- "How many meetings were booked this month, by booking source?"
- "Show me my latest chat with jane@acme.com."
- "Which accounts were most active in the last 30 days?"

## Privacy

What the tools return (lead names, messages, meetings and account activity) is sent to your AI assistant's provider, under that provider's terms. Messages are written by your leads, so treat their content as untrusted text.

## Support

Questions or problems: reach out to your Knock contact or visit [knock-ai.com](https://knock-ai.com).
