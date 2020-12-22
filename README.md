# nativefier-chromeless

[nativefier](https://github.com/jiahaog/nativefier)...but [chromeless](https://github.com/jiahaog/nativefier/blob/master/docs/api.md#hide-window-frame) and [draggable](https://github.com/electron/electron/blob/master/docs/api/frameless-window.md#draggable-region)

![nativefier-chromeless-demo](https://user-images.githubusercontent.com/290084/102848067-b985b580-43c8-11eb-824d-baef28c0e12d.gif)


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
