# crate-peek-server
MCP server component of the [crate-peek MCP](https://github.com/rpg-alex/crate_peek_mcp) project.

## Overview
This crate implements the Model Context Protocol (MCP) server that powers the `crate-peek` ecosystem.  
It exposes the `crate-peek-core` functionality through an MCP-compatible API, enabling LLMs or external clients to inspect Rust workspaces and retrieve dependency crate documentation generated from within the repo.

## Features
- TODO: Fill out

## Usage
This crate is designed to be run as an MCP server within the workspace.  
Example launch (from workspace root):

```bash
cargo run -p crate-peek-server
```

## License
[MIT © 2025 Alex Blood](../../LICENSE)