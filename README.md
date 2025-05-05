# 2025cloud Docker Project

This repository contains two simple Python applications, **app1.py** and **app2.py**, each packaged as a Docker container.

---

## 📦 Files
-- container_1
---- `app1.py` → Prints "Hello from App 1!"
---- `Dockerfile` → Docker build instructions 
-- container_2
---- `app2.py` → Prints "test authentic"
---- `Dockerfile` → Docker build instructions 

---

## 🛠 Build the Docker Image

### Build from local

```bash
# App 1
docker build -t yourdockerhubusername/2025cloud:app1 ./container_1
docker run yourdockerhubusername/2025cloud:app1

# App2 
docker build -t yourdockerhubusername/2025cloud:app2 ./container_2
docker run yourdockerhubusername/2025cloud:app2
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
