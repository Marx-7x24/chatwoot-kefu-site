# Chatwoot 客服 · 官网

Chatwoot 开源自托管客服系统 —— 中文介绍与容器化部署服务官网。

## 站点说明

单页静态站点，**无构建步骤、无外部依赖**（不挂任何 CDN），克隆下来直接就能跑。

| 文件 | 说明 |
| --- | --- |
| `index.html` | 整站（内联 CSS + 原生 JS，中英双语） |

页面区块：首屏 → 技术栈 → 核心功能 → 支持渠道 → 自托管对比 → 部署方案 → 交付流程 → 常见问题 → 联系方式。

右上角「中文 / EN」可切换语言，选择会记在浏览器本地。

## 本地预览

```bash
python3 -m http.server 8899
# 浏览器打开 http://127.0.0.1:8899
```

## 部署

已接入 **Cloudflare Pages** 的 Git 集成：推送到 `main` 分支即自动构建并发布，无需手动上传。

```bash
git add .
git commit -m "update"
git push
```

## 联系方式

- Telegram：<https://t.me/chatwoot_kefu>
- 邮箱：marxkali32502@gmail.com

## 声明

Chatwoot 为 Chatwoot Inc. 发布的 [MIT 协议](https://github.com/chatwoot/chatwoot/blob/develop/LICENSE)开源项目。
本仓库为独立的第三方部署服务站点，与 Chatwoot Inc. 无隶属或代理关系。
