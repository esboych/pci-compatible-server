FROM dcr.mfb.io/bruteforce/nginx:v0.2.0

# Docker image name is: dcr.mfb.io/bruteforce/autocontrol-nginx

RUN mkdir -p /app/web && touch /app/web/app.php

COPY ./config/nginx.conf /etc/nginx/conf.d/default.conf
