# Web Application Templates

This directory contains Docker templates for quickly starting web applications. Each template is tailored for a specific stack or use case. Below are the available templates and their descriptions.

## Table of Contents

- [Nginx + Node.js](#nginx--nodejs)
- [React Development Server](#react-development-server)
- [Django + Gunicorn](#django--gunicorn)

---

## Nginx + Node.js

**Description:**
This template sets up an Nginx server as a reverse proxy and a Node.js application server. Ideal for serving production-ready web applications.

**Files:**
- `Dockerfile`
- `docker-compose.yml`
- `nginx.conf`

**Example Usage:**
```bash
cd nginx-nodejs
docker-compose up
