## docker-nginx
Dockerized NGiNX Reverse Proxy in front of Apache Storm.

## Prerequisites
**Add certs/key**
Add your cert and key to nginx/certs/.

**Add .htpasswd**
The basic authentification uses the following credentials by default:
* user: dummy
* pw: password

**Edit nginx.conf**
Update to the IP/domain name of your server.

## Credits
Credits belong to [wurstmeister](https://github.com/wurstmeister/storm-docker) and [nginx](https://github.com/nginxinc/docker-nginx) for their work on Apache Storm and NGiNX.
