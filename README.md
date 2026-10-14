# Ranla plugin for Claude Code

Ranla is an AI growth engineer for software businesses. It writes and ships pages that rank on Google, gets your product named in AI answers, replies on Reddit, and sends the emails that turn sign-ups into customers. This plugin connects Claude Code to your Ranla workspace.

## Install

```bash
claude plugin marketplace add Super-Send/ranla-claude-plugin
claude plugin install ranla@ranla
```

The first time Claude uses a Ranla tool, you sign in through your browser. There is no API key to copy. Create a workspace at [ranla.ai](https://ranla.ai) if you don't have one.

## What's inside

- **Ranla's hosted MCP server** (`https://mcp.ranla.ai/mcp`): talk to Ranla, see growth health, campaigns, audiences and conversations, and approve or reject what Ranla wants to send, spend or publish.
- **`ranla-mcp` skill:** how Claude works with Ranla through the MCP tools.
- **`ranla-cli` skill:** drive Ranla from the terminal with `ranla-cli` (browser sign-in, Ranla's commands, approvals).
- **`ranla` skill:** wire your product's sign-ups, activation and payment events into Ranla, and send transactional email when you need it.

## Try

```text
How is growth going this week?
Ask Ranla to draft an email for people who signed up but never activated.
What is waiting on my approval in Ranla?
Connect this app to Ranla: upsert contacts at sign-up and send the activation event.
```

Nothing is sent, spent or published until you approve it.

## Develop

Validate a checkout with:

```bash
npx @anthropic-ai/claude-code plugin validate --strict .
```

Questions or problems: contact@ranla.ai.
