# 🚀 一键部署命令

## 📋 步骤 1：创建 GitHub 仓库

在浏览器打开：**https://github.com/new**

- 仓库名称：`surfplus-legal`
- ✅ Public
- ❌ 不要勾选 "Add a README file"
- 点击 **Create repository**

---

## 📋 步骤 2：执行部署命令

复制以下所有命令，在终端一次性执行：

```bash
# 进入法律文档目录
cd ~/.openclaw/workspace/docs/legal

# 初始化 git
git init
git config user.email "berniezhang428@gmail.com"
git config user.name "SURFPLUS"
git branch -M main
git add .
git commit -m "Initial commit: SURFPLUS 法律文档 🦐"

# 添加远程仓库
git remote add origin https://github.com/berniezhang428/surfplus-legal.git

# 推送（会提示输入密码）
git push -u origin main
```

**推送时认证**：
- 用户名：`berniezhang428`
- 密码：**Personal Access Token**（不是邮箱密码）

---

## 🔑 获取 Personal Access Token

1. 访问：https://github.com/settings/tokens
2. 点击 **Generate new token (classic)**
3. 填写 Note：`surfplus-legal-deploy`
4. 勾选权限：✅ **repo** (全选)
5. 点击 **Generate token**
6. 复制 Token（只显示一次！）

---

## 📋 步骤 3：启用 GitHub Pages

推送成功后：

1. 访问：https://github.com/berniezhang428/surfplus-legal/settings/pages
2. **Source** 选择 **GitHub Actions**
3. 等待 30 秒自动部署

---

## ✅ 完成后的链接

```
主页：https://berniezhang428.github.io/surfplus-legal/
隐私政策：https://berniezhang428.github.io/surfplus-legal/privacy-policy.html
服务条款：https://berniezhang428.github.io/surfplus-legal/terms-of-service.html
```

---

## 📘 Facebook 应用配置

拿到链接后：

1. https://developers.facebook.com/
2. 选择你的应用
3. **设置** → **基本设置**
4. 填入：
   - 隐私权政策网址：`https://berniezhang428.github.io/surfplus-legal/privacy-policy.html`
   - 服务条款网址：`https://berniezhang428.github.io/surfplus-legal/terms-of-service.html`
5. **保存更改**
6. 切换到 **Live** 模式

---

🦐 完成！
