# Docker YAML

This repository contains Docker Compose YAML files for running lightweight services locally.

- `n8n.yaml` 
Docker Compose configuration for running n8n (workflow automation).

- `webui_openai.yaml` 
Docker Compose configuration for a simple web UI that connects to OpenAI.


Quick start:
1. Start n8n:
```bash
docker compose -f n8n.yaml up -d
```

2. Start the web UI:
```bash
docker compose -f webui_openai.yaml up -V
```

Feel free to modify or improve the compose files with your environment-specific settings.