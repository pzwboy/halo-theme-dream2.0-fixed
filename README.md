<p align="center">
<img src="https://raw.githubusercontent.com/pzwboy/halo-theme-dream2.0-fixed/refs/heads/master/screenshot.png" alt="halo-theme-dream2.0" width="180">
</p>
<h1 align="center">halo-theme-dream2.0-fixed</h1>


<p align="center">本主题修改自 <a href="https://github.com/nineya/halo-theme-dream2.0" target="_blank">nineya/halo-theme-dream2.0</a> v1.3.2<br><b>注意：若在已安装原 <code>Dream</code> 主题的情况下安装本主题，二者主题设置将会被重置！</b></p>

## 一、预览

![玖涯博客](https://raw.githubusercontent.com/pzwboy/halo-theme-dream2.0-fixed/refs/heads/master/preview.png)

预览：[主题预览](https://pzwboy.top/)



## 二、说明

梦之城，童话梦境，动漫类型博客主题。

关于主题使用上的一些问题可以参见 [主题使用手册-基础篇](https://blog.nineya.com/archives/94.html)


## 三、版本适配关系

| 主题版本| 适配Halo版本 | 测试用Halo版本 |
| -------------- | -------------- | -------------- |
| 1.0.1 | 2.0.0+ | 2.22.4 |



## 四、安装 & 更新



1. 进入主题 `Release` 界面：https://github.com/pzwboy/halo-theme-dream2.0-fixed/releases 下载主题压缩包 `halo-theme-dream2.0.zip` 压缩包文件；
2. 进入博客后台管理 `主题->主题管理->安装主题`，选择下载的 `halo-theme-dream2.0.zip` 安装包进行上传；
3. 等待安装完成；
4. 更新主题时同样前往主题  `Release` 界面下载主题安装包，然后通过 `主题->主题管理->Dream Fixed->升级` 方法上传安装包进行更新。



## 五、参与主题开发

> 推荐使用 IDEA 进行主题开发，能够比较好的支持 FreeMarker。

1. 开发环境准备
    - 安装 `nodejs` 版本需要在 `15+`；
    - 主题目录下执行 `npm i` 安装依赖；

2. npm 命令
   
    - `npm run lint` 执行代码风格校验。
    - `npm run zip` 执行安装包打包，在无须重新编译 `js/css` 时使用。
    
    - `npm run build` 执行主题打包操作，主题将被打包为压缩包文件存放在 `dist/` 目录下，同时 `source` 目录下的文件也将被更新。
    - `npm run build --devel` 开发模式进行主题打包，`js` 和 `css` 不会被做压缩和混淆处理，方便排查问题。
    - `npm run release --tag=$version` 发布模式执行主题打包操作，将自动更新主题中的版本号，并使用这个版本标签重新创建  `FreeCDN` 清单文件。
