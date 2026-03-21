# 速卖通HR情报中心

## GitHub Pages 部署指南

由于 GitHub 安全策略，密码验证已禁用，需要使用 Personal Access Token。

### 部署步骤：

1. **创建 Personal Access Token**
   - 访问 https://github.com/settings/tokens
   - 点击 "Generate new token (classic)"
   - 勾选 "repo" 权限
   - 生成并复制 Token

2. **使用 Token 推送**
   ```bash
   cd /Users/zhaoxing/.qoderwork/workspace/mmw1esdh93ba6l06/github-deploy
   git remote set-url origin https://zhaoxing.zhao@alibaba-inc.com:TOKEN@github.com/zhaoxing/aliexpress-hr-dashboard.git
   git push -u origin main
   ```

3. **开启 GitHub Pages**
   - 访问 https://github.com/zhaoxing/aliexpress-hr-dashboard/settings/pages
   - Source 选择 "Deploy from a branch"
   - Branch 选择 "main"
   - 保存

4. **访问链接**
   - https://zhaoxing.github.io/aliexpress-hr-dashboard/
