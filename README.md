# syndicate

[![Build](https://github.com/C4droid/syndicate/actions/workflows/main.yml/badge.svg)](https://github.com/C4droid/syndicate/actions/workflows/main.yml)

## 是什么

为 [project-syndicate](https://www.project-syndicate.org) 最新的 30 篇文章生成 rss

## 接下来准备做什么

- [x] 加上图片代理
- [x] 获取全文
- [ ] 识别付费文章，自动加上 archive.is 跳转链接

## 如何订阅

推荐使用第三方 github 加速工具来引用 `atom.xml`, 例如 `https://ghproxy.com/https://raw.githubusercontent.com/C4droid/syndicate/main/atom.xml`

直接使用 github raw 格式订阅 `atom.xml` , 会提示 "error minetype text/plain", 无法解析文件内容
