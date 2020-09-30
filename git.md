# git（暂存区：stage 本地仓库：master）
1. git是一个开源的分布式版本控制系统，git版本库可以在每一个git用户上。git管理的是修改而不是文件
2. svn是集中式的版本控制系统，svn的版本库是在中央服务器上
# git常用命令（本地仓库）
1. git init 
（初始化：命令把这个目录变成Git可以管理的仓库）
2. git add 文件路径
（把文件提交到暂存区,git add .是把目录下的所有文件都提交到暂存区）
3. git commit -m "描述提交信息（便于以后维护）"（提交到本地仓库）
4. git status 
（）
5. git log
（提交日志）
6. git reflog
（记录你的每一次命令，如果关闭vscode再打开没有之前的日志就用这条命令找回以前的版本）
7. git reset --hard HEAD^或git reset --hard 版本号
（版本号就是git log以后前面的一串字符，选前n个即可）
8. git diff HEAD --readme.txt
（查看工作区和版本库里面最新版本的区别）
9. git restore 文件路径
（）
10. git rm
(用于删除一个文件)