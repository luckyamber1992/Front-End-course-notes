git是一个开源的，分布式的版本控制工具,每个人的电脑都是一个完整的仓库
每一次提交代码都会记录你对代码的改动历史
github提供了一服务器，从而让你能把仓库放到github上
git工作机制：
你在本地ide书写的代码需要保存在本地的文件夹中，该文件夹被称作为**工作区**， 工作区的代码将会通过git add 的方式暂时储存在暂存区，暂存区的代码通过git commit的方式推到本地库中（注意：一旦推送到本地库中，该代码删改都会被记录），最后通过git push的方式推送的远程仓库
## 远程库的形式
### 互联网型： github， gitee码云
### 局域网：gitlab
## git revert and git reset
如果被重置的提交只存在于本地，使用reset。但，此命令会更改提交历史记录，并且可能会覆盖远程团队成员所依赖的历史记录。
revert 是创建一个新的提交来撤消更改，因此如果要恢复的提交已经被推送到共享仓库，最好使用 revert，因为它不会覆盖提交历史。
## git merge/rebase
- git merge --squash feature
git rebase
git log nav(another branch name) -- oneline(this makes the code more readable)
git cherry-pick hashNumber(commit Id)

## git拉取特定github分支
在clone时就加上-b branch_name的操作，就可以指定分支进行拉取：
> git clone -b dev-md https://gitee.com/mindspore/mindscience.git