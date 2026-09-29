
| 使用场景 | 推荐入口 | 说明 |
|---|---|---|
| Clash Party / Mihomo Smart | `Clash Party/ClashParty(mihomo-smart).js` | Smart 内核 + LightGBM 择路；消费最终融合规则集 |
| Clash Party 普通内核 / FlClash | `Clash Party/ClashParty(mihomo).js` / `FlClash/FlClash(mihomo).js` | 同规则语义，区域组选 `url-test` |
| Android Mihomo | `Clash Meta For Android/CMFA(mihomo).yaml` | CMFA 是同步产物，不是规则基准 |
| Stash | `Stash/Stash.yaml` | 从 CMFA 自动裁剪生成，保持 Clash Premium 兼容 |
| sing-box / Hiddify / HomeProxy | `SingBox/SingBox(sing-box)-full.json` | 使用 `.srs` 融合规则集 |
| v2rayN Xray | `v2rayN/v2rayN(xray).json` | 从 69 个非空 fused sing-box JSON 展平成 89 条 Xray RuleObject |
| iOS / macOS 其他客户端 | `Egern/`、`Shadowrocket/`、`Surge/`、`Loon/`、`Quantumult X/` | 按各 APP 原生语法同步 |
| OpenWrt | 优先 `OpenClash/`，Passwall / Passwall2 作为降级参考 | Passwall 系使用 69 条非空 fused `.srs` shunt rule |


## 📄 免责声明

本仓库是一个**纯技术自用学习项目**— 所有配置文件仅供**个人技术研究与学习**，请勿用于违反所在地法律法规的用途。使用前请确认符合当地法律，风险自担。


