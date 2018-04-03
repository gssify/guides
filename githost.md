## 前言

参考(同一客户端下使用多个git账号)[https://www.jianshu.com/p/89cb26e5c3e8]

## 举例

```html
# Gitlab
Host git.company.com
   HostName git.company.com
   PreferredAuthentications publickey
   IdentityFile ~/.ssh/id_rsa_company

# Github
Host github.com
    HostName ssh.github.com
    Port 443
    PreferredAuthentications publickey
    IdentityFile ~/.ssh/id_rsa_github
    User foo

# Coding
    Host git.coding.net
    User foo@bar.com
    PreferredAuthentications publickey
    IdentityFile ~/.ssh/id_rsa_coding
```
