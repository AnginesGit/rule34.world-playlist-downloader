# rule34.world-playlist-downloader
rule34.world playlist downloader first version.

![image](/img/example.png) 
  
  ---
## Usage
```
    -d  <PATH>  specify directory to save playlist carpet.
    -i          only images (and thumbnails of videos).
    -v          only videos.

    -h          show help
```
### examples:
simple usage, a carpet will be created on the same directory
```
$ ./r34world
paste playlist id or url:
https://rule34.world/playlists/view/<ID>

```

Only Images on your home

```
$ ./r34world -id ~
paste playlist id or url:
https://rule34.world/playlists/view/<ID>
```


---
## Help
- this script only can get the first page of playlist (60 posts), urls getting x pages doesn't work for playlist, only searching tags. If anyone can help with this, I will appreciated you.
