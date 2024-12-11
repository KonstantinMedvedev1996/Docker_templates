# Docker Templates for Quick Start

Welcome to the **Docker Templates** repository! This collection of templates provides pre-configured Docker setups for quickly starting various types of projects. Whether you're building a web application, setting up an Ubuntu server, or starting a database, these templates are here to help.

## Table of Contents

- [Introduction](#introduction)
- [Templates](#templates)
  - [Web Application](#web-application)
  - [Ubuntu Server](#ubuntu-server)
  - [Database](#database)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

Docker is a powerful tool for containerizing applications and services. This repository aims to provide a set of templates for common setups, making it easier to get started with Docker for your projects. Each template includes a `Dockerfile` and, where applicable, complementary files like `docker-compose.yml` or configuration files.

## Templates

### Web Application

**Description:**
A starter template for deploying a web application. This template is based on Nginx and Node.js (can be adjusted based on your needs).

**Files:**
- `Dockerfile`
- `docker-compose.yml`

**Example Usage:**
```bash
git clone https://github.com/your-repo/docker-templates.git
cd docker-templates/web-application
docker-compose up
```
For more details, see the [Web Application README](web-applications/README.md).

### Ubuntu Server

**Description:**
A minimal template to create an Ubuntu-based container. Perfect for running custom scripts or services.

**Files:**
- `Dockerfile`

**Example Usage:**
```bash
git clone https://github.com/your-repo/docker-templates.git
cd docker-templates/ubuntu-server
docker build -t my-ubuntu-server .
docker run -it my-ubuntu-server
```

### Database

**Description:**
A template for starting a MySQL database server with pre-configured settings.

**Files:**
- `Dockerfile`
- `docker-compose.yml`
- `.env` (for environment variables)

**Example Usage:**
```bash
git clone https://github.com/your-repo/docker-templates.git
cd docker-templates/database
docker-compose up
```

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/KonstantinMedvedev1996/Docker_templates.git
   ```
2. Navigate to the template you need.
3. Follow the usage instructions provided in each template's README or inline comments.

## Contributing

We welcome contributions! If you have a template that could benefit the community, feel free to:

1. Fork this repository.
2. Create a new folder with your template.
3. Submit a pull request with a clear description of your template and its usage.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
