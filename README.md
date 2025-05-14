# `smolagents` MCP Integration

This repository showcases the integration of `smolagents` with Model Context Protocol (MCP) tools to build powerful agentic systems. The project demonstrates how to create intelligent agents that can utilize various specialized tools through the MCP standard.

## Overview

`smolagents` is a framework for building lightweight AI agents that can leverage a range of tools and capabilities. This repository focuses specifically on how `smolagents` can be integrated with MCP (Model Context Protocol) tools to create agents that can:

- Search and retrieve information from different sources
- Process specialized data (financial, scientific, etc.)
- Make decisions based on up-to-date information
- Present information in a structured format

## Getting Started

### Prerequisites

- Python 3.9+
- Pip package manager

### Installation

1. Clone this repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Set up necessary API keys in a `.env` file:
   ```
   OPENAI_API_KEY=your_openai_key
   BRAVE_API_KEY=your_brave_key
   TAVILY_API_KEY=your_tavily_key
   ```

## Notebooks

### test_mcp.ipynb

This introductory notebook demonstrates the core concepts of using MCP tools with `smolagents`. It covers:

1. **Setting up MCP servers** - Configuring servers for different tools like Brave Search, PubMed, Tavily, arXiv, and Yahoo Finance
2. **Loading tools from MCP servers** - Connecting to these servers and making their tools available to agents
3. **Creating agents** - Building agents that can use the MCP tools to solve tasks
4. **Example use cases**:
   - Using Brave Search to find information about current events
   - Analyzing stock price trends with Yahoo Finance
   - Searching and retrieving scientific papers from PubMed

The notebook serves as a practical introduction to how these systems can be combined to create powerful AI assistants with access to specialized knowledge and capabilities.

## Key Components

- **`smolagents`**: Provides the agent framework
- **MCP Servers**: Enable access to specialized tools
- **LiteLLM**: Manages interaction with language models
- **Tool Collections**: Organize available tools for the agent to use

## Use Cases

The integration demonstrated in this repository is useful for:

- Research assistants that can find and summarize papers
- Financial analysis assistants
- News and information gathering
- Question answering with specialized domain knowledge

## License

[Specify your license here]

## Acknowledgments

- The `smolagents` team
- Contributors to the MCP standard
- Developers of the various tool integrations 