# Millay Blog

全自动博客站 - Hugo + Cloudflare Pages + OpenClaw

## 特性

- ⚡ 极速加载（Hugo 静态生成）
- 🔍 SEO 优化（Schema.org、Open Graph、Twitter Cards）
- 📱 响应式设计
- 🤖 AI 辅助写作（OpenClaw 自动化）
- 🚀 自动部署（GitHub → Cloudflare Pages）

## 技术栈

- [Hugo](https://gohugo.io) - 静态网站生成器
- [Cloudflare Pages](https://pages.cloudflare.com) - 托管与 CDN
- [OpenClaw](https://openclaw.ai) - 自动化工作流

## 本地开发

```bash
# 安装 Hugo
brew install hugo

# 克隆仓库
git clone https://github.com/millay/millay-blog.git
cd millay-blog

# 启动开发服务器
hugo server -D

# 构建
hugo --minify
```

## 自动发布流程

1. 在 Obsidian 中撰写 Markdown 文章
2. 保存到 `content/posts/` 文件夹
3. OpenClaw 自动检测并处理
4. AI 润色 + GEO 优化
5. 自动推送到 GitHub
6. Cloudflare Pages 自动部署

## 许可证

MIT License
