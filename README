This is a clone of Infinite Mario, written in JavaScript for web browsers using HTML5.  
这是 Infinite Mario 的一个克隆版本，使用 JavaScript 为支持 HTML5 的网页浏览器编写。

A good demonstration of what can be accomplished with the Canvas and Audio elements.  
这是一个很好的示例，展示了通过 Canvas 和 Audio 元素可以实现的功能。

Background music currently does not work in any browser besides Firefox 4. I think. There were too many problems with other browsers.  
除了 Firefox 4（我认为）之外，目前其他浏览器都无法正常播放背景音乐。因为其他浏览器存在太多问题。

Ported from the Java version by Notch (Markus Persson).  
由 Notch（Markus Persson）的 Java 版本移植而来。

## 部署说明

当前汉化仅适用于 版本：

首先感谢原作者的开源。[原项目地址](https://github.com/robertkleffner/mariohtml5)

具体汉化了那些内容，请参考[翻译说明](./翻译说明.md)。

有需要帮忙部署这个项目的朋友,一杯奶茶,即可程远程帮你部署，需要可联系。  
微信号 `E-0_0-`  
闲鱼搜索用户 `明月人间`  
或者邮箱 `firfe163@163.com`  
如果这个项目有帮到你。欢迎start。

有其他的项目的汉化需求，欢迎提issue。或其他方式联系通知。

### 镜像

从阿里云或华为云镜像仓库拉取镜像，注意填写镜像标签，镜像仓库中没有`latest`标签

容器内部端口 3000

```bash
docker pull swr.cn-north-4.myhuaweicloud.com/firfe/mario-1:2025.05.04
```

### docker run 命令部署

```bash
docker run -d \
--name mario-1 \
--network bridge \
--restart always \
--log-opt max-size=1m \
--log-opt max-file=3 \
-p 3000:3000 \
swr.cn-north-4.myhuaweicloud.com/firfe/mario-1:2025.05.04
```
### compose 文件部署 👍推荐

```yaml
#version: '3.9'
services:
  mario-1:
    container_name: mario-1
    image: swr.cn-north-4.myhuaweicloud.com/firfe/mario-1:2025.05.04
    network_mode: bridge
    restart: always
    logging:
      options:
        max-size: 1m
        max-file: '3'
    ports:
      - 3000:3000
```

## 修改说明

这里对除了汉化之外的代码修改的说明。  
增加修改部分具体见 [修改说明](./修改说明.md)。

`./README.md` 文件翻译，增加 `## 部署说明`、`## 修改说明`、`## 效果截图` 部分。

增加目录 `./图片`
新增文件 `./.dockerignore`、`./Dockerfile`、`./翻译说明.md`、`./修改说明.md`

## 效果截图

<img src="图片/效果图.png" width="500" />
