# CrodEV - 智能聊天助手

<div align="center">

<img src="https://asperai.rth3.xyz/mingcute_ai-line.png" alt="CrodEV Logo" width="100">

**🎯 简洁、智能、高效的AI聊天助手**

[![GitHub stars](https://img.shields.io/github/stars/richyhu/CrodEV?style=for-the-badge)](https://github.com/richyhu/CrodEV/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/richyhu/CrodEV?style=for-the-badge)](https://github.com/richyhu/CrodEV/network)
[![GitHub issues](https://img.shields.io/github/issues/richyhu/CrodEV?style=for-the-badge)](https://github.com/richyhu/CrodEV/issues)
[![GitHub license](https://img.shields.io/github/license/richyhu/CrodEV?style=for-the-badge)](https://github.com/richyhu/CrodEV/blob/main/LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/richyhu/CrodEV?style=for-the-badge)](https://github.com/richyhu/CrodEV/releases)

</div>

## 📋 项目简介

CrodEV 是一款功能丰富、界面现代化的智能聊天助手，支持多种AI模型，集成联网搜索和AI绘画功能，为用户提供高效、智能的对话体验。

### 🎨 设计理念

- **Gemini 风格设计**：采用现代化的深色主题，简洁优雅
- **响应式布局**：适配各种屏幕尺寸，从手机到桌面
- **流畅交互**：精心设计的动画效果和过渡
- **用户友好**：直观的操作界面，易于使用

## ✨ 核心功能

### 🤖 多模型支持

| 模型系列       | 支持模型                                                                 |
|----------------|--------------------------------------------------------------------------|
| 🔮 DeepSeek     | DeepSeek Chat、DeepSeek Reasoner ⚡                                         |
| 🌟 Qwen         | Qwen3-8B、Qwen2.5-7B-Instruct、Qwen2.5-Coder-7B 💻、Qwen2-7B-Instruct    |
| 🎯 GLM          | GLM-Z1-9B ⚡、GLM-4-9B-Chat、GLM-4-9B-0414                                 |
| 📚 InternLM     | InternLM2.5-7B-Chat                                                      |

### 🌐 联网搜索

- 实时获取最新信息
- 显示参考资料来源
- 支持打断对话
- 可手动开启/关闭

### 🎨 AI绘画

- 支持多种绘画模型
- 生成高质量图片
- 支持图片下载和查看

### 💡 高级功能

- **代码高亮**：支持多种编程语言
- **数学公式**：LaTeX 公式渲染
- **Markdown 支持**：完整的 Markdown 解析
- **实时预览**：即时显示格式化内容

### ⚙️ 个性化设置

- 自定义 API 密钥
- 调整功能开关
- 检查更新
- 隐私设置

## 🛠️ 技术栈

<div align="center">

| 类别       | 技术                                                                     |
|------------|--------------------------------------------------------------------------|
| **前端框架** | HTML5 + CSS3 + JavaScript (ES6+)                                          |
| **样式框架** | Tailwind CSS                                                             |
| **图标库**   | Font Awesome                                                             |
| **字体**     | Google Fonts (Inter)                                                     |
| **数学渲染** | KaTeX                                                                    |
| **代码高亮** | highlight.js                                                             |
| **HTTP 服务器** | Python 内置 http.server                                               |

</div>

## 🚀 快速开始

### 🔧 环境要求

- Python 3.6+（用于本地开发服务器）
- 现代浏览器（Chrome、Firefox、Safari、Edge）

### 📦 安装步骤

#### 方法 1：直接克隆仓库

```bash
# 克隆仓库
git clone https://github.com/richyhu/CrodEV.git

# 进入项目目录
cd CrodEV/chat

# 启动 HTTP 服务器
python3 -m http.server 8000

# 在浏览器中访问
# http://localhost:8000
```

#### 方法 2：下载桌面版

1. 访问 [GitHub Releases](https://github.com/richyhu/CrodEV/releases)
2. 下载对应平台的桌面版安装包
3. 安装并运行

## 📖 使用说明

### 📝 基本使用

1. 在输入框中输入您的问题
2. 选择合适的 AI 模型
3. 点击发送按钮或按 Enter 键发送
4. 可随时点击停止按钮中断 AI 输出
5. 在设置中配置 API 密钥和功能选项

### ⌨️ 快捷键

| 快捷键       | 功能                                                                     |
|--------------|--------------------------------------------------------------------------|
| `Enter`      | 发送消息                                                                 |
| `Shift + Enter` | 换行                                                                  |
| `Ctrl + /`   | 打开/关闭设置                                                            |

### ⚙️ 配置选项

#### API 配置

- 为每个模型配置独立的 API 密钥
- 支持自定义 API 端点
- 可切换不同模型提供商

#### 功能设置

- **联网搜索**：开启/关闭实时信息获取
- **敏感内容过滤**：可选的内容安全检测
- **代码高亮**：调整代码显示样式

#### 隐私设置

- 本地数据存储
- 不收集个人信息
- 隐私政策透明

## 📁 项目结构

```
CrodEV/
├── chat/                   # 网页版代码
│   └── index.html          # 主页面
├── app/                    # 桌面版代码
│   └── index.html          # 主页面
├── download/               # 下载页面
│   └── index.html          # 下载页面
├── README.md               # 项目说明文档
└── LICENSE                 # 许可证文件
```

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

### 贡献流程

1. Fork 仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

### 开发规范

- 代码风格统一
- 注释清晰
- 测试充分
- 文档完整

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 📞 联系方式

- **GitHub**：[richyhu/CrodEV](https://github.com/richyhu/CrodEV)
- **邮箱**：(mailto:richy8221@outlook.com)

## 🙏 致谢

感谢所有为项目做出贡献的开发者和用户！

<div align="center">

---

**CrodEV - 让智能聊天更便捷、更强大！**
