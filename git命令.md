1. 创建本地分支

git branch 分支名，例如：git branch 2.0.1.20120806

注： 2.0.1.20120806是分支名称，可以随便定义。

2. 从已有的分支创建新的分支(如从master分支),创建一个dev分支

Git checkout -b dev

创建完可以查看一下,分支已经切换到dev

git branch

    * dev
    
    master

3. 切换本地分支

it checkout 分支名，例如从master切换到分支：git checkout 2.0.1.20120806

4. 远程分支就是本地分支push到服务器上。比如master就是一个最典型的远程分支（默认）。

git push origin  2.0.1.20120806

5. 提交分支数据到远程服务器

git push origin  2.0.1.20120806

6. 比如自己分支代码合并到dev分支上：

 1.先切换到dev分支，然后git pull 更新一下
 
 2.切自己分支 然后 git merge dev （意思是把dev分支代码合并到自己分支上）
 
 3.git push 提交代码上去。 如果有冲突解决冲突，解决后git add *,  然后 git commit -m '更改的内容', git push
 
 4.以上三步完成后再切到dev上
 
 5.git merge 自己分支
 
 6.git push 提交
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

