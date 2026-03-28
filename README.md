# Test Project
# 1. 进入本地项目目录
cd my-project
# 至少创建要给文件
echo "# Test Project" > README.md

# 2. 初始化 Git（如果还没做）
git init

# 3. 添加所有文件
git add .

# 4. 首次提交
git commit -m "初始提交"

# 5. 关联 GitHub 远程仓库（使用你的仓库地址），origin为远程仓库别名
git remote add origin https://github.com/你的用户名/my-project.git

# 6. 将本地分支重命名为 main（如果默认是 master）
git branch -M main

# 7. 推送到 GitHub
git push -u origin main