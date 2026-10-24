# psql

[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/shubhamtatvamasi/psql)](https://hub.docker.com/r/shubhamtatvamasi/psql)
[![Docker Image Version (latest semver)](https://img.shields.io/docker/v/shubhamtatvamasi/psql?sort=semver)](https://hub.docker.com/r/shubhamtatvamasi/psql)
[![Docker Image Size (tag)](https://img.shields.io/docker/image-size/shubhamtatvamasi/psql/latest)](https://hub.docker.com/r/shubhamtatvamasi/psql)
[![Docker Pulls](https://img.shields.io/docker/pulls/shubhamtatvamasi/psql)](https://hub.docker.com/r/shubhamtatvamasi/psql)
[![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/shubhamtatvamasi/psql/latest)](https://hub.docker.com/r/shubhamtatvamasi/psql)
[![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/shubhamtatvamasi/psql)](https://hub.docker.com/r/shubhamtatvamasi/psql)

```
brew install libpq
```

```
echo 'export PATH="/opt/homebrew/opt/libpq/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
```

```
psql -h <hostname> -p 5432 -U <username> -d <database>
```

---

connect to magma database:
```bash
PGPASSWORD=postgres psql -U postgres -d magma
```
