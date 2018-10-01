xnbd-server in docker container
===============================
*serve an image file or a block device over the network*

```
docker-compose build
docker-compose up
```

Default Settings
================
| `Environment Variable` | `Default Setting` |
|:----------------------:|:-----------------:|
|   `DISTRO_VERSION`     |      `xenial`     |
|   `IMG_FILE`           | `/tmp/G4.img` (change this to yours) |
|   `PRIV_MODE`          | `false` (set to `true` if `IMG_FILE` is a blkdev |
|   `NBD_PORT`           | `8520`            |

__author__: *tuan t. pham*
