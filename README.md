# mcpfetch
A MCP server for fetching HTML or Markdown content from the web. Written in Xojo.

mcpfetch is a MCP server that allows a LLM to request the contents of a URL as Markdown.

I use this in conjunction with mcpkagi (https://github.com/gkjpettet/mcpkagi) which is a Kagi search engine MCP server to discover URLs my LLM might want to add to its context to answer a question.

It takes no command line arguments.

This is how I use it in my mcp.json file for LM Studio:

{
  "mcpServers": {
	"mcpfetch": {
		"command": "/Users/garry/mcpservers/mcpfetch/mcpfetch",
		"args" : []
	}
  }
}

