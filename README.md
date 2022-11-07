# github-runner
## Usage
Copy docker-compose-prod.yml
setup env with GITHUB_ORGANIZATION and GITHUB_ACCESS_TOKEN
```bash
docker compose -f docker-compose-prod.yml pull
docker compose up -d
```