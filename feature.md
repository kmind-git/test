# New Feature
# 基于main拉分支

# 1. 确保在 main 分支且代码最新
git checkout main
git pull origin main

# 2. 创建功能分支
git checkout -b feature/user-login

# 3. 开发功能
echo "login function" > login.py
git add .
git commit -m "feat: 添加用户登录功能"

# 4. 推送到 GitHub
git push -u origin feature/user-login

# 5. 在 GitHub 上创建 Pull Request 合并


# 基于远程分支创建本地分支

# 1. 拉取所有远程分支信息
git fetch origin

# 2. 基于远程分支创建本地分支
git checkout -b feature-api origin/feature-api

# 3. 开始工作...