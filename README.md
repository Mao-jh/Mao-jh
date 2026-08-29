# 你好，我是 Mao-jh 👋

独立开发者。主线：做「**AI 对话里直接用、按次付费**」的垂直预审工具（支付宝 AI 收 · A2M/402 按量付费，2026-12-31 前个人 0 费率）；副线：Rust 效率工具。

## 💰 按次付费 AI Skill 矩阵

每个仓库 = 一个可**一句话安装**的 AI Skill：对话里说出需求 → 内置的支付宝官方支付流程弹码 → 扫码付款 → 自动返回带**编号依据**的风险预审报告。装完即用，无订阅、无隐藏费用。

| Skill | 一句话场景 | 定价 |
|---|---|---|
| [港卡开户·拒批风险预审](https://github.com/Mao-jh/hk-bank-precheck) | 内地人开香港银行账户，会被拒吗、材料齐不齐 | ¥4.99/次 |
| [香港身份续签·风险预审](https://github.com/Mao-jh/hk-visa-renewal) | 高才/优才/IANG 续签，断签风险与两址两单 | ¥2.99/次 |
| [优才高才申请·获批画像预审](https://github.com/Mao-jh/hk-talent-apply) | 高才 A/B/C、优才申请资格与收入口径 | ¥4.99/次 |
| [境外所得申报·CRS风险预审](https://github.com/Mao-jh/crs-tax-precheck) | 炒港美股/港险要报税吗、CRS 查得到吗 | ¥4.99/次 |
| [留服认证·拒批风险预审](https://github.com/Mao-jh/cscse-precheck) | 留学生学历认证，出境天数/网课/院校名单雷点 | ¥3.99/次 |
| [抖音小店报白·驳回风险预审](https://github.com/Mao-jh/dy-shop-baibai) | 报白一直被驳回？经营范围/授权链/资质自查 | ¥2.99/次 |
| [留学生落户·资格风险预审](https://github.com/Mao-jh/haigui-settle) | 落户上海的社保红线、回国两年窗口怎么算 | ¥2.99/次 |
| [港险投保·健康告知预审](https://github.com/Mao-jh/hk-insurance-disclosure) | 体检有结节能买港险吗、问卷没问要不要说 | ¥3.99/次 |
| [竞业限制协议·被诉风险预审](https://github.com/Mao-jh/non-compete-precheck) | 竞业协议有约束力吗、违约金百万怎么办 | ¥4.99/次 |
| [房贷征信·拒批风险预审](https://github.com/Mao-jh/mortgage-credit-precheck) | 网贷影响房贷吗、申请前怎么修复征信 | ¥3.99/次 |

安装示例：

```bash
git clone https://github.com/Mao-jh/hk-bank-precheck.git ~/.claude/skills/hk-bank-precheck
```

> 开发者想给自己的 API / Skill / MCP 接同款「按量付费」：
> `npx -y @alipay/alipay-aipay@latest install`（支付宝官方 AI 付引导：签约入驻 + 集成 + 沙箱）

## 🧰 其他项目

- [Ocli](https://github.com/Mao-jh/Ocli) — 通过 Chrome DevTools Protocol 远程控制 OpenCode Desktop 的 CLI（Rust，已发布 crates.io）

---

*付费能力来自支付宝 AI 收（A2M/402）：调用返回 402 账单 → 用户支付宝授权 → 服务端验付 → 履约交付。所有工具均为风险预审（顾问位），不构成「必过/必拒」保证。*
