# learn-head-first-html-and-css
基于 [Jekyll][1] 构建，是对《Head First HTML 与 CSS》一书的学习总结。

[![Release](https://img.shields.io/github/release/mrzhqiang/learn-head-first-html-and-css.svg)](https://github.com/mrzhqiang/idea-helper/releases/latest)
[![Build Status](https://travis-ci.org/mrzhqiang/learn-head-first-html-and-css.svg?branch=master)](https://travis-ci.org/mrzhqiang/learn-head-first-html-and-css)

## 主题
当前使用：[just-the-docs][3]，因为它简洁、易用，对初次使用 [Jekyll][1] 非常友好。

## 在线查看
请访问：[learn-head-first-html-and-css]。

## 本地预览？
- 安装 [开发环境][4]
- 安装 [Jekyll][1]
```bash
$ gem install jekyll bundler
```
- 安装主题
```bash
$ gem install just-the-docs
```
- 开启本地预览
```bash
$ bundle exec jekyll serve
```
- 打开浏览器并访问 [http://localhost:4000](http://localhost:4000)

**注意：如果本地预览无效，请先打开 `_config.yml` 的以下注释，再执行以上操作。**
```yaml
# If you need local preview, just uncomment the line
#theme: just-the-docs
```

## 声明
**仅供学习交流使用，如有侵权或不当之处，请及时联系作者。**

[learn-head-first-html-and-css]:https://mrzhqiang.github.io/learn-head-first-html-and-css

[1]:https://jekyllrb.com/
[2]:https://www.jetbrains.com/idea/?fromMenu
[3]:https://pmarsceill.github.io/just-the-docs/
[4]:https://jekyllrb.com/docs/installation/