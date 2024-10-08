# 简单导航
五分钟上线一个导航网站

<img src="./public/jc3.png" alt="数据目录" size="50%" />


## 介绍

官网：[https://tag.zhuayuya.com](https://tag.zhuayuya.com)

最简单的导航网站解决方案，使用主流框架 Next.js技术栈编写，服务端渲染更利于 SEO

使用标签星球导出收藏夹为 JSON 格式文件，将文件夹放入「简单导航」数据目录即可生成一个导航网站，发布到服务器上线，全程不到 5 分钟

## 使用方法
推荐使用 `pnpm` `NodeJS 16+版本`


- 下载代码到本地

- 安装依赖

```
npm i
pnpm i
```

- 启动
```
pnpm start
```

## 数据
简单导航是一个 JSON 驱动的导航系统，没有操作后台，一切都是 JSON

在，`public/data` 目录下放置了系统所需的 JSON 文件，按照以下方法修改 JSON 文件即可完成上线之前的网站配置

**1、如何添加导航网址：** 简单导航的网址添加非常的简单，无需传统导航系统那样挨个添加

只需要将想要展示在导航里的网站用浏览器自带的收藏夹功能收藏起来，下载「标签星球」浏览器扩展，选中要导出的收藏夹，点击「导出」按钮，即可把收

藏夹导出为一个 JSON 文件
<img src="./public/jc1.png" alt="数据目录" size="50%" />

替换掉 `public/data/nav.json` 文件即可

**2、如何修改网站名称及其他网站基础配置：** 打开 `public/data/config.json` 文件，修改 `title` 字段即可，修改其他配置详见此目录的其他字段

**3、如何修改菜单：** 打开 `public/data/menu.json` 文件，修改 `title` 和 `url` 字段

**4、如何修改网站LOGO：** 直接替换 `public/logo.svg` 文件我们推荐使用 `svg` 格式

**5、如何修改网站favicon：** 直接替换 `public/favicon.svg` 文件我们推荐使用 `svg` 格式

<img src="./public/jc2.png" alt="数据目录" size="50%" />

## 更多问题
微信：1090879115

