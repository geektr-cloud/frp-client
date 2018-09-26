# frp-client

## Deploy

```bash
# source deploy script first
source <(wget -qO- https://raw.githubusercontent.com/geektr-cloud/frp-client/master/deploy.sh)

# update (init) project to local enviroment
frp-client::update

# when first run this init data directory and secrets directory
frp-client::init-secrets

# edit secrets files
# vim xxxxxx

# up the services
frp-client::up
```

## Backup

```bash
source /srv/geektr.cloud/frp-client/deploy.sh

frp-client::backup-data
```
