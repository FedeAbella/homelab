# Homelab config

Containers and config for them in use in my personal homelab.

Containers are run using `docker compose`. `nginx-proxy-manager` custom network
is used to facilitate `ufw` rules to access other containers only through `npm`.

## Containers

### Connection

- [Nginx Proxy Manager](https://nginxproxymanager.com/): Reverse Proxy
- [cloudflare-ddns](https://github.com/timothymiller/cloudflare-ddns): Update
  Cloudflare proxy DDNS with dynamic local IP
- [Apache Guacamole](https://guacamole.apache.org/): Remote access

### Monitor

- [portainer.io](https://www.portainer.io/): Container Manager
- [gotify](https://gotify.net/): Notifications
- [Homarr](https://homarr.dev/): Dashboard

### Media

- [Prowlarr](https://prowlarr.com/): Indexer Manager
- [Radarr](https://radarr.video/): Movie Manager
- [Sonarr](https://sonarr.tv/): TV Series Manager
- [Deluge](https://deluge-torrent.org/): Bittorrent Client
- [Jellyfin](https://jellyfin.org): Media Manager and Player
