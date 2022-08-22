<img src="https://user-images.githubusercontent.com/1423657/173144443-fc7ba783-d5bf-47f9-bf59-707693da5ed1.png" width=200 />

# qryn-oss-demo
**qryn.js** docker demo w/ sample _logs, traces and metrics_

![184538094-13c11500-24ef-4468-9f33-dc9d564238e3](https://user-images.githubusercontent.com/1423657/186014786-165b18da-e808-4cf7-a6fc-eb90df705400.gif)

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

