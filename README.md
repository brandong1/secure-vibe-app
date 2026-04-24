# Secure Vibe Coding with Semgrep

An animated Flask landing page in the Semgrep colorway.

## Features

- Flowing gradient text animations in Semgrep orange/amber
- Pulsing glow effect on the headline
- 60 floating particle sparks
- Scanline shimmer overlay
- Responsive layout

## Requirements

- Python 3.11+
- [uv](https://github.com/astral-sh/uv)

## Setup

```bash
# Install dependencies
uv sync --no-install-project

# Run the app
uv run flask run --port 5001
```

Then open `http://127.0.0.1:5001` in your browser.

## Configuration

| Environment Variable | Default | Description |
|---|---|---|
| `FLASK_DEBUG` | `false` | Set to `true` to enable debug mode (development only) |

## Security

Debug mode is off by default and must be explicitly enabled via the `FLASK_DEBUG` environment variable — it is never hardcoded. This prevents stack traces and environment details from leaking in production.
