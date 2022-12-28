# compose-files
This is a repo containing different docker-compose.yml files that I use in my personal projects.

## Portainer
The portainer docker-compose.yml uses the following images:
- portainer/portainer-ce for container management
- nginxproxy/nginx-proxy as a reverse proxy with automatic routing to containers
- nginxproxy/acme-companion for handling SSL certificates for the proxied containers

