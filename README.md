###  本地开发
# 1. 进入项目目录
cd next-daily-hot

# 2. 安装依赖
pnpm install

# 3. 启动开发服务器
pnpm dev

# 构建生产版本
pnpm build

# 启动生产服务器
pnpm start

# 代码检查
pnpm lint

# 更新版本
pnpm release

### 💡 功能建议

- 通过 Issues 提出新功能建议
- 描述功能的使用场景和预期效果
- 欢迎提供设计思路和实现方案

### 📝 添加新平台

如果你想添加新的热点平台支持：

1. 在 `src/app/api/` 目录下创建新的路由文件
2. 实现数据获取逻辑
3. 添加对应的图标到 `public/` 目录
4. 更新 README.md 中的平台列表
5. 提交 PR 并说明新平台的特点

## ⚠️ 免责声明

> ⚠️ **重要提醒：请仔细阅读以下声明**

### 📋 使用条款

1. **数据来源**：本项目通过公开 API 和网页抓取获取数据，仅供学习和研究使用
2. **合规使用**：用户需遵守各平台的使用条款和相关法律法规
3. **商业使用**：禁止将本项目用于任何商业用途
4. **数据准确性**：不保证数据的实时性和准确性

### 🛡️ 责任限制

- 本项目仅供技术研究和学习交流使用
- 任何因使用本项目产生的法律风险由使用者自行承担
- 如有平台方要求移除相关接口，请及时联系我们处理
- 项目维护者不承担任何直接或间接的损失责任


## 📄 许可证

本项目基于 [MIT 许可证]( LICENSE) 开源。

## 🙏 致谢

### 💖 开源项目

感谢以下开源项目为本项目提供的灵感和支持：

- [imsyy/DailyHot](https://github.com/imsyy/DailyHot) - 原始项目灵感来源
- [imsyy/DailyHotApi](https://github.com/imsyy/DailyHotApi) - API 设计参考
- [Next.js](https://nextjs.org/) - 强大的 React 框架
- [Tailwind CSS](https://tailwindcss.com/) - 优秀的 CSS 框架
- [HeroUI](https://www.heroui.com/) - 现代化的 Next.js UI 库

### 🏆 贡献者

感谢所有为项目做出贡献的开发者们！

<a href="https://github.com/baiwumm/next-daily-hot/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=baiwumm/next-daily-hot" alt="贡献者"/>
</a>

---
