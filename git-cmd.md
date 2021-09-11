git commands
---
by seyed ali hosseini

  - 
    github: https://github.com/ali79hm
  - special thanks to [mahdi ghadami](https://github.com/mahdighadami) ♥♥♥
---
# start with git 
```shell
git init
```
## git status
this commands shows status of git for example if a file not staged or a file changed 
```shell
git status
```
## add file to git 

### add all changed files 
```shell
git add -A
```

### add special file
```shell
git add <file-name>
```

## commit

```shell
git commit -m " message "
```
if you dont write ```-m " message "``` git automaticly opens editor fot typing commit message

## see history of changes (log)

```shell
git log
```

## compare you files with git 
### compare with git head 
```shell
git diff HEAD
```
### compare with staged files
```shell
git diff --staged
```
## remove file from stage
```shell
git reset <file-name>
```
## restore file changes to last commit

```shell
git reset -<file-name>
```

