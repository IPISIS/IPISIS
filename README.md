# 1. 初始化 Git 仓库
git init

# 2. 添加文件到 Git 暂存区
git add 生日.html

# 3. 提交更改
git commit -m "Add 生日.html"

# 4. 添加远程仓库
git remote add origin https://github.com/IPISIS/IPISIS.git
# 替换 URL 中的 IPISIS 为您的 GitHub 用户名和仓库名称

# 5. 推送到远程仓库的 master 分支
git push -u origin master
