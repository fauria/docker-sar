fauria/sar
==========

![docker_logo](https://raw.githubusercontent.com/fauria/docker-sar/master/docker_139x115.png)![docker_fauria_logo](https://raw.githubusercontent.com/fauria/docker-sar/master/docker_fauria_161x115.png)

[![Docker Pulls](https://img.shields.io/docker/pulls/fauria/sar.svg?style=plastic)](https://hub.docker.com/r/fauria/sar/)
[![Docker Build Status](https://img.shields.io/docker/build/fauria/sar.svg?style=plastic)](https://hub.docker.com/r/fauria/sar/builds/)
[![](https://images.microbadger.com/badges/image/fauria/sar.svg)](https://microbadger.com/images/fauria/sar "fauria/sar")

This Docker container implements interconnect/it [Database Search and Replace Script](https://interconnectit.com/products/search-and-replace-for-wordpress-databases/) script.

Documentation pending.

Examples
----
```
docker run -i -t --rm --link mysql-container:mysql -p 8080:80 --entrypoint "/bin/bash" fauria/sar
```
