# Basic Traefik 2.0 template

To run:
* `docker-compose -f docker-compose.local.yml -f docker-compose.whomai.yml up -d`
* add to /etc/hosts: alias for idcp.localdomain
* `lynx http://idcp.localdomain`
* `lynx https://idcp.localdomain`
