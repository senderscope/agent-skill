# Reverse email lookup by Senderscope

Reverse email lookup, email finder and email verifier as an agent skill. `SKILL.md` teaches an agent to use
Senderscope's MCP server (`https://senderscope.app/mcp`) or REST API (`https://senderscope.app/v1`): see who
owns a work email (the professional profile behind it), find a work email from a name and company or a
LinkedIn profile, and run email verification to check whether an address is deliverable.

```sh
npx skills add senderscope/agent-skill
```

Connect the MCP server separately: add `https://senderscope.app/mcp` in a remote MCP client, or run
`npx -y senderscope-mcp` for a stdio client with Node.js 22+.

[Website](https://senderscope.app) · [MCP repository](https://github.com/senderscope/mcp-server)
