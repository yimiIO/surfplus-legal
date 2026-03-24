# 🚀 快速部署到 GitHub Pages

## 已完成 ✅

- [x] 隐私权政策 (`privacy-policy.html`)
- [x] 服务条款 (`terms-of-service.html`)
- [x] 索引页面 (`index.html`)
- [x] GitHub Actions 配置 (`.github/workflows/pages.yml`)

---

## 📋 部署步骤

### 1️⃣ 创建 GitHub 仓库

1. 访问 https://github.com/new
2. 仓库名称：`surfplus-legal`
3. 设置为 **Public**
4. **不要** 勾选 "Add a README file"
5. 点击 **Create repository**

### 2️⃣ 推送文件

在终端执行以下命令：

```bash
cd ~/.openclaw/workspace/docs/legal

# 初始化 git
git init
git branch -M main

# 添加所有文件
git add .
git commit -m "Initial commit: SURFPLUS 法律文档"

# 添加远程仓库（替换为你的用户名）
git remote add origin https://github.com/你的用户名/surfplus-legal.git

# 推送
git push -u origin main
```

### 3️⃣ 启用 GitHub Pages

1. 进入仓库 **Settings** → **Pages**
2. **Source** 选择 `GitHub Actions`
3. 等待 Actions 运行完成（约 30 秒）

### 4️⃣ 获取链接

部署完成后，页面将发布到：
```
https://你的用户名.github.io/surfplus-legal/
```

文档链接：
- 隐私政策：`https://你的用户名.github.io/surfplus-legal/privacy-policy.html`
- 服务条款：`https://你的用户名.github.io/surfplus-legal/terms-of-service.html`

---

## ✅ Facebook 应用配置

获得链接后：

1. 访问 https://developers.facebook.com/
2. 选择你的应用
3. **设置** → **基本设置**
4. 填入：
   - **隐私权政策网址**
   - **服务条款网址**
5. **保存更改**
6. 切换到 **Live** 模式

---

## 🦐 需要帮助？

遇到问题随时问我！
