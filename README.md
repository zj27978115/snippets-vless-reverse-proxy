https://cfxr.eu.org/getSub?host=自定义域名

🔧 参数自定义说明
 1️⃣ 基础订阅参数
🔹 target=clash – 指定订阅类型
📌 用于生成特定客户端如Clash的配置
2️⃣ 优选IP设置
🌍 best=IP:端口 – 手动指定优选IP 默认为443端口
📂 示例：?best=ip.sb:443
3️⃣ Path路径自定义
🔧 通过路径参数调整代理行为：
✔️ path=/?ip=1.1.1.1 – 强制Proxy IP
✔️ path=/?s5=user:pass@host:port – SOCKS5代理 仅限当前订阅
✔️ path=/?gs5=user:pass@host:port – 全局SOCKS5代理
4️⃣ 参数组合使用
🛠 示例：?best=1.1.1.1&path=/?ip=1.1.1.1
节点数量限制：?count=数字 如 ?count=3 仅保留3个节点
📂 URL路径参数 新版格式
📌 支持路径式参数，例如：
/snippets/ip=example.com
 /snippets/nat64=2a02:898:146:64::
⚠️ 优先级：URL查询参数 大于 路径参数
💡 注意事项
🔄 订阅有效期为 24小时，建议：
✔️ 设置合理的自动更新间隔如12小时
