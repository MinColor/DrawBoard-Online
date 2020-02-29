# DrawBoard-Online

draw together with yout coworker, enjoy the creating time

## 1、基于socket io 和 canvas  实现的共享画板

> 起初只是想要写个简单的画板,后面不知不觉的想起石墨文档有一个白板功能，就想将当前这个画布功能，开发成一个简易版的协作画板。
> <hr>
> 在线演示：努力部署中，目前需要clone到本地运行。

## 2、运行

```bash
git clone <repository>

npm install

#>>>对于开发阶段：
#前端服务启动（利用webpack dev server）：
npm run dev

#后台服务启动(使用了nodemon 实时监听后端文件修改重启服务)
npm run start

#>>>对于生产阶段：
#打包前端文件,然后启动服务器即可
1、 npm run build
2、 npm run start
```

## 注意 还需要启动nodejs socket.io服务

node server.js

## 3、功能：

#### 开发完成:

- 画布缩放(Done)
- 画布颜色(Done)
- 画笔颜色(Done)
- 画笔粗细(Done)
- 历史记录（撤销，恢复）(Done)
- 聊天室(Done)
- 绘制协作(类似于石墨文档协作)（Done）
- UI 界面美化（Done）
  - 使用UI库（material Design）


#### 待开发的功能：

- 文字控件（待开发）
- 上传图片，基于图片绘图（待开发）
- 绘图带基本形状可拖拽调控大小 （待开发）
- 聊天功能丰富（表情，图片，音视频）（待开发）
  - webRTC 获取视频流数据，并传输
- 其它未知功能（x）

## 4、效果图

![效果图1](http://photo.forrestyuan.cn/draw1.gif)

![效果图2](http://photo.forrestyuan.cn/draw2.gif)

## 5、使用MDUI后效果

![效果图3](https://github.com/forrestyuan/DrawBoard-Online/blob/master/upgrade1.PNG)
![效果图4](https://github.com/forrestyuan/DrawBoard-Online/blob/master/upgrade2.PNG)

# License

MIT
