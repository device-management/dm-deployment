# Device Management - Deployment

Represents a configuration for automatic deployment.

## Prerequisites

* [Docker compose](https://docs.docker.com/compose/)

## Usage

Production environment:
```bash
docker-compose -f docker-compose.yml up -d
```

Development environment:
```bash
docker-compose -f docker-compose.yml -f docker-compose.dev.yml up -d
```
