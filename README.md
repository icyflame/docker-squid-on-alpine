## Useful commands

```sh
# 1. Edit the squid configuration to allow some IP addresses
# 2. Build the docker images
$ docker-compose build
# 3. Start all the services
$ docker-compose up -d
# 4. Follow the access log (if required)
$ docker exec -it alpinesquid_squid_1 tail -f /var/log/squid/access.log
```
