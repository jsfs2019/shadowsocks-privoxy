# Shadowsocks-Privoxy

    forked from [oldiy/shadowsocks-privoxy](https://github.com/oldiy/shadowsocks-privoxy)

    Add PAC that you can use Synology NAS to sync your dropbox or googledrive by CloudSync.
    It's not global.
    
    Add Facebook & Twitter API, so you can share your ps4 photos.

## Features

-  Add chacha20 support

## Run

```bash
docker run --name shadowsocks-privoxy \
  -e SERVER_ADDR=ss.server.ip SERVER_PORT=port PASSWORD=123456 METHOD=chacha20 \
  -p 8118:8118 7070:7070 \
  yyscamper/shadowsocks-privoxy:latest
```
