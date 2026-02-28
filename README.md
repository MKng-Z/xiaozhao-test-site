# GitHub Pages 部署指南

## 项目信息

- **仓库地址：** https://github.com/MKng-Z/xiaozhao-test-site
- **网站地址：** https://mkng-z.github.io/xiaozhao-test-site/
- **本地路径：** `/root/.openclaw/workspace/test-site/`

## 部署步骤

### 1. 代码已推送到 GitHub
```bash
cd /root/.openclaw/workspace/test-site
git push origin master
```

### 2. GitHub Pages 已启用
- 分支：`master`
- 路径：`/`
- 自动 HTTPS：✅

### 3. 更新网站内容
```bash
# 修改 index.html
cd /root/.openclaw/workspace/test-site
# 编辑文件...

# 提交并推送
git add .
git commit -m "更新内容"
git push origin master

# 等待 1-2 分钟让 GitHub Pages 重新构建
```

## 项目文件

- `index.html` - 主页面
- `package.json` - 项目配置（含 gh-pages 脚本）
- `.gitignore` - 忽略 node_modules

## 未来增强

可以添加的功能：
- [ ] 自定义域名
- [ ] GitHub Actions 自动部署
- [ ] 更多页面和样式