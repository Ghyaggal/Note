# GIT命令

#### 初始化仓库  

`git init`

***

#### 添加文件

`git add -A`添加所有内容   
`git add .`添加新文件和编辑过的文件不包括删除的文件   
`git add -u`添加编辑或者删除的文件，不包括新添加的文件

***

#### 提交到本地库

`git commit -m "提交的提示信息"`

***

#### 查看提交历史

`git log --stat`

***

#### 撤回文件

`git checkout 文件`工作区撤回  
`git reset 文件`提交后放弃更改

***

#### 分支

`git checkout -b <branchname>`冲当前节点新建分支  
`git branch`列举所有的分支  
`git checkout <branchname>`单纯地切换到某个分支  
`git branch -D <banchname>`删掉特定分支  
`git merge <branchname>`在a目录中合并b分支  

***

#### 远程仓库

`git push` 推送  
`git pull`拉取

***

#### 下载代码

`git clone ...`

***

#### VScode插件

GIT History diff











 





