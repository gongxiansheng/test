git init   创建本地仓库

git add    添加文件到版本库暂存区!

git status 查阅暂存区的文件?

git commit 提交文件到当前分支   -m 添加提交注释

git diff 比较的是工作区文件与暂存区文件的区别（上次git add 的内容）

git diff --cached 比较的是暂存区的文件与仓库分支里（上次git commit 后的内容）的区别

git diff HEAD -- filename 命令可以查看工作区和版本库里面最新版本的区别

git checkout -- filename 让文件回到最近一次git commit或git add时的状态

从版本库中删除该文件，那就先用命令git rm filename 删掉，并且git commit

git reset HEAD <file>可以把暂存区的修改撤销掉（unstage），重新放回工作区

git log    查看提交版本记录

git reflog 查看每次命令

git reset --hard HEAD^   回退到上一个版本
