# 初始化git仓库
git init

# 添加当前目录下所有文件到git
git add .

# 添加远程路径
git remote add origin https://{username}:{password}@github.com

# 删除远程路径
git remote rm origin

# 修改远程路径
git remote set-url origin xxx

# 移除文件track索引
git rm -r --cached FILENAME

# 切换到Master分支
git checkout master

# 将develop分支合并到当前分支
git merge develop

# 自动添加所有改变并提交改变
git commit -am 'comment'

# 新建分支
git branch 分支名

# 删除分支
git branch -d 分支名

# 删除远程分支
git push origin -delete 分支名

# 提交到远程的master
git push orgin master

# 获取master
git pull orgin master

# 查看master分支历史
git reflog master

# 恢复到历史
* git reset --hard <COMMIT_ID> 或
* git reset --hard master@{1}

# 手动解决冲突
git add 冲突文件

# 打标签
git tag v1.0.0 -m '附注'

# 切换标签
git checkout [tagname]

# 删除标签
git tag -d [tagname]

# 标签发布
* git push origin [tagname] 提交一个
* git push origin -tags     提交所有

# 查看当前分之下的标签
git tag

# ssh for git
* cd ~/.ssh
* ssh-keygen -t rsa -C "your_email@youremail.com"
* clip < ~/.ssh/id_rsa.pub
* 粘贴公钥到服务器
* git remote set-url origin git@github.com:someaccount/someproject.git

# 查看commit日志
git log