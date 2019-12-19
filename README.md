# Laijun's personal wiki
[![Build Status](https://travis-ci.org/mlj1991/gitbook-wiki.svg?branch=master)](https://travis-ci.org/mlj1991/gitbook-wiki)

用来进行个人知识的沉淀与管理

[Laijun's personal wiki](https://wiki.menglaijun.com/) generate by [gitbook](https://www.gitbook.com/)


# Deploy
使用`.travis.yml`进行自动部署

## Token
创建一个`Personal access tokens`，然后加密以后告知`travis-ci`
```
travis encrypt GITHUB_TOKEN=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx --add
```
