# BugOtter

![BugOtter](assets/logo.png)

Packaging only. This public repository is the Cursor Marketplace, LobeHub, and awesome-mcp listing for BugOtter. It does not contain the BugOtter application.

Monitoring for indie shippers: uptime, analytics, revenue, and errors in one calm list — your coding agent can fix what breaks.

This plugin is a connector. It points Cursor at BugOtter’s hosted MCP server.

- MCP URL: https://bugotter.com/api/mcp (Streamable HTTP)
- Docs: https://bugotter.com/docs/mcp
- Privacy: https://bugotter.com/privacy
- Terms: https://bugotter.com/terms
- Support: hello@bugotter.com

## Install

Install this plugin from the Cursor Marketplace (once listed), or add the server by URL in Cursor as described at https://bugotter.com/docs/mcp.

The first time Cursor connects, sign in to BugOtter when prompted (OAuth). The connection is read-only unless you also allow changes on the consent screen. You can limit it to some apps.

A BugOtter account is required. Every plan includes MCP. A 14-day free trial of everything is available with no card. This plugin is free; BugOtter’s product plans are billed by BugOtter, not through the Cursor Marketplace.

Optional: instead of OAuth, create an agent token under Settings → Agent access and send it as `Authorization: Bearer bo_…`. You do not need a token for the usual sign-in path.

## What it can do

Read issues, errors, uptime, traffic, revenue, deploys, setup, plan and usage, alerts, connections, the status page, and more. With write permission: resolve or snooze issues, post status updates, add checks, and similar changes. Secrets never come back over MCP.

Try: “Which of my apps need attention today?”
