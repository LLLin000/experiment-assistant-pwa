# 实验助手 PWA

一个面向移动端的科研实验设计与记录网页工具。

## 在线访问

部署后地址：<https://lllin000.github.io/experiment-assistant-pwa/>

## 使用方式

1. 用 iPhone Safari 打开在线地址。
2. 点击分享按钮 → **添加到主屏幕**。
3. 从主屏幕打开即可使用。

## 数据说明

- 实验数据默认保存在当前浏览器的 `localStorage`。
- GitHub 仓库只保存网页程序，不保存实验记录。
- 换设备或清除 Safari 网站数据前，请使用“导出全部 JSON”备份。
- 网页程序更新后，数据结构会尽量兼容已有记录；重要记录仍建议定期导出。

## 更新方式

向 `main` 分支推送新的网页文件后，GitHub Actions 会自动发布到 GitHub Pages。部署通常需要几十秒到几分钟。
