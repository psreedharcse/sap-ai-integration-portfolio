# Tool Orchestration Flow

The system uses MCP to dynamically orchestrate tools based on user intent.

## Steps

1. LLM identifies required operations from user query
2. Agent maps operations to available tools
3. MCP enables dynamic tool invocation
4. n8n executes workflow sequences
5. Multiple tools can be executed sequentially or in parallel
6. Results are aggregated and returned

## Key Characteristics

* No hardcoded workflow
* Dynamic decision-making
* Multi-system integration
* Scalable orchestration
