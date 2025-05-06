# 2025cloud Docker Project

This repository contains two simple Python applications, **app1.py** and **app2.py**, each packaged as a Docker container.

---

## 📦 Files
- container_1
  - app1.py — Prints "Hello from App 1!"
  - Dockerfile — Docker build instructions for app1.py

- container_2
  - app2.py — Prints "test authentic"
  - Dockerfile — Docker build instructions for app2.py

---

## 🛠 Build the Docker Image

### Build from local

```bash
# App 1
cd container_1
docker build -t myapp1:local .
docker run myapp1:local

# App2 
cd container_2
docker build -t myapp2:local .
docker run myapp2:local
```

### Pull and Run from Docker Hub
```bash
# App 1
docker pull r13922038/2025cloud:application
docker run r13922038/2025cloud:application

# App2 
docker pull r13922038/2025cloud:test
docker run r13922038/2025cloud:test
```
