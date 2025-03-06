# 自用 Clash 分流规则

这是一个为 Clash 客户端设计的个人分流规则集 (`Rules_Online_Mini.ini`)，基于 ACL4SSR 格式，用于优化网络访问体验。规则集支持去广告、自动测速，并将中国境内无法访问的 AI 类网站分流至美国节点。

## 功能特点
- **去广告**：支持，拦截广告和程序相关广告。
- **自动测速**：支持，自动选择延迟最低的节点。
- **微软分流**：不支持。
- **苹果分流**：不支持。
- **增强中国IP段**：不支持。
- **增强国外GFW**：不支持。
- **AI 分流**：将中国境内无法访问的 AI 类网站路由到美国节点 (`🇺🇸.*`)。

## 使用方法
1. **获取规则集**：
   - Raw 链接：

https://raw.githubusercontent.com/Howl-Star/Rules/refs/heads/Default/Rules_Online_Mini.ini
text
- 或从仓库下载 `Rules_Online_Mini.ini` 文件。

2. **配置 Clash**：
- 在 Clash 配置文件中添加：
```yaml
rules:
  - "RULE-SET,https://raw.githubusercontent.com/Howl-Star/Rules/refs/heads/Default/Rules_Online_Mini.ini,💬 AI大模型"

    确保代理节点名称以 🇺🇸 开头（如 🇺🇸 US-Node1），以匹配美国节点。

    验证：
        访问 openai.com、x.ai 等 AI 网站，确认流量通过美国节点。
