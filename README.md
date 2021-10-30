## Introduction

Create a docker container based on bitnami/nginx to validate domain name for ZeroSSl

## Build

# Steps

1. Install Docker and docker-compose
2. Make sure the machine running the container can be accessed from the internet by domain
3. Download the txt file from ZeroSSL and put it in nginx_public/.well-known/pki-validation
4. Execute `docker-compose up -d`
5. Verify Domain Name on ZeroSSL Dashboard
