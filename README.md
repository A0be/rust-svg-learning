<div align="center">
  <img src="https://github.com/rust-lang/rust-artwork/blob/master/rust-logo/rust-logo-blk.png?raw=true" alt="Rust Logo" width="120">
  <h1>Rust 学习之旅</h1>
  <p>从零基础到高级进阶，以 SVG 动画演示 Rust 核心概念</p>
  <p>
    <a href="https://a0be.github.io/rust-svg-learning" style="text-decoration:none; background:#E44D26; color:#fff; padding:8px 16px; border-radius:4px; font-size:14px; font-family:monospace; display:inline-block;">在线预览</a>
    <a href="https://github.com/A0be/rust-svg-learning" style="text-decoration:none; background:#1C2128; color:#fff; border:1px solid #30363D; padding:8px 16px; border-radius:4px; font-size:14px; font-family:monospace; display:inline-block; margin-left:8px;">查看源码</a>
  </p>
</div>

---

## 📖 项目简介

这是一个为 Rust 语言学习者打造的可视化学习平台，通过 SVG 动画直观演示 Rust 的核心概念（如所有权、借用、生命周期等），帮助初学者快速理解 Rust 的内存安全机制。

## ✨ 主要特性

- 🎨 **SVG 动画演示**：每个核心概念都配有专属的 SVG 动画
- 📚 **完整学习路径**：从基础语法到高级特性，共 7 个学习阶段
- 🖥️ **终端工业风设计**：深色主题 + Rust 橙配色，符合程序员美学
- 📝 **代码示例演示**：配合内存可视化，展示代码执行过程
- 🔗 **官方资源链接**：包含 Rust 官方文档、书籍、GitHub 仓库推荐

## 🗺️ 学习路径

| 阶段 | 标题 | 核心概念 |
|------|------|----------|
| 1 | 基础入门 | 变量、数据类型、函数、控制流 |
| 2 | 所有权系统 | 所有权、移动、克隆、Copy Trait |
| 3 | 引用与借用 | 不可变引用、可变引用、借用规则 |
| 4 | 结构体与枚举 | 结构体、枚举、Option、Result、模式匹配 |
| 5 | 泛型与 Trait | 泛型函数、Trait 定义与实现、特征对象 |
| 6 | 生命周期 | 生命周期标注、省略规则、NLL |
| 7 | 高级特性 | 并发、异步、宏、unsafe、FFI |

## 🚀 本地使用

直接在浏览器中打开 `index.html` 即可使用，无需任何构建工具或依赖。

```bash
git clone https://github.com/A0be/rust-svg-learning.git
cd rust-svg-learning
start index.html  # Windows
open index.html   # macOS
xdg-open index.html  # Linux
```

或者使用任意本地 HTTP 服务器：

```bash
# 使用 Python
python3 -m http.server 8080
# 使用 Node.js (http-server)
http-server . -p 8080 -o
# 使用 PowerShell (Windows)
$listener = New-Object System.Net.HttpListener
$listener.Prefixes.Add('http://localhost:8080/')
$listener.Start()
```

## 📚 学习资源

### 官方资源

| 资源 | 链接 | 说明 |
|------|------|------|
| The Book | https://doc.rust-lang.org/book/ | Rust 官方入门书籍 |
| Rust by Example | https://doc.rust-lang.org/rust-by-example/ | 可运行的 Rust 代码示例 |
| Rust Reference | https://doc.rust-lang.org/reference/ | Rust 语言完整参考 |
| Rust 标准库 | https://doc.rust-lang.org/std/ | 标准库 API 文档 |
| Cargo 手册 | https://doc.rust-lang.org/cargo/ | Rust 包管理器指南 |

### 推荐仓库

| 仓库 | 链接 | 说明 |
|------|------|------|
| Rustlings | https://github.com/rust-lang/rustlings | 通过小练习学习 Rust |
| Comprehensive Rust | https://github.com/google/comprehensive-rust | Google 官方 Rust 教程 |
| Rust 设计模式 | https://github.com/rust-unofficial/patterns | Rust 设计模式集合 |

## 🎯 项目截图

### Hero 欢迎区

Ferris 螃蟹吉祥物 + 打字机效果副标题

### 学习路线图

SVG 绘制的 7 阶段学习路径

### 概念动画卡片

点击查看所有权、借用、生命周期等核心概念的 SVG 动画演示

### 代码演示区

模拟代码编辑器 + 内存可视化

## 📝 技术实现

- **纯前端实现**：无依赖，单文件 HTML + CSS + JavaScript
- **动画方案**：原生 CSS 动画 + SVG 内置动画 + requestAnimationFrame
- **响应式设计**：支持桌面端、平板端、移动端
- **字体**：Fira Code (等宽) + Noto Sans SC (中文)
- **配色**：Rust 橙 (#E44D26) + GitHub 暗色主题

## 📜 许可证

本项目使用 MIT 许可证发布，详情请查看 [LICENSE](LICENSE)。

Rust 是 Rust 基金会的商标，本项目与 Rust 基金会无官方关联。

## 🤝 贡献

欢迎通过 Issue 和 Pull Request 贡献内容、修复问题或添加新的 SVG 动画演示！

---

<div align="center">
  <p>Made with ❤️ and 🦀 by Rust enthusiasts</p>
  <p><em>“Rust: 系统级编程，内存安全，性能无限”</em></p>
</div>
