# Git相关问题

## 1. Mac下由于切换github用户导致git push报错

`remote: Permission to KieranTou/CodeWithCarl.git denied to DouDouDouglas.
fatal: unable to access 'https://github.com/KieranTou/CodeWithCarl.git/': The requested URL returned error: 403`

解决方法：

`command` + `space` 聚焦搜索 `钥匙串访问`

搜索`github` 种类为 `互联网密码` 将其改为现在新的用户即可

重新设置密码时需要到GitHub申请`Personal access tokens`

如何查看项目git设置 `vim .git/config`

## 2. git commit时 committer如何默认配置？