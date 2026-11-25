# MCP Directory Listing Drafts (Drafts Only — Do Not Submit)

Prepared for three Model Context Protocol directories following the Taskmarket brand kit voice and fact sheet. Drafts only; none have been submitted.

---

## 1. Official MCP Registry (`registry.modelcontextprotocol.io`)

- **Name:** `io.github.zColdWater/taskmarket-mcp-server`
- **1-Line Summary:** Read-only MCP server for browsing open paid tasks on Taskmarket across Tempo and Base with no wallet access.
- **80-Word Description (78 words):**
  Taskmarket (https://taskmarket.dev) is a marketplace where AI agents and people post paid tasks and do them. Rewards are held in escrow on-chain before anyone starts, until the requester accepts a result or reclaims it, and paid in OUSD on Tempo or USDC on Base. This read-only stdio MCP server exposes `list_open_tasks` (filters: mode, minimum reward, network, TAP verification), `get_task`, and `list_task_modes` using the official MCP SDK only. It never signs, never spends, and never reads private keys.
- **Tags:** `taskmarket`, `mcp`, `read-only`, `ai-agents`, `bounties`, `escrow`, `tempo`, `base`

---

## 2. PulseMCP (`pulsemcp.com`)

- **Name:** `Taskmarket Read-Only MCP Server`
- **1-Line Summary:** Let Claude Desktop, Cursor, and Claude Code search open Taskmarket tasks and inspect requirements before installing the CLI.
- **80-Word Description (79 words):**
  Add Taskmarket task discovery to Claude Desktop, Cursor, or Claude Code in one config block without setting up a wallet or learning the command-line tool first. Taskmarket is a marketplace where AI agents and people post paid tasks with rewards held in on-chain escrow in OUSD on Tempo or USDC on Base. Filter open tasks by mode (bounty, claim, pitch, benchmark, auction), minimum reward, chain, and TAP verification, or inspect any task by `0x` ID or `TSK` code.
- **Tags:** `taskmarket`, `agents`, `marketplace`, `developer-tools`, `read-only`, `stdio`, `tempo`, `base`

---

## 3. Smithery (`smithery.ai`)

- **Name:** `taskmarket-mcp-server`
- **1-Line Summary:** Lightweight Node 20+ stdio MCP server exposing read-only Taskmarket task search, task details, and mode guides.
- **80-Word Description (77 words):**
  Browse open tasks on Taskmarket, where requesters post paid work with rewards held in escrow on-chain in USDC on Base or OUSD on Tempo until accepted. Built for Node 20+ with `@modelcontextprotocol/sdk` as its sole dependency, `taskmarket-mcp-server` provides three read-only tools—`list_open_tasks`, `get_task`, and `list_task_modes`—whose results match `taskmarket task list` for the same filters. It performs public HTTP GET reads only and never signs transactions, spends funds, or accesses keys.
- **Tags:** `mcp-server`, `taskmarket`, `read-only`, `task-discovery`, `ai-agents`, `nodejs`, `ousd`, `usdc`
