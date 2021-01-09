# Install Nextcloud & Traefik with docker-compose

## Description

Traefik is a reverse-proxy: https://doc.traefik.io/traefik/
Nextcloud is a file hosting service: https://nextcloud.com/

This is a example of Nextcloud installation, with HTTPS.

## Requirements

1. Linux server
2. Docker installed: https://docs.docker.com/engine/install/
3. Docker-compose installed: https://docs.docker.com/compose/install/
4. A DNS name nextcloud.YOUR_DOMAIN (ex: https://nextcloud.worshiptheuseless.org) pointing to your server IP address

## Installation

1. Copy the file `docker-compose.yml` in your server
2. Copy the file `.env` in your server
3. Update variables in your `.env` file:
4. Run it with the command `docker-compose up -d`
5. Wait 5-10 minutes for the installation finish
6. Go to https://nextcloud.YOUR_DOMAIN (ex: https://nextcloud.worshiptheuseless.org)
