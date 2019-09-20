# rpi-ssr-server
SSR server migrated for arm devices.
https://github.com/shadowsocksr-backup/shadowsocksr
# Usage

```shell
$ docker run -p <port>:<port> \ 
    -v /path/to/your/configuration/file.json:/config.json \ # Should be synced with the path below
    -d \ # Run in background
    cheneyyan/rpi-ssr-server \
    -v -c /config.json 
```

# License
WTFPL - Don't worry about it.
