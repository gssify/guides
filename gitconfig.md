## 前言

简化 Git 命令，提高操作效率。

## 配置

```
[color]
  ui = auto
  diff = auto
  branch = auto
  status = auto
[alias]
  ci = commit
  st = status
  br = branch
  unstage = reset HEAD --
  pullrb = pull --rebase
  fetchv = fetch -v
  al = add -vA
  co = checkout
  histo = log --graph --decorate --oneline
[core]
  editor = vim
  quotepath = false
  autocrlf = falsefilemode = false
[gui]
  encoding = utf-8
  eccoding = utf-8
[i18n "commit"]
  encoding = utf-8
```
