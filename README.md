# iconjs
:trollface: favico for fun


## 看视频

上下控制音量

左右控制前进后退5秒

```js
    var m = new Icon()
    m.initVideo('http://image.shengxinjing.cn/moyu/video/ji.mp4')
```



![](./img/01-video.gif)

## 摄像头

无聊的功能，我还加了个滤镜

```js
var m = new Icon()
m.initCam()
```

![](./img/02-cam.gif)

灰色滤镜

![](./img/02-cam-filter.gif)

怀旧滤镜

![](./img/02-cam-filter2.gif)

## 贪食蛇

上下左右，title显示分数和记录

```js
var s = new Snake()
s.init()
```

![](/Users/woniuppp/Downloads/iconjs/img/03-snake.gif)