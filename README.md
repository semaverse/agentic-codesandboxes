# AI-Agentic-REPL
Description and Utilization of Read Eval Print Loop (REPL) aka known as Code Sandboxes for Agentic Usecases

# Technology Map Agentic REPL


```mermaid
  graph LR

    subgraph Languages
      L1{Python}
      L2{Typscript}
    end

    subgraph Hosting
      D1[Selfhosted]
      D2[Cloud Service]
    end

    subgraph AI Technoligy
      AI1[MCP-SSE]
      AI2[MCP-STDIO]
    end

    subgraph Projects
      P1("Pydantic MCP Run Python")
      P1 --> L1
      P1 --> D1
      P1 --> AI1
  
      P2(E2b.dev)
      P2 --> L1
      P2 --> D2
      P2 --> |?| AI1
  
      P3(Daytona.io)
      P3 --> L1
      P3 --> L2
      P3 --> D2
      P3 --> |?| AI1
  
      P4(mcp-python)
      P4 --> L1
      P4 --> D2
      P4 --> AI2
  
      P5(Conda MCP Executor)
    end
   

```
## Listview

| Project | Link | In this Repo |
| --------| -----| ------------ | 
| Pydantic MCP Run Python | https://ai.pydantic.dev/mcp/run-python/ | [pydantic-mcp-python-run](python/pydantic-mcp-python-run/) |
| E2b.dev | https://e2b.dev/docs/quickstart |  |
| Daytona.io | https://www.daytona.io/ |  |
| mcp-python | https://github.com/hdresearch/mcp-python ||
| Conda MCP Executor | https://github.com/bazinga012/mcp_code_executor ||
