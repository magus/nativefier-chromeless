# nativefier-chromeless

[nativefier](https://github.com/jiahaog/nativefier)...but [chromeless](https://github.com/jiahaog/nativefier/blob/master/docs/api.md#hide-window-frame) and [draggable](https://github.com/electron/electron/blob/master/docs/api/frameless-window.md#draggable-region)

## usage

```sh
yarn global add nativefier

nativefier "http://crawl.akrasiac.org:8080/#lobby" \
  --hide-window-frame \
  --maximize \
  --inject ./draggable.css \
  --name DCSS \
  ~/Desktop
```
