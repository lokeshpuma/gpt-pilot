# GPT Pilot

Autonomous AI platform that builds complete production-ready applications. Orchestrates specialized agents for architecture, development, testing, and deployment.

## Features

- **Autonomous Development**: AI agents handle architecture, development, testing, debugging, and deployment
- **Production-Ready Code**: Generates fully working applications, not just snippets
- **Developer Oversight**: Works with developers to ensure quality and address issues
- **Scalable**: Handles projects of any size efficiently
- **Multiple LLM Support**: Works with OpenAI, Anthropic, and Groq

## Quick Start

### Requirements
- Python 3.9+
- API key for LLM provider (OpenAI, Anthropic, or Groq)

### Installation

```bash
git clone https://github.com/Pythagora-io/gpt-pilot.git
cd gpt-pilot
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
cp example-config.json config.json
```

### Configuration

Edit `config.json` and add:
- Your LLM provider API key
- Database settings (SQLite is default, PostgreSQL supported)
- Other preferences

### Run

```bash
python main.py
```

## CLI Commands

```bash
python main.py --list              # List all projects
python main.py --project <id>      # Continue a project
python main.py --delete <id>       # Delete a project
python main.py --help              # See all options
```

## How It Works

GPT Pilot orchestrates multiple AI agents that work together:
1. Specification Writer - Clarifies requirements
2. Architect - Designs technology stack
3. Tech Lead - Creates development tasks
4. Developer - Plans implementation
5. Code Monkey - Implements changes
6. Reviewer - Quality assurance
7. Debugger - Fixes issues
8. Technical Writer - Documentation

## Contributing

We welcome contributions! Join our [Discord community](https://discord.gg/HaqXugmxr9) or check out [open issues](https://github.com/Pythagora-io/gpt-pilot/issues).

## Resources

- [Blog](https://blog.pythagora.ai)
- [Discord](https://discord.gg/HaqXugmxr9)
- [VS Code Extension](https://marketplace.visualstudio.com)

## License

FSL-1.1-MIT
