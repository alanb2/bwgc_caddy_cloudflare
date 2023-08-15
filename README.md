# Bitwarden on Google Cloud Docker Image - Caddy - Cloudflare

This is the proxy container repository for the [Bitwarden self-hosted on Google Cloud for Free](https://github.com/dadatuputi/bitwarden_gcloud) project.

## Changes

Base Image: `caddy:alpine`

Changes to Base Image: 
- Add [caddy-dns/cloudflare](https://github.com/caddy-dns/cloudflare) module for DNS-01 ACME validation support
- Add tzdata package so timezone is set using `TZ` env variable
