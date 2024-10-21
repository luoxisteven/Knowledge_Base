## 初始化 Git
```bash
cd /path/to/your/project    # 进入项目目录
git init                    # 初始化 Git 仓库

git add .                   # 添加所有文件

git commit -m "Initial commit"  # 提交，并添加提交信息

git remote add origin git@github.com:luoxisteven/knowledge_base.git

git push -u origin main
```

## Pull
``` bash
# 从远程仓库获取最新的更改，并与本地分支进行合并。
# 它相当于执行了两个操作的组合：
# git fetch（从远程仓库获取最新的更新）和 git merge（将这些更新合并到当前分支）。
git pull origin main  # 从远程仓库的 main 分支拉取最新更改并合并

# 用于切换分支或恢复文件状态的命令
git checkout feature-branch  # 切换到 feature-branch 分支

```

## Push
```bash
git add .
git commit -m "***"
git push origin main
```

## Remote
```bash
#查看远程仓库
git remote -v

#修改远程仓库
git remote set-url origin git@github.com:luoxisteven/Management_System.git

```

## Others
```bash
#force push
git push -u origin main -- force 
```