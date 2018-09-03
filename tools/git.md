  mkdir：         XX (创建一个空目录 XX指目录名)<\br>
   pwd：          显示当前目录的路径。<\br>
   git init ：         把当前的目录变成可以管理的git仓库，生成隐藏.git文件。<\br>
   git add XX ：      把xx文件添加到暂存区去。<\br>
   git commit -m “XX” ： 提交文件 –m 后面的是注释。<\br>
   git status：        查看仓库状态<\br>
   git diff  XX ：     查看XX文件修改了那些内容<\br>
   git log ：         查看历史记录<\br>
   git reset  --hard HEAD^ ：或者 git reset  --hard HEAD~ 回退到上一个版本<\br>
                        (如果想回退到100个版本，使用git reset --hard HEAD~100 )<\br>
   cat XX   ：      查看XX文件内容<\br>
   git reflog  ：     查看历史记录的版本号id<\br>
   git checkout -- XX ： 把XX文件在工作区的修改全部撤销。<\br>
   git rm XX  ：        删除XX文件<\br>
   git remote add origin https://github.com/RTplay/testgit.git： 关联一个远程库<\br>
   git push -u(第一次要用-u 以后不需要) origin master ：把当前master分支推送到远程库<\br>
   git clone https://github.com/RTplay/testgit.git ： 从远程库中克隆<\br>
   git checkout -b dev ： 创建dev分支 并切换到dev分支上<\br>
   git branch  ：查看当前所有的分支<\br>
   git checkout master ：切换回master分支<\br>
   git merge dev    ：在当前的分支上合并dev分支<\br>
   git branch -d dev ：删除dev分支<\br>
   git branch name  ：创建分支<\br>
   git stash ：把当前的工作隐藏起来 等以后恢复现场后继续工作<\br>
   git stash list ：查看所有被隐藏的文件列表<\br>
   git stash apply ：恢复被隐藏的文件，但是内容不删除<\br>
   git stash drop： 删除文件<\br>
   git stash pop： 恢复文件的同时 也删除文件<\br>
   git remote： 查看远程库的信息<\br>
   git remote -v ：查看远程库的详细信息<\br>
   git push origin master  ：Git会把master分支推送到远程库对应的远程分支上<\br>
