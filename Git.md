## Git工作区域
- 远程仓库（Remote）
	备份代码，实现代码的远程管理

- 仓库区/本地仓库（Respository）
	确定的文件保存到仓库，成为一个新的版本，并且对他人可见

- 暂存区(Index/unStage)
	暂存已经修改的文件，最后统一提交到git仓库

- 工作区（Workspace）
	添加、编辑、修改文件	
	
## Git命令
### 新建代码库
- 在当前目录新建一个Git代码库
`git init` 

- 新建一个目录，将其初始化为Git代码库
`git init [project-name]`

- 下载一个项目
`git clone [url]`

### 配置
- 显示当前配置
`git config --list`
- 显示文件状态
`git status`

### 增加/删除文件
- 添加当前目录所有文件(work)到暂存区(index)
`git add`
- 添加指定文件到暂存区
`git add [filename]`

### 代码提交
- 提交暂存区(index)到仓库（repo）
`git commit -m [Message提交描述]`

### 分支 
- 列出所有本地分支
`git branch`

- 列出所有远程分支
`git branch -r`

### 远程同步
- 更新远程仓库
`git remote update`
- 取回远程仓库的变化，并与本地分支合并
`git pull [remote][branch]`
- 上传本地指定分支到远程仓库
`git push [remote][branch]` 
