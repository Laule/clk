git branch 查看当前分支
git branch -a 查看所有分支
git checkout [分支名]   git switch [分支名]   切换到分支
git checkout -b [分支名]   git switch -c [分支名] 创建新分支并切换



git diff [文件名]  比对文件修改的内容

#合并
在新建的分支 编写代码

完成代码后 （添加）

1、git add .  或者 git add [文件名]   添加到暂存区
2、git commit -m ' '    将指针指到这个

切换到 dev 分支

git merge lyj_dev


# 删除分支

 git branch -d dev


# 为文件改名（区分大小写）
git mv README.md readme.md


区分文件名大小写（会让服务器上保存两份代码！）
git config core.ignorecase false  