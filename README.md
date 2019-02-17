### 测试项目
* 第一次提交

## git 常用命令
* 初始化本地仓库
```
git init
```
* 查看状态
```
git status
```

* 查看changes
```
git diff
```
* 添加文件
```
git add filename
```
* 提交到本地仓库
```
git commit -m "commit message"
```
* 查看提交日志
```
git log
```
* 回退版本
```
git reset --hard commitId
```
* 推送到远程仓库
```
git push
```
* 推送到远程仓库某一分支
```
git push -u origin branchName
```
* 新建分支
```
git checkout -b branchName
```
* 添加upstream
```
git remote add upstream gitRepoUrl
```
* 更新代码到本地
```
git fetch upstream
```
```
* 从远程仓库同步代码到相应分支
```
git merge upstream/branchName
```
* 拉取代码
```
git pull origin gitRepoUrl
```
* 克隆代码
```
git clone gitRepoUrl
```
* cherry-pick 代码，把其他分支的修改应用到当前分支
```
git cherry-pick commitId
```
