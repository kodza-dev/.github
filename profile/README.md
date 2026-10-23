# Kodza

Free UI components in plain HTML, CSS and vanilla JS. Zero dependencies. Your AI can fetch them.
One new one a day until 1,000.

The components live on **[kodza.dev](https://kodza.dev)**, not here.

## Use it from your editor

One address for every editor: `https://kodza.dev/api/mcp`. Hosted, nothing to install, no API key.

- **Claude Code**: `claude mcp add -t http kodza https://kodza.dev/api/mcp`
- **Claude app**: Customize → Connectors → Add custom connector, paste the address.
- **Codex**: `codex mcp add kodza --url https://kodza.dev/api/mcp`
- **Cursor**: the [plugin](https://github.com/kodza-dev/kodza-plugin), or the address in `.cursor/mcp.json`.
- **VS Code**: `code --add-mcp '{"name":"kodza","type":"http","url":"https://kodza.dev/api/mcp"}'`

Rather run it on your machine? `npx -y kodza-mcp`. Every detail: [kodza.dev/docs](https://kodza.dev/docs/#install).

Then ask in your own words: *"add a button that fills from the cursor"*. Your AI finds the
component and pastes the real code where it goes.

## What's here

- **[requests](https://github.com/kodza-dev/requests)**: ask for a component, vote for the ones
  you want. Bugs go there too.
- **[kodza-plugin](https://github.com/kodza-dev/kodza-plugin)**: the Cursor plugin. One file that
  points at the address above. Cursor's directory wants a repo, so here's a repo.

No source code on GitHub: copy it from kodza.dev, or let your AI fetch it. Free in any project,
client work included. Reselling it isn't. [License](https://kodza.dev/docs/#print-license).
