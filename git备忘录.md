# Linux操作备忘录

1. pwd：当前目录
2. cd： 进入（切换盘的时候要先进入其他盘
   1. 。。：返回上一级
3. mkdir：创建文件夹
4. cat：查看文件
5. mv：更改文件名



# Git备忘录

<img src="git工作流程.png" alt="Screenshot (40)" style="zoom:%;" />

1. 创建本地库：
   1. 初始化：git init
2. 设置签名：
   1. 签名分为项目与系统（项目一般不会使用
   2. git config --global user.name *
   3. git config --global user.email *
3. git status：显示工作区，缓存区状态
4. git add name：工作区上传到缓存区
   1. git rm --chached name：删除工作区/缓存区中文件
   2. git checkout：切换分支/恢复文件
5. git commit -m ‘\*’ name：缓存区上传到本地库以*为备注
6. git log --oneline:日志信息
7. git relog: 
8. git update-git-for-windows:更新git版本

## GitHub管理

1. git remote -v ：查看上传的源

2. git remote add name url:添加别名为name的远程库url

3. git.push origin master: 上传

4. git.pull:下载，合并
   
   1. 等于git.fetch(抓取)+git.master(合并)
   
   