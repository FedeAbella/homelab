# Homelab config

Containers and config for them in use in my personal homelab.

Containers are run using `docker compose`. `nginx-proxy-manager` custom network
is used to facilitate `ufw` rules to access other containers only through `npm`.

## Containers

- [cloudflare-ddns](https://github.com/timothymiller/cloudflare-ddns): Update
  Cloudflare proxy DDNS with dynamic local IP
- [Nginx Proxy Manager](https://nginxproxymanager.com/): Handle requests to
  personal domain and subdomains via reverse proxy
- [Homarr](https://homarr.dev/): Homelab dashboard
