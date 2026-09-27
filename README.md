[![M8ven Score](https://m8ven.ai/badge/mcp/anushka2670/test-remote-mcp-server)](https://m8ven.ai/mcp/anushka2670/test-remote-mcp-server)


A lightweight *Model Context Protocol (MCP) server* for managing personal expenses through AI assistants and MCP-compatible clients.

The server provides tools to add, retrieve, summarize, and delete expense records stored in a local SQLite database. It also exposes expense categories as an MCP resource.

## 🚀 Features

- Add new expense records
- Retrieve expenses within a date range
- Summarize expenses by category
- Filter expense summaries by category
- Delete an expense using its ID
- Expose expense categories through an MCP resource
- Persistent local storage using SQLite
- HTTP-based MCP transport
- Built with FastMCP and Python
- Simple and lightweight architecture

## 🧠 What is MCP?

*Model Context Protocol (MCP)* is a standard that allows AI applications to interact with external tools, resources, and data sources.

This project demonstrates how an MCP server can provide an AI assistant with controlled access to an expense-management system.

Instead of manually interacting with a database, an MCP-compatible AI client can invoke tools such as:

Add an expense
        ↓
MCP Client
        ↓
Expense Tracker MCP Server
        ↓
SQLite Database
