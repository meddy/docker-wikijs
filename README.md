# docker-wikijs
A Docker Compose configuration for running a Wiki.js instance on a VPS such as
a Digital Ocean droplet. Includes nginx as a reverse proxy for HTTPS support.
Based on https://docs.requarks.io/en/install/docker

## Required Environment Variables
- `POSTGRES_DB`
- `POSTGRES_PASSWORD`
- `POSTGRES_USER`
- `DB_TYPE`
- `DB_HOST`
- `DB_PORT`
- `DB_USER`
- `DB_PASS`
- `DB_NAME`
