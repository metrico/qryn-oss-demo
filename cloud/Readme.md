# qryn-go
Containers and Recipes for Docker

## Overview

Docker Compose to start
 - Clickhouse
 - Grafana
 - QRYN-Writer
 - QRYN-Go

## To Start
```
docker login ghcr.io
username: XXXXX
password: token with read:package permission enabled
```
```
docker compose up -d
```
## Ports

- clickhouse: 
  - 9000, 8123
- grafana: 
  - 3000
- qryn: 
  - 3101, 3200
