---
layout: post
title: 用jekyll & GitHub Page搭建blog
date: 2024-02-22 02:35 +0800
category: [假物集]
tags: [jekyll]
img_path:
---

#### 安装jekyll

```
# 在 MacOS 用 brew 安装 ruby
brew install ruby
echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc

# 用 gem 安装 jekyll 与官方建议的 bundler
gem install jekyll bundler

# 在当前路径下初始化一个项目
jekyll new blogtest

# 安装gemfile中的依赖
cd blogtest
bundle install
# 开启服务
jekyll serve
```

#### 搭建Github Pages

[github page](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)

#### 使用Chirpy主题

[chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)

