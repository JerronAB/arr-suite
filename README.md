# arr-suite

Goal is to set up a fully rebuild-able Docker Compose stack which takes care of the following:

* Creates Radarr in home directory of relevant user
* Sonarr deployment
* qBittorrent-nox deployment
* NGINX reverse proxy for placing everything in subdomains
* Later goals:
  * PLEX server within this deployment
  * *Maybe* a container for a VPN or tunnel, connected to NGINX

A ridiculous amount of work still has to be done:

setup.sh needs to add user control to subfolders for qbittorrent to do the downloads

Plex will always require setup on both app and server. Use

ssh ubuntu@[plex-server-ip4] -i private-ssh.key -L 8888:localhost:32400 <-- this allows one to initially access the web services to set up public access.
