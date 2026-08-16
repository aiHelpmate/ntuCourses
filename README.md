# ntuCourses

将本地新增或修改的内容同步到 GitHub：

```bash
# 1. 查看变更
git status

# 2. 暂存所有变更（.DS_Store 已被 .gitignore 忽略）
git add .

# 3. 提交，message 简要描述本次改动
git commit -m "描述本次改动"

# 4. 推送到 GitHub
git push origin main
```