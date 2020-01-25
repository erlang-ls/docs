# README

This repo contain documentation resources for the Erlang Language Server.

## Gif

Gifs are created by performing a screen-recording via QuickTime (Emacs
window only). Files are saved in full quality, trimmed as required and
then converted to GIF via:

    ffmpeg -i [INPUT].mov -vf scale=1000:-1 -r 10 -f image2pipe -vcodec ppm - | convert -delay 5 -layers Optimize -loop 0 - [OUTPUT].gif
