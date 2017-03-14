---
title: "node 安装"
layout: post
comments: true
---
node 版本管理1
{% highlight shell %}
brew install nvm # 安装nvm,nvm是版本管理的工具
source $(brew --prefix nvm)/nvm.sh #安装完，在shell的配置文件(例如~/.bashrc)中加入配置
nvm ls # 查看有哪些node版本
nvm install v6.10.0 #安装某个版本  
nvm alias default v6.10.0 # 设置默认的哪个版本
{% endhighlight %}
