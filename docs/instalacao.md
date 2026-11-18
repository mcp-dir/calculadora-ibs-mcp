# Instalação detalhada

Calculadora IBS é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_calculadora-ibs`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_calculadora-ibs` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_calculadora-ibs` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_calculadora-ibs` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.calculadoraibs` (ou `servers.calculadoraibs` no VS Code) do config do cliente e reinicie.
