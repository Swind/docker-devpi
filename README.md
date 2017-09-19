## Run

    docker run -v $(pwd)/mnt:/mnt -p 3141:3141 -it widerin/openshift-devpi:latest

## Environment variables

- `DEVPI_PASSWORD`: devpi creates a user named `root` by default, its password
  can be set with this environment variable.
- `DEVPI_MIRROR_CACHE_EXPIRY`: Default to `86400` which is one day. Cache expiry time.
