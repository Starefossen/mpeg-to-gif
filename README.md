MPEG to GIF
===========

```bash
vagrant up; vagrant ssh
ffmpeg -ss 00:00:00.000 -i input.mov -pix_fmt rgb24 -r 10 -s 320x240 -t 00:00:10.000 output.gif
convert -layers Optimize output.gif output_optimized.gif
```

