# WolfBeacon Nginx Router

A Dockerized [Nginx](https://www.nginx.com/resources/wiki/) Server for WolfBeacon. This functions as a reverse proxy server to route incoming client requests to corresponding webservice handlers.

You must have a nginx.vh.default.conf file before issuing `docker build`. See `nginx.vh.default.example.conf` for more information.

**Base Image**: https://github.com/nginxinc/docker-nginx/tree/master/stable/alpine

**Credits**: http://stackoverflow.com/a/43956748/4258892
