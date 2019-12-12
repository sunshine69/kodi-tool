# kodi-tool
Small playground with kodi controlling

Currently it can allow you to add playlist, play, queue and save/load playlist
(not kodi playlist but itself)

Have fun with Go!

# Usage

### Build

`go build`

### Run

```
kodi-tool -h
# remember to enable jsonrpc on kodi
kodi-tool -kodiurl localhost:9090
```

Now accessing the http://kodi-tool-server-ip:8001/static

You can create a new tab in browser, goto youtube, search song, copy link url
and insert it in. Play around the simple GUI interface.

I usually use it for karaoke list :P

You can cross build on Linux ARM as I ran on my X96 box (using linux-deploy to get a chroot
linux there to run several other servers)
