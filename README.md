# MCU Watch Order

A checklist of every Marvel Cinematic Universe film. Switch between release
order and chronological (story) order, tick films off as you watch them, and
see how many hours are left. Upcoming releases show a countdown.

It's a single static page (`index.html`) with no build step. Open it in a
browser, or serve it with GitHub Pages. Progress is saved in the browser's
`localStorage`, so it stays on the device you used.

To update the film list, edit the `FILMS` array near the top of the script.
Each film lists its director and cast as `character=Actor|note`. Recasts and
variants (a character played by more than one actor) are worked out from that
data automatically, so adding a cast entry is all it takes.
