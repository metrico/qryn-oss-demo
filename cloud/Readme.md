# qryn-go
Containers and Recipes for Docker

## Overview

Docker Compose to start
 - Clickhouse
 - Grafana
 - QRYN-Writer
 - QRYN-Go

## To Start

docker login ghcr.io
username: XXXXX
password: token with read:package permission enabled

docker compose up -d

## Ports

Clickhouse exposes: 9000, 8123
Grafana exposes: 3000
QRYN-Writer exposes: 3101
QRYN-Go exposes: 3200
