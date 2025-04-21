# 📊 ELK Stack Logging Demo

This project sets up a centralized log aggregation stack using **Elasticsearch**, **Logstash**, and **Kibana** (ELK) to parse and visualize logs from an **Nginx** server.

## 🔍 What It Does

- Collects and parses logs from an Nginx server
- Stores logs in Elasticsearch
- Visualizes logs with Kibana dashboards

## 🧰 Stack

- Elasticsearch
- Logstash
- Kibana
- Nginx (as a log source)
- Docker Compose

## 📂 Project Structure

```
elk-stack-logging-demo/
├── docker-compose.yml
├── logstash/
│   └── logstash.conf
├── nginx/
│   └── default.conf
└── README.md
```

## 🚀 Usage

### 1. Start the stack

```bash
docker-compose up -d
```

### 2. Access the dashboards

- **Kibana**: [http://localhost:5601](http://localhost:5601)
- **Nginx**: [http://localhost:8080](http://localhost:8080)

### 3. Import logs

Check Logstash is forwarding logs to Elasticsearch. Go to **Kibana > Discover** to browse logs.

---

> Ideal for learning centralized logging and log parsing using the ELK stack.
