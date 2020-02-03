Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.
now git.com connected

git commands:

git add readme.txt
git commit -m "xxxxx "

git status
git log
git log --pretty=oneline

git diff HEAD -- readme.txt 

设置远程地址输入以下两个命令行：
$ git remote set-url origin https:xxxxx.git
$ git push -u origin master


git remote add origin0 https://github.com/aaron-lui/learngit.git

git remote -v

git push -u origin0 master


首先，我们创建dev分支，然后切换到dev分支：

$ git checkout -b dev
Switched to a new branch 'dev'
git checkout命令加上-b参数表示创建并切换，相当于以下两条命令：

$ git branch dev
$ git checkout dev
Switched to branch 'dev'


