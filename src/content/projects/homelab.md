---
title: "Home Lab"
description: "Self-hosted infrastructure on a mini PC — Docker, reverse proxy, monitoring stack."
tags: ["docker", "linux", "devops", "self-hosted"]
status: "in progress"
github: "https://github.com/AlexSzczygielski"
weight: 1
---

## What It Is

A self-hosted homelab running on a mini PC. Services are containerised with Docker and exposed via a reverse proxy with automatic TLS.

## Stack

- **OS**: Debian Linux
- **Containers**: Docker + Docker Compose
- **Reverse proxy**: Caddy (automatic HTTPS)
- **Monitoring**: Prometheus + Grafana

## What I Learned

Setting this up taught me a lot about networking (VLANs, DNS, port forwarding), Linux administration, and how production-grade infrastructure actually works rather than just reading about it.
