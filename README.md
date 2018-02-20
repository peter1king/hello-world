[![Build Status](https://travis-ci.org/peter1king/hello-world.svg?branch=master)](https://travis-ci.org/peter1king/hello-world)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/peter1king/hello-world/blob/master/LICENSE)
# 我使用GIT时常用到的命令
## 1.配置
- [x] 增加配置项
``` git
git config alias.co checkout
```
- [x] 移除配置项
```git
git config --unset alias.co
```
- [x] 带```--global```参数时指定为全局配置，否则为当前git特有配置

- [x] 常用全局配置列表
```
# 用户名
user.name=peter.e.king
# 用户邮箱
user.email=star.yp@gmail.com
# 显示状态颜色
color.ui=true
# 解决文件名是中文时显示乱码的问题
core.quotepath=false
# 增加快速打时间戳标签的别名
alias.datetag=!git tag `date "+%Y%m%d%H%M"`
# 增加查看日志记录的别名
alias.lg=log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
```
