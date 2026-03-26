# 📌 Rules — Clash 分流规则集合

[![GitHub Repo stars](https://img.shields.io/github/stars/Howl-Star/Rules?style=social)](https://github.com/Howl-Star/Rules/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/Howl-Star/Rules)](https://github.com/Howl-Star/Rules/issues)
[![License](https://img.shields.io/github/license/Howl-Star/Rules)](https://github.com/Howl-Star/Rules/blob/main/LICENSE)

**Rules** 是一个为 **Clash 代理客户端** 定制的个人分流规则集合，旨在优化网络访问体验、去广告、智能分流 AI 网站流量，并提供自动测速功能。该规则集兼容多种 Clash 配置格式，易于扩展和自定义。

---

## 🔹 功能特点

* 🚫 **去广告**：过滤常见网站广告
* ⚡ **自动测速**：优先选择延迟最低的节点
* 🌐 **AI 分流**：针对无法直连的 AI 网站流量智能转发
* 🛠 **可扩展性强**：支持自定义规则和节点组

---

## 📂 文件结构

| 文件名                     | 描述                |
| ----------------------- | ----------------- |
| `Rules_Online_Mini.ini` | 主规则文件，Clash 可直接使用 |
| `academic.yaml`         | 学术网站访问优化          |
| `aimodel.yaml`          | AI 模型网站分流规则       |
| `clashdns.yml`          | DNS 优化配置          |
| `emby.yaml`             | Emby 媒体服务器规则      |
| `steam.yaml`            | Steam 平台流量优化      |
| `fuckbilibilicdn.yaml`  | B 站特殊 CDN 分流      |

> ⚠️ 文件名示例，具体内容请参考仓库文件。

---

## 🚀 使用方法（Clash）

在 Clash 配置文件中添加如下内容：

```yaml
rules:
  - "RULE-SET,https://raw.githubusercontent.com/Howl-Star/Rules/Default/Rules_Online_Mini.ini, AI大模型"
```

然后保存配置并重启 Clash。

---

## 💡 注意事项

* 本规则以个人优化为主，无法保证覆盖所有网络环境
* 可根据需求修改或新增规则，实现更精细化分流
* 欢迎通过 issues 或 pull requests 提出改进建议

---

## 🤝 贡献指南

1. ⭐ Star 项目
2. Fork 仓库
3. 提交新的规则或优化现有配置
4. 发起 Pull Request

---

## 📄 许可证

MIT License

Copyright (c) 2026 Howl-Star

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
