# genshin-server-switching

Windows版原神大陆地区bilibili/官服切换程序

## 如何使用

1. 从[这里](https://github.com/misaka10843/genshin-server-switching/releases/latest)下载最新的编译版本,随便放在哪里都可以(建议**新建一个文件夹放入exe程序后创建快捷方式**)

2. 复制游戏路径(如：`E:\Genshin Impact\Genshin Impact Game`)

3. 启动程序按照提示操作即可qwq

（ps：此程序的配置文件已经链接到本仓库的`ver.json`上，只要此文件一更新所有程序再次打开时会**重新获取配置**）

## 注意

千万要记住必须要填写对的游戏路径！
如：`E:\Genshin Impact\Genshin Impact Game`

## 实现功能

- [x] 检测版本(V2按照json中直接版本替换)
- [x] 更换服务器
- [x] 检测路径正确
- [x] 判断是否安装原神
- [x] 自动更新版本信息(在程序中)
- [ ] 图形化界面

## readme统计

![统计](https://count.getloli.com/get/@misaka10843?theme=elbooru)

## 后言

重新用python写了一下
果然我还是不适合用C++写啊qwq

## 备注

### 2021.10.8

重新更改了语言，从C++更改成python，并且使用远程json来检测更新

### 2021.9.25

最近可能会重新编写此程序，并且直接向此仓库get版本信息而不需要再修改任何文件qwq

## 截图

![命令行](jietu/1.png)
(命令行截图)

![图标对比](jietu/2.png)
(图标对比)

## 开源协议

MPL-2.0 License
