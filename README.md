# SURFPLUS 法律文档

本仓库包含 SURFPLUS 的官方法律文档，用于 Facebook 应用发布和其他合规用途。

## 📄 文档列表

| 文档 | 说明 | 状态 |
|------|------|------|
| [隐私权政策](./privacy-policy.html) | 说明如何收集、使用和保护用户个人信息 | ✅ 已完成 |
| [服务条款](./terms-of-service.html) | 规定服务使用规则和用户权利义务 | ✅ 已完成 |

## 🚀 部署到 GitHub Pages

### 方法一：使用 GitHub Actions（推荐）

本仓库已配置自动部署，推送到 `main` 分支后自动发布。

### 方法二：手动启用 GitHub Pages

1. 进入仓库 **Settings** → **Pages**
2. **Source** 选择 `Deploy from a branch`
3. **Branch** 选择 `main` / `root`
4. 点击 **Save**
5. 等待 1-2 分钟，页面将发布到：
   ```
   https://your-username.github.io/surfplus-legal/
   ```

## 📋 获取公开链接

部署完成后，您将获得以下公开链接：

| 文档 | 链接格式 |
|------|----------|
| 隐私权政策 | `https://your-username.github.io/surfplus-legal/privacy-policy.html` |
| 服务条款 | `https://your-username.github.io/surfplus-legal/terms-of-service.html` |

## ✅ Facebook 应用配置

获得链接后，前往 Facebook 开发者后台：

1. 访问 https://developers.facebook.com/
2. 选择你的应用
3. 进入 **设置** → **基本设置**
4. 填写：
   - **隐私权政策网址**：粘贴隐私政策链接
   - **服务条款网址**：粘贴服务条款链接
5. 点击 **保存更改**

## 📝 文档更新

如需更新文档：

1. 修改对应的 `.html` 文件
2. 更新文件内的"最后更新日期"
3. 提交并推送到仓库
4. GitHub Pages 将自动更新

## 📞 联系方式

如有疑问，请联系：
- 邮箱：office@surfplus.club
- WhatsApp：+66 81 052 0715

---

© 2026 SURFPLUS. All rights reserved.
