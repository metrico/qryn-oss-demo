<img src="https://user-images.githubusercontent.com/1423657/173144443-fc7ba783-d5bf-47f9-bf59-707693da5ed1.png" width=200 />

# qryn-js
Docker Compose for qryn-js (opensource)

## Overview

This docker-compose will spin up a full qryn setup w/ test data for validation

The following elements will be started and automatically configured:

- qryn
- clickhouse
- grafana
- vector

### Usage

From the current directory execute the following steps to get started:

1) Start the containers
```
docker-compose up -d
```
2) Login to Grafana as `admin/admin`
```
http://localhost:3000
```
3) Explore Loki logs and Tempo traces using the auto-configured datasources:

![image](https://user-images.githubusercontent.com/1423657/183254312-b52811e5-f563-440e-84e4-8312714a4c9b.png)

![image](https://user-images.githubusercontent.com/1423657/183254290-fac87747-51ce-4648-a7aa-073fdcdd6c10.png)

