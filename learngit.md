# 初始化仓库
`git init`
# 将文件提交到暂存区
`git add .`
# 将暂存区内容添加到仓库
`git commit`
# 拷贝远程仓库
`git clone`
# 切换到指定分支
`git checkout [branch-name]`
# 切换到上一个分支
`git checkout -`
# 新建一个分支
`git branch [branch-name]`
# 列出所有分支(本地、远程)
`git branch   /-r/-a`
# 新建分支并指定commmit
`git branch [branch][commit]`
# 合并指定分支到当前分支
`git merge [branch]`
# 创建一个tag在当前提交
`git tag [commit]`
# 上传到远程仓库
`git push [远程主机名] [本地分支名]`
# pull 获取远程代码合并本地
`git pull`
# rebase相关操作
`git rebase main`将把 feature-branch 分支上的提交逐个应用到 main 分支上，使得 feature-branch 看起来像是在 main 分支上进行开发的一样
# 交互式Rebase
`git rebase -i HEAD~3`
rebase可以改变提交历史