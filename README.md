# arr-suite

Goal is to set up a fully rebuild-able Docker Compose stack which takes care of the following:

* Creates Radarr in home directory of "jerron" user: /home/jerron/Radarr
* Sonarr deployment: /home/jerron/Sonarr
* qBittorrent-nox deployment
* NGINX reverse proxy for placing everything in subdomains
* Later goals:
  * PLEX server within this deployment
  * *Maybe* a container for a VPN or tunnel, connected to NGINX

Testing server: 193.122.162.94
