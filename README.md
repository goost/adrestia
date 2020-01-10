# Project "Adrestia"

## Description
Improve your life with Adrestia.

## Architecture

![](./images/architecture.png)

## Notes

### Minimal Version
* modular
* minimal NextCloud
* docker
* Office (NextCloud Connection)
* SecureConnection -> OpenVPN

* Caddy or Traeffik Proxy/Domain?
* Backups of Containers via mounting and backup software on well-known mount location

### Optional Features
* Startpage
* Monitoring Page
* Financial Manager		    -> FireflyIII or app.financier.io
* Photosoftware			    -> Pivigo 
* Media Streaming Software	-> plex 
* Music Player
* Git-Server			    -> Gitlab or Gitea 
* RSS-Reader 			    -> to read and subscribe NewsFeeds
* Webmail-Client		    -> roundcube (-> opensource webmail software which connects with my secure email)
* Backups
* Read-it-later
* Mindmap Software
* Bitwarden (needs individual Licensing Key (which is free but still...), also needs HTTPS and Domain, so nope)
    * Bitwarden-rs lightweight server implementation?

### Commands

* getent hosts <domain>




