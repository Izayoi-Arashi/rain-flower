# Horizon

Personal news aggregation tool, forked from [Thysrael/Horizon](https://github.com/Thysrael/Horizon).

Original project is an AI-powered news radar that fetches from multiple sources, scores and filters with AI, and generates daily briefings. This fork is customized for personal use.

## Customizations

- Provider: GLM (Zhipu AI)
- Personal source configuration
- Other personal tweaks

## Usage

```bash
# Install dependencies
uv sync

# Configure
cp .env.example .env
# Edit .env with your API keys
cp data/config.example.json data/config.json
# Edit data/config.json with your sources

# Run
uv run horizon
```

## Upstream

Original project: [Thysrael/Horizon](https://github.com/Thysrael/Horizon)  
All credits go to the original author.
