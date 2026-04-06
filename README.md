# ProxyRules

QuantumultX & Shadowrocket 双客户端代理规则配置。

## 使用方法

### QuantumultX

长按首页右下角网络图标 → 配置文件 → 下载 → 粘贴链接：

```
https://raw.githubusercontent.com/mercuryzy/ProxyRules/main/quantumultx.conf
```

### Shadowrocket

配置 → 右上角 `+` → 粘贴远程链接：

```
https://raw.githubusercontent.com/mercuryzy/ProxyRules/main/shadowrocket.conf
```

## 策略组

| 策略 | 说明 |
|------|------|
| 🤖 AI 服务 | ChatGPT、Claude、Gemini 等 |
| 💰 Crypto | 交易所、钱包、DeFi |
| 🎮 Discord | Discord |
| 📮 电报代理 | Telegram |
| 🍎 苹果服务 | Apple 相关服务 |
| 🏦 香港金融 | 香港银行、支付工具 → 香港节点 |
| 🎥 Netflix / ▶️ YouTube / 🎵 Spotify | 流媒体 |
| 📺 国际媒体 / 🎬 港台番剧 | 流媒体通用 |
| 🪐 全球加速 | 通用代理兜底 |
| 🐟 漏网之鱼 | 未匹配流量 |

## 规则优先级

拦截（广告/隐私） → 专用策略 → 流媒体 → 通用代理 → 直连 → Final

## Disclaimer

- For personal use and educational purposes only
- No warranty of any kind, use at your own risk
