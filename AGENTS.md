# Base44 Dev Environment

## Overview
This repo contains static HTML landing pages under `sites/`. No backend, database, or build step.

## Running
```
docker compose -f docker-compose.base44.yml up -d
```
Serves `sites/impresiones3dfusions/index.html` via nginx on port 3000.

## Sites
- `sites/impresiones3dfusions/` — 3D printing/design landing page (currently served)
- `sites/cafeteria-luna/` — café landing page

## Notes
- To serve a different site, change the volume mount in `docker-compose.base44.yml`.
- No secrets or external services required.
