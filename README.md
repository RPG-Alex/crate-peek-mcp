# Crate Peek MCP

Crate Peek MCP is an implementation of the [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) designed to make language models aware of the local Rust project context.

It scans the workspace for crates, generates structured documentation, and exposes this data to the LLM host through MCP tools for context-aware reasoning and code assistance.
