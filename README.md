# PikPak 个人网页版

## 官方地址

 * [PikPak](https://mypikpak.com)

## Demo
 * [PikPak](https://mumuchenchen.github.io/pikpak/)

## 安装部署

### 安装教程
  * [去年夏天版教程](https://www.tjsky.net/?p=201)
### Github Aciton

### Github Page

### Cloudflare Workers
  * [CF Workers实现反代](cf-worker)

### 我改了什么
+ 添加config默认项，在`src\config\index.ts`加了默认aria2和默认登录账号配置
+ aria2设置添加走代理开关，可以推送到远程http协议的aria2服务器。走cf-worker时有效
