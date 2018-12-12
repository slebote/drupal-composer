# About this Repo

**This image is based on drupal docker official image :**

- Docker image : [composer](https://hub.docker.com/_/composer/)
- Github repository : [composer/docker](https://github.com/composer/docker)

**Additions :**

- HTTPS support : usage of self-signed snakeoil certificates (based on linux package `ssl-cert`)
- Clean permissions with docker : force `www-data` user to every mounted volumes
- Mysql client for drush support

## Supported tags and respective `Dockerfile` links

- `1.8.0`, `1.8` [(1.8/Dockerfile)](https://github.com/slebote/drupal-composer/blob/master/1.8/Dockerfile)
