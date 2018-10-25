# iPokeMon Edge Server
This is the Edge server of iPokeMon, modified from [iPokeMon Cloud Server](https://github.com/qub-blesson/ENORM/tree/master/Application/iPokeMon-CloudServer). Removed functionalites include: user ID management, user initialisation.

## Tested Platform
We have tested the iPokeMon Edge server in [LXC](https://help.ubuntu.com/lts/serverguide/lxc.html) on [ODroid XU3](https://www.hardkernel.com/main/products/prdt_info.php?g_code=g140448267127) with [Alpine Linux](https://alpinelinux.org/) v3.4.

## Requirement
- [Redis](https://redis.io/)
- [Python](https://www.python.org/), [py-pip](https://pkgs.alpinelinux.org/package/v3.3/main/armhf/py-pip), [redis-py](https://github.com/andymccurdy/redis-py)

## How to use
iPokeMon Edge Server is deployed by the [Cloud Manager](https://github.com/qub-blesson/ENORM/tree/master/CloudManager) when requesting Edge services.
