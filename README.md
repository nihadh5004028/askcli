# askcli

Minimal LLM CLI: stdin in, streamed answer out

## Installation

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=sk-...
```

## Highlights

- Reads the prompt from args or stdin
- Model and system prompt via flags or env
- Works with any OpenAI-compatible endpoint
- Streams tokens as they arrive

## How to use

```bash
chatsh explain this error < error.log
cat diff.patch | chatsh review this diff
```

## Project structure

```text
├── docs/
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
├── LICENSE
├── chatsh.py
└── requirements.txt
```

## License

MIT. Do whatever you want.
