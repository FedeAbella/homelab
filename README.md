# Homelab config

Containers and config for them in use in my personal homelab.

Containers are run using `podman` and `podman-compose`. `nginx-proxy-manager`
custom network is used to facilitate `ufw` rules to access other containers only
through `npm`.

## Containers

- [cloudflare-ddns](https://github.com/timothymiller/cloudflare-ddns)
- [Nginx Proxy Manager](https://nginxproxymanager.com/)
