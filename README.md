# Homelab config

Containers and config for them in use in my personal homelab.

Containers are run using `docker compose`. Docker networks are needed for
containers to be able to talk to one another:

- `proxy`: Used for `nginx` to serve as reverse proxy
- `nextcloud-aio`: Used to route and send emails from the Nextcloud managed
  container
- `mail`: Used for apps that need access to ProtonMail

All networks need to be created first using `docker network create <network>`

## Containers

### Connection

- [Nginx Proxy Manager](https://nginxproxymanager.com/): Reverse Proxy
- [cloudflare-ddns](https://github.com/FedeAbella/cloudflare-ddns): Update Cloudflare DDNS
- [Apache Guacamole](https://guacamole.apache.org/): Remote access
- [ProtonMail Bridge](https://github.com/VideoCurio/ProtonMailBridgeDocker):
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
- [Planka](https://planka.app): Project tracking
