# Learn Git

------------------------
克隆：`git clone [url]`

----------------
add: `git add *`
commit: `git commit -m 'note'`
push: `git push`

----------------
查看文件状态：`git status`

-------
查看本地分支：`git branch`
查看远程分支：`git branch -r`
创建本地分支：`git branch [name]` ----注意新分支创建后不会自动切换为当前分支
切换分支：`git checkout [name]`
创建新分支并立即切换到新分支：$ git checkout -b [name]

------------
```
git branch tree
git checkout tree
git add *
git commit -m '' //单引号内不能为空，否则无法commit
git push --set-upstream origin tree  //提交远程不存在的分支
```