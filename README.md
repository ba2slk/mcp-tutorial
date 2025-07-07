# MCP-Tutorial: Fetching Weather Information from NWS
This tutorial is based on the official documentation from [Model Context Protocol](https://modelcontextprotocol.io/introduction)

## Install Dependencies
```
$ uv add  mcp anthropic python-dotenv httpx
```

## Run MCP-Client
```
$ uv run client.py ../server/server.py
```
Client runs the server subprocess by itself.

## Type a query
```
Query: What are the weather alerts in California?
```

## Quit
```
Query: quit
```
