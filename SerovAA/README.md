# Password Generator - Microservices Demo

## Architecture
- **Nginx**: Reverse proxy and static frontend server
- **Frontend**: HTML/JS UI served by Nginx
- **Backend (Flask)**: API endpoint for generating password tasks
- **Worker (Python)**: Long-running password generation service
- **Redis**: Task queue and result storage

## Run
```bash
docker compose up -d
