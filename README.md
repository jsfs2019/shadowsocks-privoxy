# Shadowsocks-Privoxy

    forked from [oldiy/shadowsocks-privoxy](https://github.com/oldiy/shadowsocks-privoxy)

    Add PAC that you can use Synology NAS to sync your dropbox or googledrive by CloudSync.
    It's not global.
    
    Add Facebook & Twitter API, so you can share your ps4 photos.

## Features

-  Add chacha20-ietf-poly1305 support

## Run

```bash
docker run -i -t -e SERVER_ADDR=<addr> -e SERVER_PORT=<port> -e PASSWORD=<passwd> -e METHOD=chacha20-ietf-poly1305 -p 8118:8118 -p 7070:7070 jarontang/shadowsocks-privoxy
```
notes:

- 8118: http proxy port
- 7070: socks5 proxy port
