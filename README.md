# Prometheus + Grafana Monitoring Stack

## Overview
This project demonstrates infrastructure monitoring using Prometheus, Grafana, and Node Exporter deployed with Docker Compose on AWS EC2.

## Architecture
Node Exporter → Prometheus → Grafana Dashboard

## Technologies Used
- AWS EC2
- Docker
- Docker Compose
- Prometheus
- Grafana
- Node Exporter

## Features
- Real-time CPU monitoring
- Memory usage visualization
- Disk and filesystem monitoring
- Network statistics
- Grafana dashboards for observability

## Files
- docker-compose.yml → Monitoring stack deployment
- prometheus.yml → Prometheus scrape configuration

## Access URLs
- Grafana: http://<EC2-IP>:3000
- Prometheus: http://<EC2-IP>:9090

## Ports
- 3000 → Grafana
- 9090 → Prometheus
- 9100 → Node Exporter

## Architecture

Node Exporter → Prometheus → Grafana

##  Run Stack

docker compose up -d
  
## Screenshots

### Grafana Dashboard

<img width="1344" height="630" alt="image" src="https://github.com/user-attachments/assets/f3abf928-3046-493a-9629-3563997d0d1e" />


### Prometheus UI

<img width="1355" height="558" alt="image" src="https://github.com/user-attachments/assets/bd4ccf97-d981-4fc3-b532-39d9aeb5c668" />



## Deployment
docker compose up -d

## Author
Narayana KS
