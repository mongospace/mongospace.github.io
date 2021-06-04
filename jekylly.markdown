---
layout: page
title: jekyll
permalink: /jekyll/
---

```
https://jekyllrb.com/docs/installation/ubuntu/
https://jekyllrb.com/docs/installation/macos/   安装所需要环境ruby,

brew install ruby or sudo apt-get install ruby-full build-essential zlib1g-dev
ruby -v
gem install jekyll bundler
jekyll new myblog
jekyll b --incremental --watch # _config.yml的修改不能被自动编译
jekyll serve --livereload  #调试博客时自动刷新浏览器

_site目录是build自动生成的不需要修改.
_config.yml 定义site变量,在md里可以用site.email的方式引用
md里头部可以定义page变量,用page.title的方式引用
layout的可选项:home, page, default
.gitignore内容:这些内容不需要提交到git,这些内容会在自动编译时生成.
_site
.sass-cache
.jekyll-cache
.jekyll-metadata
vendor

https://jekyllrb.com/docs/step-by-step/03-front-matter/
```