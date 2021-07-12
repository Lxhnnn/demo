---------下载git.exe

---------命令行
# 切换目录
cd 
# 创建仓库
git init
# 查看状态
git status
# 查看分支
git branch
# 创建分支
git branch testing
# 切换分支
git checkout testing
# 添加所有到本地仓库
git add --all
git add .
# 单个文件
git add README.md
# 提交
git commit -m '第一次版本提交'
# 显示所有远程
git remote -v
# 删除远程
git remote rm origin
# 关联
git remote add origin https://github.com/Lxhnnn/demo.git
# 推送
git push origin master


---------报错
error: src refspec master does not match any
git add .
git commit -m '第一次版本提交'
git push origin master