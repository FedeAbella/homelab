# Homelab config

Containers and config for them in use in my personal homelab.

Containers are run using `docker compose`. `nginx-proxy-manager` custom network
is used to facilitate `ufw` rules to access other containers only through `npm`.

## Containers

### Connection

- [Nginx Proxy Manager](https://nginxproxymanager.com/): Reverse Proxy
- [cloudflare-ddns](https://github.com/FedeAbella/cloudflare-ddns): Update Cloudflare DDNS
- [Apache Guacamole](https://guacamole.apache.org/): Remote access
- [ProtonMailBridgeDocker](https://github.com/VideoCurio/ProtonMailBridgeDocker):
  Send emails via ProtonMail custom domains

### Monitor

- [portainer.io](https://www.portainer.io/): Container Manager
- [gotify](https://gotify.net/): Notifications
- [Watchtower](https://containrrr.dev/watchtower/): Container updater

### Media

- [Prowlarr](https://prowlarr.com/): Indexer Manager
- [Radarr](https://radarr.video/): Movie Manager
- [Sonarr](https://sonarr.tv/): TV Series Manager
- [Deluge](https://deluge-torrent.org/): Bittorrent Client
- [Jellyfin](https://jellyfin.org): Media Manager and Player
- [Calibre Web](https://github.com/janeczku/calibre-web): Ebook Management

### Storage

- [Nextcloud](https://nextcloud.com/): Self-hosted cloud storage

### Misc

- [Homarr](https://homarr.dev/): Dashboard
- [BookStack](https://bookstackapp.com): Collaborative note-taking
- [Excalidraw](https://excalidraw.com): Drawing board
- [FreshRSS](https://github.com/FreshRSS/FreshRSS): RSS Feed

### Dev Tools

- [Webhook Tester](https://github.com/tarampampam/webhook-tester): HTTP Testing
- [ChartDB](https://github.com/chartdb/chartdb): DB Diagram Editor
