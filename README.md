## issue occur:
Tested on Chrome, Firefox, Edge  with:

to reproduce, start http server:

```sh
python -m http.server
```

## issue doesn't occur:
VLC media player, windows media player, ffplay

to reproduce :
```
ffplay -vf subtitles=filename=input.mkv input.mkv
```
