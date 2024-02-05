# Git-learning-demo

####  创建远程仓库
在github中创建仓库，默认名如果是`main`的可以选择改为`master`

#### 克隆远程仓库
- 克隆仓库：`git clone`
- 查看当前分支：`git branch -a -v`
- 更改当前分支：`git checkout [branch]`

#### git remote
- 获取远程仓库信息： `git remote -v`
- 更新远程变更信息: `git remote update`
- 查看历史提交信息:`git log --oneline --graph`
- 合并当前分支所有提交：`git merge origin/[branch]`

#### git pull
- 拉取远程修改：`git pull origin [远程分支]:[本地分支]`

#### git push
- 推送本地修改： `git push origin [本地分支]:[远程分支]`

#### 团队开发实践
- `git add` -> `git commit`->  `git pull` -> 解决冲突 ->  `git push`