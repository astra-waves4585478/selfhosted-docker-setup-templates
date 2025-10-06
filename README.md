# selfhosted-docker-setup-templates
A collection of Docker Compose setups for home systems, privacy tools, and automation. All tested on Ubuntu 24.04 with Docker &amp; Docker Compose v2 &amp; tailscale 

# Home Lab Docker Services

Educational examples of Docker Compose setups for typical self-hosted services.  
These are **anonymised**, generic templates based on real configurations used in home labs.

> ⚠️ No live systems or personal data are represented.  
> Use these files as learning material — modify to suit your own environment.

## Contents
- [reverse_proxy](./reverse_proxy): Example of Caddy/Nginx reverse proxy
- [notes_backup](./notes_backup): Generic backup system (e.g., rsync or Rclone)
- [private_cloud](./private_cloud): Example Nextcloud stack
- [local_db](./local_db): Example CouchDB/PostgreSQL setup

## Tested Environment
- Ubuntu 24.04 LTS  
- Docker Engine 27+  
- Docker Compose v2+

## Usage
Clone the repo, edit environment variables, and run:
```bash
docker compose up -d
```
