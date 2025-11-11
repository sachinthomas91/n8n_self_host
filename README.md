# n8n Self-Hosted

A Docker Compose setup for running n8n (workflow automation platform) locally.

## Quick Start

1. **Start the service:**
   ```bash
   docker-compose up -d
   ```

2. **Access n8n:**
   Open `http://localhost:5678` in your browser

3. **Stop the service:**
   ```bash
   docker-compose down
   ```

## Requirements

- Docker
- Docker Compose

## Configuration

Edit `.env` file to customize n8n settings (port, database, etc.). See [n8n environment variables documentation](https://docs.n8n.io/hosting/environment-variables/) for available options.

## Data Persistence

Workflows and data are stored in Docker volumes. They persist between container restarts.
