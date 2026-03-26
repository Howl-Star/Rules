📌 Rules — Clash 分流规则集合




Rules 是一个为 Clash 代理客户端 定制的个人分流规则集合，旨在优化网络访问体验、去广告、智能分流 AI 网站流量，并提供自动测速功能。该规则集兼容多种 Clash 配置格式，易于扩展和自定义。

🔹 功能特点
🚫 去广告：过滤常见网站广告
⚡ 自动测速：优先选择延迟最低的节点
🌐 AI 分流：针对无法直连的 AI 网站流量智能转发
🛠 可扩展性强：支持自定义规则和节点组
📂 文件结构
文件名	描述
Rules_Online_Mini.ini	主规则文件，Clash 可直接使用
academic.yaml	学术网站访问优化
aimodel.yaml	AI 模型网站分流规则
clashdns.yml	DNS 优化配置
emby.yaml	Emby 媒体服务器规则
steam.yaml	Steam 平台流量优化
fuckbilibilicdn.yaml	B 站特殊 CDN 分流

⚠️ 文件名示例，具体内容请参考仓库文件。

🚀 使用方法（Clash）

在 Clash 配置文件中添加如下内容：

rules:
  - "RULE-SET,https://raw.githubusercontent.com/Howl-Star/Rules/Default/Rules_Online_Mini.ini, AI大模型"

然后保存配置并重启 Clash。

💡 注意事项
本规则以个人优化为主，无法保证覆盖所有网络环境
可根据需求修改或新增规则，实现更精细化分流
欢迎通过 issues 或 pull requests 提出改进建议
🤝 贡献指南
⭐ Star 项目
Fork 仓库
提交新的规则或优化现有配置
发起 Pull Request
📄 许可证

MIT License
