# Veracium

Veracium builds provenance-aware tools for AI agents.

## Veracium Memory

Long-term, per-user memory for AI agents that records **who said what**. A fact your user told the agent and a
claim the agent only read in an email are stored differently, so the claim never silently becomes a fact about
the user. When memory holds no grounding for an answer, an abstention gate says "I don't know" instead of guessing.

- 📦 **Install:** `pip install veracium` · [PyPI](https://pypi.org/project/veracium/)
- 🔧 **Code:** [veracium-ai/Veracium](https://github.com/veracium-ai/Veracium) · **Docs:** [docs.veracium.ai](https://docs.veracium.ai)
- 🔌 **MCP server included** (`veracium-mcp`), so MCP clients such as Claude Desktop and Claude Code can use it
  without code
- ⚖️ **Limits:** labels record where a memory came from, not whether the source is telling the truth. They're only
  as good as your integration's account of who wrote each message. Memory does not detect or block prompt
  injection.
- 🤝 **Contributing:** [good first issues](https://github.com/veracium-ai/Veracium/issues?q=is%3Aissue+is%3Aopen+label%3Agood-first-issue) · [CONTRIBUTING.md](https://github.com/veracium-ai/Veracium/blob/main/CONTRIBUTING.md)
- 🔒 **Security:** memory poisoning is a vulnerability, not a quality bug. [Report it privately](https://github.com/veracium-ai/Veracium/security/policy).

[veracium.ai](https://veracium.ai) · MIT-licensed
