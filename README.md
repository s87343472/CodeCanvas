# CodeCanvas

[English](#english) | [中文](#chinese)

## English

CodeCanvas is a modern, elegant code beautification and sharing tool that helps developers create beautiful screenshots of their code snippets.

### ✨ Features

- 🎨 6 Beautiful themes (Midnight, Ocean, Forest, Sunset, Dawn, Candy)
- 🖼️ Window style customization (macOS, Windows, or None)
- 📏 Line numbers and whitespace visualization
- 🔧 Fully customizable:
  - Padding and border radius
  - Font size and line height
  - Background opacity
  - Word wrap options
- 📸 Export options:
  - High-quality PNG export
  - Copy to clipboard
  - Optimized file size
- 🌐 Multi-language support:
  - English
  - 中文 (Chinese)
  - 日本語 (Japanese)
  - Français (French)
  - Deutsch (German)
  - العربية (Arabic)
- 🌓 Dark/Light mode support
- ⌨️ Keyboard shortcuts
- 📱 Responsive design
- ♿ RTL language support

### 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/s87343472/codecanvas.git

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

### 🛠️ Built With

- React + TypeScript
- Tailwind CSS
- Vite
- i18next for internationalization
- Lucide Icons
- html2canvas for image export
- Prettier for code formatting

### 🌟 Coming Soon

- Syntax highlighting for all major programming languages
- More export options (Twitter, Reddit, Facebook)
- Code formatting
- History tracking
- Google Sign-in
- Share functionality

### 📝 License

This project is licensed under the MIT License.

---

## Chinese

CodeCanvas 是一个现代、优雅的代码美化和分享工具，帮助开发者创建漂亮的代码截图。

### ✨ 特性

- 🎨 6种精美主题（午夜、海洋、森林、日落、黎明、糖果）
- 🖼️ 窗口样式自定义（macOS、Windows或无边框）
- 📏 行号显示和空白可视化
- 🔧 完全可自定义：
  - 内边距和圆角
  - 字体大小和行高
  - 背景透明度
  - 自动换行选项
- 📸 导出选项：
  - 高质量PNG导出
  - 复制到剪贴板
  - 优化文件大小
- 🌐 多语言支持：
  - 英语
  - 中文
  - 日语
  - 法语
  - 德语
  - 阿拉伯语
- 🌓 深色/浅色模式支持
- ⌨️ 键盘快捷键
- 📱 响应式设计
- ♿ RTL语言支持

### 🚀 快速开始

```bash
# 克隆仓库

git clone https://github.com/s87343472/codecanvas.git

CodeCanvas 部署文档
系统要求
Node.js 18.0.0 或更高版本
npm 9.0.0 或更高版本
现代浏览器（Chrome, Firefox, Safari, Edge）
安装步骤
克隆仓库

git clone https://github.com/s87343472/CodeCanvas.git
cd CodeCanvas
安装依赖

npm install
开发环境运行

npm run dev
访问 http://localhost:5173 查看应用

生产环境构建

npm run build
构建后的文件将生成在 dist 目录下

预览生产构建

npm run preview
项目结构

CodeCanvas/
├── public/               # 静态资源
├── src/
│   ├── components/      # React组件
│   ├── i18n/           # 国际化文件
│   │   └── locales/    # 翻译文件
│   ├── pages/          # 页面组件
│   ├── App.tsx         # 应用入口
│   ├── main.tsx        # 主渲染文件
│   └── index.css       # 全局样式
├── index.html          # HTML模板
├── package.json        # 项目配置
├── tailwind.config.js  # Tailwind配置
├── tsconfig.json       # TypeScript配置
└── vite.config.ts      # Vite配置
主要依赖

{
  "dependencies": {
    "html-to-image": "^1.11.11",
    "i18next": "^23.10.1",
    "i18next-browser-languagedetector": "^7.2.0",
    "lucide-react": "^0.344.0",
    "react": "^18.3.1",
    "react-dom": "^18.3.1",
    "react-i18next": "^14.1.0",
    "react-router-dom": "^6.22.3"
  },
  "devDependencies": {
    "@types/react": "^18.3.5",
    "@types/react-dom": "^18.3.0",
    "@vitejs/plugin-react": "^4.3.1",
    "autoprefixer": "^10.4.18",
    "postcss": "^8.4.35",
    "tailwindcss": "^3.4.1",
    "typescript": "^5.5.3",
    "vite": "^5.4.2"
  }
}
环境变量配置
创建 .env 文件（可选）:


VITE_APP_TITLE=CodeCanvas
VITE_APP_DESCRIPTION=Beautiful Code Screenshots
功能特性
代码截图生成
多主题支持
暗色/亮色模式
国际化支持（英语、中文、日语、法语、德语）
响应式设计
SEO优化
部署到生产环境
静态托管 构建项目后，可以将 dist 目录部署到任何静态托管服务：
Netlify
Vercel
GitHub Pages
任何支持静态文件托管的服务器
使用 Docker（可选）
创建 Dockerfile:


FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build
EXPOSE 4173
CMD ["npm", "run", "preview"]
构建并运行容器：


docker build -t codecanvas .
docker run -p 4173:4173 codecanvas
故障排除
如果遇到依赖安装问题：

rm -rf node_modules package-lock.json
npm install
如果开发服务器端口被占用：

# 修改 vite.config.ts
export default defineConfig({
  server: {
    port: 3000  // 修改为其他端口
  }
  // ...
})
清除缓存：

npm cache clean --force
注意事项
确保 Node.js 和 npm 版本符合要求
开发时建议使用现代浏览器
生产环境部署前请进行完整的测试
定期更新依赖以修复潜在的安全问题
支持
如有问题，请访问 GitHub 仓库 提交 issue。
```

### 🛠️ 技术栈

- React + TypeScript
- Tailwind CSS
- Vite
- i18next 国际化
- Lucide Icons
- html2canvas 图片导出
- Prettier 代码格式化

### 🌟 即将推出

- 支持所有主要编程语言的语法高亮
- 更多导出选项（Twitter、Reddit、Facebook）
- 代码格式化
- 历史记录跟踪
- Google登录
- 分享功能

### 📝 许可证

本项目采用 MIT 许可证。
