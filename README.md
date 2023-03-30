# git_practice

Git 常用命令：
1. git init & git clone 工程准备
2. git add/rm/mv 新增/删除/移动文件到暂存区
3. git diff 比较差异
4. git status 显示工作目录和暂存区的状态
5. git commit -m "commit message" 将暂存区的文件改动提交到本地版本库
6. git log 查看日志
7. git push origin branch_name 推送至远端
8. git branch 查看本地工程的所有git分支名称（*表示当前工作区所在分支）
   git branch -r 查看远端服务器上的分支
   git branch -a 查看远端服务器和本地工程所有的分支
   git branch -d/D branch_name 删除本地分支（D表示强制删除）
9. git checkout -b branch_name 新建分支后自动切换到新分支
   git checkout 切换分支
10.git pull origin remote_branch:local_branch 从远端服务器获取某个分支的更新，再与本地指定的分支进行自动合并
11.git fetch origin remote_branch:local_branch 从远端服务器中获取某个分支的更新到本地仓库（与git pull不同，不会进行git merge合并操作）
12.git merge branch_name 从指定分支合并到当前分支
13.