$git init	#把当前目录变成Git可以管理的仓库
$git add <file>
$git commit -m <message>
$git status
$git diff
$git log
$git log --pretty=oneline
$git reset --hard commit_id
$git reflog
$git diff HEAD -- readme.txt  #查看工作区和版本库里面最新版本的区别
$git checkout -- readme.txt   #把readme.txt文件在工作区的修改全部撤销
$git reset HEAD readme.txt    #把暂存区的修改撤销掉（unstage），重新放回工作区
$git rm test.txt
$git push origin master       #把本地master分支的最新修改推送至GitHub
$git remote add origin git@github.com:fucckktest21/learngit.git     #关联远程库
$git clone git@github.com:fucckktest21/gitskills.git                #克隆本地库

Creating a new branch is quick.