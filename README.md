# mcp-snippetbox

MCP server template I base new tools on

## How to use

```bash
# claude_desktop_config.json
# {
#   "mcpServers": {
#     "notes-box": {"command": "python", "args": ["server.py"]}
#   }
# }
python server.py
```

## What it does

- State persisted to a JSON file in the home dir
- FastMCP style: decorators, zero boilerplate
- Three tools: add / get / list notes
- Includes Claude Desktop config snippet

## Getting started

```bash
pip install -r requirements.txt
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── requirements.txt
└── server.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m pytest -q
```

## Known issues

- none reported yet (surprisingly)

## License

MIT - see [LICENSE](LICENSE).
