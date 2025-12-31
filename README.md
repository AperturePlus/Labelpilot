# CCF-Lens

[![CI](https://github.com/AperturePlus/CCF-Lens/actions/workflows/ci.yml/badge.svg)](https://github.com/AperturePlus/CCF-Lens/actions/workflows/ci.yml)
[![Release](https://github.com/AperturePlus/CCF-Lens/actions/workflows/release.yml/badge.svg)](https://github.com/AperturePlus/CCF-Lens/releases)
[![License](https://img.shields.io/github/license/AperturePlus/CCF-Lens)](LICENSE)
[![Version](https://img.shields.io/github/v/release/AperturePlus/CCF-Lens)](https://github.com/AperturePlus/CCF-Lens/releases)

> A powerful userscript that automatically displays CCF rankings for academic venues directly on arXiv, DBLP, and IEEE Xplore

[English](#english) | [中文](#中文)

## English

### What is CCF-Lens?

CCF-Lens enhances your academic browsing experience by automatically displaying China Computer Federation (CCF) conference and journal rankings directly on popular academic websites. No more manual lookups - see at a glance whether a paper is from a top-tier (A), high-quality (B), or recognized (C) venue.

### Key Features

**Smart Recognition** - Automatically identifies conference and journal names from paper titles and metadata, matching them against the comprehensive CCF catalog

**Multi-Site Support** - Seamlessly integrates with:
- arXiv (search, list, and abstract pages)
- DBLP (search, database, and author pages)
- IEEE Xplore (search, author, and document pages)

**Performance Optimized** - Intelligent caching system ensures fast loading without redundant API calls

**Clean & Intuitive** - Color-coded badges (gold for A, silver for B, bronze for C) blend naturally with each site's design

**Privacy Focused** - All processing happens locally in your browser, no data collection

### Installation

1. Install a userscript manager:
   - [Tampermonkey](https://www.tampermonkey.net/) (Recommended - Chrome, Firefox, Edge, Safari)
   - [Violentmonkey](https://violentmonkey.github.io/) (Chrome, Firefox, Edge)

2. Install CCF-Lens:
   - Visit [Releases](https://github.com/AperturePlus/CCF-Lens/releases)
   - Click on the latest `ccf-lens.user.js` file
   - Your userscript manager will prompt you to install

3. Start browsing - CCF badges will appear automatically!

### Usage

Once installed, CCF-Lens works automatically. When you visit supported academic sites:

- Papers from CCF-ranked venues will display colored badges
- Click on any badge to see full venue details
- Use the floating settings button to customize display preferences
- View statistics showing distribution of rankings on the current page

### Screenshots

*Coming soon - See badges in action on arXiv, DBLP, and IEEE Xplore*

### Development

Built with modern web technologies and comprehensive testing:

```bash
# Install dependencies
npm install

# Development mode with hot reload
npm run dev

# Run complete test suite (208 tests)
npm test

# Build production version
npm run build
```

**Tech Stack:**
- Vue 3 with TypeScript for robust component architecture
- Vite for fast builds and development
- Vitest with 208+ tests including property-based testing
- Fast-check for thorough edge case coverage

### Contributing

Contributions are welcome! Whether it's bug reports, feature requests, or pull requests:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure your code passes all tests (`npm test`) and follows the existing code style.

### Support

- Report bugs: [GitHub Issues](https://github.com/AperturePlus/CCF-Lens/issues)
- Feature requests: [GitHub Discussions](https://github.com/AperturePlus/CCF-Lens/discussions)
- Questions: Check existing issues or start a new discussion

### Acknowledgments

- CCF ranking data sourced from the China Computer Federation
- Inspired by the need for efficient academic literature evaluation
- Thanks to all contributors and users who provide feedback

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 中文

### CCF-Lens 是什么？

CCF-Lens 是一个强大的油猴脚本，能在 arXiv、DBLP、IEEE Xplore 等主流学术网站上自动显示 CCF（中国计算机学会）会议和期刊排名徽章。无需手动查询，一眼就能看出论文是否来自顶级（A类）、高质量（B类）或认可（C类）会议/期刊。

### 核心功能

**智能识别** - 自动从论文标题和元数据中识别会议/期刊名称，与完整的 CCF 目录进行匹配

**多站点支持** - 无缝集成以下网站：
- arXiv（搜索页、列表页、摘要页）
- DBLP（搜索页、数据库页、作者页）
- IEEE Xplore（搜索页、作者页、文档页）

**性能优化** - 智能缓存系统确保快速加载，避免重复查询

**简洁直观** - 彩色徽章（A类金色、B类银色、C类铜色）自然融入各网站设计

**注重隐私** - 所有处理均在浏览器本地完成，不收集任何数据

### 安装方法

1. 安装油猴管理器：
   - [Tampermonkey](https://www.tampermonkey.net/)（推荐 - 支持 Chrome、Firefox、Edge、Safari）
   - [Violentmonkey](https://violentmonkey.github.io/)（支持 Chrome、Firefox、Edge）

2. 安装 CCF-Lens：
   - 访问 [Releases 页面](https://github.com/AperturePlus/CCF-Lens/releases)
   - 点击最新版本的 `ccf-lens.user.js` 文件
   - 油猴管理器会提示您安装

3. 开始使用 - CCF 徽章将自动出现！

### 使用说明

安装后，CCF-Lens 会自动工作。当您访问支持的学术网站时：

- 来自 CCF 排名会议/期刊的论文会显示彩色徽章
- 点击徽章可查看完整的会议/期刊详情
- 使用浮动设置按钮自定义显示偏好
- 查看统计信息，了解当前页面的排名分布

### 屏幕截图

*即将推出 - 展示在 arXiv、DBLP 和 IEEE Xplore 上的实际效果*

### 开发指南

使用现代 Web 技术构建，配备完善的测试：

```bash
# 安装依赖
npm install

# 开发模式（支持热重载）
npm run dev

# 运行完整测试套件（208 个测试）
npm test

# 构建生产版本
npm run build
```

**技术栈：**
- Vue 3 + TypeScript 构建健壮的组件架构
- Vite 实现快速构建和开发
- Vitest 提供 208+ 测试，包括基于属性的测试
- Fast-check 确保全面的边界情况覆盖

### 贡献指南

欢迎贡献！无论是 Bug 报告、功能建议还是 Pull Request：

1. Fork 本仓库
2. 创建功能分支（`git checkout -b feature/AmazingFeature`）
3. 提交更改（`git commit -m 'Add some AmazingFeature'`）
4. 推送到分支（`git push origin feature/AmazingFeature`）
5. 开启 Pull Request

请确保您的代码通过所有测试（`npm test`）并遵循现有代码风格。

### 支持与反馈

- Bug 报告：[GitHub Issues](https://github.com/AperturePlus/CCF-Lens/issues)
- 功能建议：[GitHub Discussions](https://github.com/AperturePlus/CCF-Lens/discussions)
- 问题咨询：查看已有 issue 或发起新讨论

### 致谢

- CCF 排名数据来源于中国计算机学会
- 灵感源于高效学术文献评估的需求
- 感谢所有贡献者和提供反馈的用户

### 开源协议

本项目采用 MIT 协议 - 详见 [LICENSE](LICENSE) 文件

## 📝 License

MIT License

## 🙏 致谢

- [CCF 推荐国际学术会议和期刊目录](https://www.ccf.org.cn/Academic_Evaluation/By_category/)
- [vite-plugin-monkey](https://github.com/lisonge/vite-plugin-monkey)
