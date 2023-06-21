#### 设置用户信息

```bash
#设置用户名和邮箱
git config --global user.name "hngc"
git config --global user.email "hngc@qq.com"
#查看用户名和邮箱
git config --global user.name
git config --global user.email
```

##### 设置快捷指令

```bash
# 用于输出git提交日志
alias git-log='git log --pretty=oneline --all --graph --abbrev-commit'
# 用于输出当前目录所有文件及基本信息
alias ll='ls -al'
```