# video
- https://www.youtube.com/watch?v=Iv7DZdn8phg
# docker-compose-n8n-traefik

## Key features

- Docker Compose
- PostgreSQL
- Traefik

## Setup

```
-- file gốc : git clone https://github.com/woakes070048/n8n-docker
git clone https://github.com/DNV-CODE/n8n.git
cd n8n-docker
cp .env.example .env
# edit .env
mkdir /root/n8n/
docker-compose up -d && docker-compose logs -f
```

This is based on [n8n Official docker-compose.yml](https://github.com/n8n-io/n8n/tree/master/docker/compose/withPostgres).
