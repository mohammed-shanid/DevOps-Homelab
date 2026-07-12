# 🏠 DevOps Homelab

A production-inspired DevOps homelab built from scratch to learn Linux, Docker, networking, system administration, infrastructure, and cloud engineering through hands-on projects instead of tutorials.

> This repository documents my journey from Linux fundamentals to production-grade infrastructure.

---

## 🎯 Objectives

- Learn Linux system administration
- Master Docker & Docker Compose
- Understand container networking and service communication
- Build infrastructure using production-style practices
- Progress toward Kubernetes, CI/CD, Terraform, monitoring, and cloud deployments

---

## 📂 Repository Structure

```text
homelab/
├── compose/
│   ├── browser-server/
│   ├── download-server/
│   ├── dashboard/
│   └── monitoring/
│
├── data/
│   ├── firefox/
│   ├── qbittorrent/
│   ├── homepage/
│   └── monitoring/
│
├── docs/
├── scripts/
├── assets/
└── README.md
```

---

## 🖥️ Current Infrastructure

### Download Server

- Docker Compose
- qBittorrent
- Persistent bind mounts
- Shared external storage

### Browser Server

- Firefox (LinuxServer.io)
- Persistent browser profile
- Docker networking
- Shared downloads

---

## 📚 Concepts Practiced

- Linux
- Docker
- Docker Compose
- Images & Containers
- Bind Mounts
- Volumes
- Environment Variables
- Port Mapping
- Docker Networks
- Internal Docker DNS
- Container Isolation
- Service Architecture

---

## 🚧 Roadmap

- [x] Docker installation
- [x] Docker Compose
- [x] qBittorrent Stack
- [x] Firefox Browser Stack
- [x] Docker Networking
- [ ] VPN Integration (Gluetun)
- [ ] Reverse Proxy
- [ ] Homepage Dashboard
- [ ] Monitoring Stack
- [ ] Docker Images & Dockerfiles
- [ ] CI/CD Pipeline
- [ ] Terraform
- [ ] Kubernetes
- [ ] AWS Deployment

---

## 💡 Philosophy

This homelab is not a collection of random Docker containers.

Every service is added only if it solves a real infrastructure problem or teaches a production-relevant engineering concept.

The goal is to understand **why** systems are designed a certain way—not just how to deploy them.

---

## 🛠️ Tech Stack

- Debian 13
- Fedora Workstation
- Docker
- Docker Compose
- qBittorrent
- Firefox (LinuxServer.io)
- Git
- GitHub

---

## 📈 Current Status

🚧 Work in Progress

This repository is actively being built as part of my transition toward Cloud & DevOps Engineering.