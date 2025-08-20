# Utilization of Pydantic MCP Server 
[Pydantic MCP Server](https://ai.pydantic.dev/mcp/run-python/) enables Python Code Execution by using [Pyodide](https://pyodide.org/en/stable/)
see  for details. Github Files at https://github.com/pydantic/pydantic-ai/tree/main/mcp-run-python
## Basic Dockerfile wit SSE enabled

[Dockerfile](basic/Dockerfile) provides a simplified Dockerfile for only spinning up an MCP Server for Python Code Execution based on https://deno.com/

### Insights
1. As it is the nature Server Send Events (SSE) to be statefull it is not possible to go beyond more than 1 Replica in a kubernetes setup. 
