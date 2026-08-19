# Instalação detalhada

Receita Federal: NFE é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_receita_federal_nfe`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_receita_federal_nfe` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_receita_federal_nfe` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_receita_federal_nfe` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.receita_federal_nfe` (ou `servers.receita_federal_nfe` no VS Code) do config do cliente e reinicie.
