# nativefier-chromeless

[nativefier](https://github.com/jiahaog/nativefier)...but [chromeless](https://github.com/jiahaog/nativefier/blob/master/docs/api.md#hide-window-frame) and [draggable](https://github.com/electron/electron/blob/master/docs/api/frameless-window.md#draggable-region)

<img width="2048" alt="Screen Shot 2020-12-21 at 8 03 35 PM" src="https://user-images.githubusercontent.com/290084/102847657-b3dba000-43c7-11eb-945b-b4498c17ff5b.png">


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
