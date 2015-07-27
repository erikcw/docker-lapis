docker-lapis
============

This image aims to provide a clean docker base image for the latest version of the Lapis Lua web framework (backed by OpenResty).

OpenResty is installed at `/opt/openresty`. To use this image, place your Lapis application files in `/opt/openresty/nginx/conf` (either by attaching a docker volume or Creating a new Dockerfile `FROM erikcw/lapis:latest`.).
