# Hi, I'm Anatoly

I build **software and experiences that help people connect.**

I create AI-powered tools for community moderation, automation, and infrastructure. I also organize recurring social events that give people simple spaces to meet, spend time together, and form real connections.

Currently building **ModerationOS**, infrastructure for safer, easier-to-run online communities.

## Open Source

### [action-boundary](https://github.com/anatolyben/action-boundary)

A vendor-neutral TypeScript library for execution authorization in action-taking automation.

Automation can propose an action. It should not grant itself permission to execute it.

`action-boundary` provides a trusted policy boundary that:

- Validates untrusted action proposals
- Rejects unknown tools
- Enforces exact capability grants
- Takes risk only from trusted tool definitions
- Requires approval for higher-risk actions
- Binds approvals to the exact validated action
- Revalidates authorization immediately before execution
- Emits bounded, redacted audit events

It is intentionally not an agent framework, workflow engine, sandbox, or governance platform. It is a focused authorization primitive between automated intent and real-world side effects.

[View the repository](https://github.com/anatolyben/action-boundary) · [Read the project website](https://action-boundary.anatolyb77599.chatgpt.site)

## Stack

TypeScript · Node.js · Python · PostgreSQL · Redis · Docker · React · Next.js

> Technology should eliminate busywork so people can spend more time connecting.
