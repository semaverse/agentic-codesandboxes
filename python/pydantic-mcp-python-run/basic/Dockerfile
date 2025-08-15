FROM denoland/deno:2.4.4

# The port that your application listens to.
EXPOSE 3001

#Install MCP
RUN deno install jsr:@pydantic/mcp-run-python


CMD ["run", "-N", "-R=node_modules", "-W=node_modules", "--node-modules-dir=auto", "jsr:@pydantic/mcp-run-python", "sse"]
