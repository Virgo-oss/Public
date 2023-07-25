# 提交到 Github
git remote add origin git@github.com:Virgo-oss/Blood.Dream.git

# 提取远程仓库
1、在网站上更新编辑记录后使用以下命令：
git fetch
git merge

2、本地对应文件将被更新。

# 本地文件上传到 Github
1、项目完成后执行命令，添加要上传的文件：
添加全部文件：git add .
添加一个文件：git add <文件名>

2、执行提交命令：
git commit -m "描述信息(例如：添加 ** 文件)"
3、执行上传命令：

git push origin <branch> (默认为master)

# 从远程仓库拉取文件，使用克隆命令
git clone + 远程项目地址（HTTP地址或SSH地址）

# 删除仓库
git remote rm origin
