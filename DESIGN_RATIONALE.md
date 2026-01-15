# Design Rationale

ICL prioritizes:
- minimal token usage
- deterministic parsing
- human approval
- local execution

Unlike Git-style diffs:
- ICL does not depend on file context
- ICL avoids line-based ambiguity

Unlike MCP tools:
- ICL avoids JSON overhead
- ICL requires no tool registry
- ICL is executor-owned

ICL is optimized for cost-sensitive, local, secure AI agents.
