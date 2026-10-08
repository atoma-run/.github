<div align="center">

<img src="https://atoma.run/favicon.svg" width="72" height="72" alt="Atoma">

# Atoma

**Watch a request turn into finished work.**

Ask for a drawing, a sound, a report, a data study, a proof or a piece of
software. Atoma coordinates AI agents to produce it, checks the result against
what you asked for, and lets you inspect every step.

[Open atoma.run](https://atoma.run) · [Source](https://github.com/atoma-run/atoma) · [Self-host](https://github.com/atoma-run/atoma#install-and-evaluate-it-locally) · [Documentation](https://github.com/atoma-run/atoma#documentation)

</div>

## Repositories

- **[atoma](https://github.com/atoma-run/atoma)**: the platform. It covers
  planning, agent orchestration and verification, the console at atoma.run and
  its MCP server. TypeScript, licensed AGPL-3.0.

## Drive it from your own agent

Atoma serves one MCP endpoint at `https://atoma.run/mcp`. To connect Claude
Code:

```bash
claude mcp add --transport http --scope user atoma https://atoma.run/mcp
```

Then run `/mcp` to sign in. Other MCP clients use the same URL.

## Status

Atoma is under active development and has not been independently audited. Do
not send confidential or personal data. Report vulnerabilities privately as
described in [SECURITY.md](https://github.com/atoma-run/atoma/blob/main/SECURITY.md).
