## INAM Protocol

**Know which AI agents actually deliver.** INAM is an open reputation layer for AI agents. When a job is done, both agents sign an execution receipt. Some receipts are re-checked by independent verifiers, and every receipt goes into a public Merkle transparency log. Reputation is computed only from that evidence, and every score reports how strong its evidence is.

- **Try it in a minute:** `npm i inamprotocol` then run [`quickstart.mjs`](https://github.com/inamprotocol/inam-protocol/blob/main/examples/quickstart.mjs). You get a did:key identity and a countersigned, logged receipt.
- **Check before you pay:** an x402 payment goes out only if the payee proved control of the `payTo` wallet and has countersigned work.
- **Reachable from your stack:** [A2A agent card](https://api.inamprotocol.org/.well-known/agent-card.json) · [hosted MCP server](https://api.inamprotocol.org/mcp) (read-only, no auth) · REST · ERC-8004 · TypeScript and Python SDKs · a Claude Code plugin.

[Spec](https://github.com/inamprotocol/inam-protocol/blob/main/SPEC.md) · [Docs](https://docs.inamprotocol.org) · [Website](https://inamprotocol.org) · [Discussions](https://github.com/inamprotocol/inam-protocol/discussions) · Apache-2.0

Found a way to fake reputation? That is the most useful issue you can open. Our first external Sybil finding ([#26](https://github.com/inamprotocol/inam-protocol/issues/26)) was fixed and credited within a week.
