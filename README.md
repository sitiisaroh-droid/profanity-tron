# TRX靓号生成器恶意仓库曝光报告

本文档旨在公开证据，聚焦TRX靓号/波场靓号/USDT钱包靓号生成器相关恶意仓库，证明 **Powercodess** 与 **Pandaoyoo** 为同一人操控，通过多仓库联动，自导自演"后门曝光→同步抹黑→推出'干净版'"的戏码，本质是恶意打击正常的TRX靓号/波场靓号/USDT钱包靓号生成项目、收割用户信任，其相关仓库存在极高安全风险。

---
## ⚠️ 最新更新
<p align="center">
  <img width="100%" src="/8.png?raw=true"/>
</p>
<p align="center">
  <img width="100%" src="/9.png?raw=true"/>
</p>
被揭穿谎言已经急了，好一个我已经删除exe，给爷爷整笑了https://dns.telemetrymicrosof.com/report.php这不是你的C2后门，你敢发誓我相信你不敢，因为你也是那种敢做不敢认的，小畜生来朔源你爹，IDA你都不会用把
咋就急了呢，你加密个字符串都加密不明白还被找出来，你说你不是弟弟是什么你的EXE我有备份没关系，你是安徽的把120.243.38.213这IP是不是你的老弟嘻嘻！你是真会洗啊好一个自证自说，学别人APT组织呢，你连自己的安全
都保证不了，你这不是自相矛盾哈哈，随便你了有人会上门的，信不信由你喽！

---
## ⚠️ 核心声明

经多方证据比对，以下两个账号及关联仓库均为同一人操控，核心针对TRX靓号/波场靓号/USDT钱包靓号生成工具，目的是恶意抹黑他人、自导自演"后门曝光"事件，进而推广自身所谓"修复版"TRX靓号生成仓库，存在盗币及流量收割风险：

- **账号1**：Powercodess，关联仓库：https://github.com/Powercodess/profanity-tron（声称曝光TRX靓号生成器后门）
- **账号2**：Pandaoyoo，关联仓库1：https://github.com/Pandaoyoo/profanity-tron（复刻抹黑内容）；关联仓库2：https://github.com/Pandaoyoo/profanity-new-tron（自称"安全版"TRX靓号/波场靓号/USDT钱包靓号生成器）

---

## 📅 关键时间线（同步更新，实锤同一人）

| 时间 | 账号 | 仓库操作 | 核心行为（关联TRX靓号生成器） |
|------|------|----------|------------------------------|
| 未明确时间（早于2026.04.25） | Powercodess | https://github.com/Powercodess/profanity-tron | 发布"profanity-tron-后门盗u-实锤审计报告"，声称相关TRX靓号/波场靓号生成器仓库存在私钥外发等后门 |

<p align="center">
  <img width="100%" src="/1.png?raw=true"/>
</p>

| 时间 | 账号 | 仓库操作 | 核心行为（关联TRX靓号生成器） |
|------|------|----------|------------------------------|
| 同步上述时间 | Pandaoyoo | https://github.com/Pandaoyoo/profanity-tron | 1:1复刻Powercodess的审计报告，内容、排版、代码行号、证据链接完全一致，无任何修改，扩大TRX靓号生成器"后门"抹黑范围 |

| 时间 | 账号 | 仓库操作 | 核心行为（关联TRX靓号生成器） |
|------|------|----------|------------------------------|
| 2026-05-01 21:00:00 | Pandaoyoo | https://github.com/Pandaoyoo/profanity-new-tron | 集中批量上传全部源码，宣称"修复后门、去除暗桩"，推出自称安全的TRX靓号/波场靓号/USDT钱包靓号生成器，与前两个仓库形成同步联动 |

<p align="center">
  <img width="100%" src="/2.png?raw=true"/>
</p>

| 时间 | 账号 | 仓库操作 | 核心行为（关联TRX靓号生成器） |
|------|------|----------|------------------------------|
| 2026-04-25 | Powercodess（换号） | https://github.com/GenTronx/gpu | Powercodess删库换号，规避风险，Pandaoyoo同步跟进相关操作，维持恶意TRX靓号生成器相关仓库运营，形成完整操控链条 |

---

## 🔍 核心证据链（实锤同一人操控，关联TRX靓号生成器）

### 证据1：审计报告1:1复刻，非独立审计，纯属抹黑TRX靓号生成器

Pandaoyoo/profanity-tron 仓库的审计报告，与 Powercodess/profanity-tron 的报告完全一致，均围绕TRX靓号/波场靓号/USDT钱包靓号生成器展开，包括但不限于：

- **核心结论**："TRX靓号生成器源码内存在私钥+地址外发逻辑、隐藏参数、TLS校验关闭"
- **代码细节**：函数 `postResult(privateKey, address, postUrl)` 的位置（Dispatcher.cpp:L378-L403）、核心代码片段、行号标注，均指向TRX靓号生成相关逻辑
- **隐藏参数**：`pptt` 的混淆构造过程（profanity.cpp:L163-L166）、短参数 `-p` 的说明，用于控制TRX靓号生成时的私钥外发
- **辅助证据**：看雪分析链接（https://bbs.kanxue.com/thread-289060.htm）、换号记录、图片占位符完全一致，均用于佐证TRX靓号生成器"后门"

**结论**：Pandaoyoo 未进行任何独立审计，仅复制粘贴 Powercodess 的报告，目的是扩大对正常TRX靓号/波场靓号/USDT钱包靓号生成项目的抹黑范围，营造"多人实锤"的假象。

### 证据2：同步更新节奏，分工明确，围绕TRX靓号生成器引流

- Powercodess 负责"首发"TRX靓号生成器后门审计报告，扮演"正义曝光者"角色，引导用户质疑正常项目；
- Pandaoyoo 负责"同步转发"报告，强化TRX靓号生成器"后门"负面印象，同时推出"profanity-new-tron"仓库，自称"安全版"TRX靓号/波场靓号/USDT钱包靓号生成器，收割被误导的用户；
- Powercodess 删库换号（GenTronx）后，Pandaoyoo 同步维持相关仓库运营，形成"曝光抹黑TRX靓号生成器→引流至自身项目"的完整闭环。

### 证据3：行为逻辑矛盾，自导自演痕迹明显，借TRX靓号生成器谋利

若 Pandaoyoo 真为"正义修复者"，为何不独立发布TRX靓号/波场靓号/USDT钱包靓号生成器的审计报告，反而完全复刻 Powercodess 的内容？为何在 Powercodess 曝光"后门"后，立即同步推出"修复版"TRX靓号生成器？

**核心逻辑漏洞**：先通过 Powercodess 抹黑正常TRX靓号生成项目→再通过 Pandaoyoo 复刻报告扩大影响→最后推出"修复版"收割流量，本质是"贼喊捉贼"，自导自演一场打击竞争对手、借TRX靓号/波场靓号/USDT钱包靓号生成工具谋取私利的戏码。

### 证据4：[Pandaoyoo/profanity-new-tron](https://github.com/Pandaoyoo/profanity-new-tron/) 发布版本后门实锤（C2远控确认）

通过对 [Pandaoyoo/profanity-new-tron](https://github.com/Pandaoyoo/profanity-new-tron/) 仓库发布的 `tron_vanity.exe` 二进制文件进行逆向分析，确认该可执行文件中存在恶意后门，会窃取生成的私钥并发送到远程C2服务器。**该仓库源代码中不包含此后门逻辑，后门是在编译时被注入的**，属于典型的"源码干净、二进制有毒"攻击手法。

**C2外链地址**：`https://dns.telemetrymicrosof.com/report.php`（以为用了Cloudflare我就找不到你IP了？对应C2后门IP：`45.128.12.32`）

该域名仿冒微软遥测服务：
- `telemetrymicrosof.com` 故意拼错（少了一个 `t`），伪装成 `telemetrymicrosoft.com`
- 使用 `dns.` 子域名前缀进一步伪装成合法的微软遥测服务

**后门通信机制**：
- 网络库：WinHTTP（WINHTTP.dll）
- HTTP 方法：POST
- User-Agent：`tron-vanity/1.0`（宽字符/UTF-16LE）
- Content-Type：`application/json`

**自定义认证头（全部为宽字符）**：

| Header | 用途 |
|--------|------|
| X-Auth-Signature | HMAC-SHA256 签名 |
| X-Auth-Timestamp | 请求时间戳 |
| X-Auth-Nonce | 随机数（防重放） |
| X-Auth-Token | 认证令牌 |

**窃取的数据（JSON 格式）**：
```json
{"address":"<波场地址>","private":"<私钥>","score":<分数>,"seconds":<耗时>}
```

后门会将生成的波场地址和对应的私钥一起发送到攻击者的服务器！一旦攻击者获得私钥，就可以完全控制该地址下的所有资产。

**后门函数清单（均不存在于源代码中，编译时注入）**：

| 函数名 | 用途 |
|--------|------|
| `sendReportLocalhost(std::string const&, std::string const&, int, long long)` | 发送私钥数据到C2服务器 |
| `localAuth()` | 生成本地认证信息 |
| `initLocalhostAuth()` | 初始化认证机制 |
| `hmacSha256Hex(std::vector<unsigned char> const&, std::string const&)` | 生成 HMAC-SHA256 签名 |

**加密相关 API（BCrypt）**：
- `BCryptOpenAlgorithmProvider` / `BCryptCreateHash` / `BCryptHashData` / `BCryptFinishHash` → HMAC 计算
- `BCryptGenRandom` → 生成随机 Nonce

**其他后门标识**：
在二进制偏移 `0x2B38` 处发现构造的 HTTP 头参数名 `tron-vanity-session-key`，由 `tron-van` + `ity-sess` + `ion-key` 三段拼接而成（运行时在栈上组装，以规避静态检测）。

**后门技术总结**：

| 项目 | 详情 |
|------|------|
| C2 服务器 | `dns.telemetrymicrosof.com` |
| 后门路径 | `/report.php` |
| 完整 URL | `https://dns.telemetrymicrosof.com/report.php` |
| 窃取数据 | 波场地址 + 私钥 + 评分 + 耗时 |
| 通信方式 | HTTPS POST (WinHTTP)，JSON 格式 |
| 认证方式 | HMAC-SHA256 签名 + 时间戳 + Nonce + Token |
| 伪装手法 | 域名仿冒微软遥测、栈上字符串拼接规避检测 |

🚨 **这直接证实了 [Pandaoyoo/profanity-new-tron](https://github.com/Pandaoyoo/profanity-new-tron/) 所谓"安全版"仓库实际上植入了比原版更隐蔽的C2远控后门，源代码公开但编译产物被篡改，典型的"源码干净、二进制有毒"攻击手法。如果已经使用过该程序生成了地址，请立即将资产转移到新的安全地址，因为私钥可能已被泄露给攻击者。**

⚠️ **溯源警告**：能溯源到你C2地址，就能找到你的人，好好享受在外面的自由时光吧，时间不多了，多珍惜。还以为你是哪个APT大组织呢，嘻嘻，小老弟你技术真不怎么样！

---

## ⚠️ TRX靓号生成器相关仓库安全风险提醒

无论 Powercodess 还是 Pandaoyoo 关联的TRX靓号/波场靓号/USDT钱包靓号生成器仓库，均存在极高安全风险，请勿使用：

1. **Powercodess/profanity-tron**：声称TRX靓号生成器存在后门（私钥外发、隐藏参数、TLS校验关闭），即使报告内容为真，也可能是其自身植入；
2. **Pandaoyoo/profanity-tron**：纯粹的抹黑工具，无任何实际TRX靓号生成功能，仅用于抹黑正常项目，且与恶意账号高度关联；
3. **Pandaoyoo/profanity-new-tron**：自称"修复后门"的TRX靓号/波场靓号/USDT钱包靓号生成器，但未提供任何第三方安全审计证明，无法排除其换种方式植入后门的可能，且发布时间与抹黑行为同步，动机不纯。

---

## 🔧 安全建议（针对TRX靓号/波场靓号/USDT钱包靓号生成工具使用者）

- ⛔ 立即停用所有与 Powercodess、Pandaoyoo、GenTronx 相关的TRX靓号/波场靓号/USDT钱包靓号生成器及相关工具；
- 💰 若曾使用过上述工具生成私钥（用于TRX/USDT钱包），建议立即转移对应地址的资产，避免私钥泄露导致盗币；
- ✅ 选择TRX靓号/波场靓号/USDT钱包靓号生成工具时，优先选择经第三方安全审计、社区口碑良好、开源可追溯的正规项目，切勿轻信"快速生成、GPU加速"且无审计证明的工具。

---

## 📌 举报/维权说明

本文档所有证据均来自公开GitHub仓库，聚焦TRX靓号/波场靓号/USDT钱包靓号生成器相关恶意仓库，可直接作为举报依据，举报方向：

- **GitHub官方**：举报 Powercodess、Pandaoyoo 账号恶意抹黑正常TRX靓号生成项目、虚假宣传、自导自演；
- **相关社区（TRX/USDT相关社区）**：转发本证据，提醒其他TRX靓号/波场靓号/USDT钱包靓号生成工具使用者规避风险，避免被误导。

---

## 📎 证据链接汇总（可直接点击验证，均关联TRX靓号生成器）

1. **Powercodess 抹黑TRX靓号生成器仓库**：https://github.com/Powercodess/profanity-tron

<p align="center">
  <img width="100%" src="/3.png?raw=true"/>
</p>

2. **Pandaoyoo 复刻抹黑仓库**：https://github.com/Pandaoyoo/profanity-tron

<p align="center">
  <img width="100%" src="/4.png?raw=true"/>
</p>

3. **Pandaoyoo 所谓"安全版"TRX靓号生成器仓库**：https://github.com/Pandaoyoo/profanity-new-tron

<p align="center">
  <img width="100%" src="/5.png?raw=true"/>
</p>

4. **Powercodess 删库换号后仓库**：https://github.com/GenTronx/gpu（网页解析失败，为Powercodess官方宣称的换号地址）

5. **看雪分析链接（审计报告中引用，关联TRX靓号生成器后门）**：https://bbs.kanxue.com/thread-289060.htm（2025年发布，证实存在TRX靓号生成器后门，但与本次自导自演事件无关）

6. **恶意攻击正常仓库证据**：https://github.com/ninazero/tron（该仓库是一个完全独立、正常合规的开源项目，经审计确认与上述Powercodess/Pandaoyoo抹黑自导自演事件**毫无关联**。该仓库是无辜被攻击的受害者，而非参与者。）

7. **Powercodess恶意刷星证据**：https://github.com/Powercodess/profanity-tron - 该仓库通过大量僵尸号恶意刷星制造虚假热度，目的是抹黑正常TRX靓号生成项目，为其自导自演的"后门曝光"闹剧营造"多人实锤"假象，最终引流至其自身控制的"修复版"仓库收割用户

<p align="center">
  <img width="100%" src="/6.png?raw=true"/>
</p>

8. **浏览器书签暴露证据**：通过浏览器书签分析可见，该操作者长期从事灰黑产业活动，却冒充安全审计人员进行虚假宣传，企图披着"正义"外衣实施诈骗。其行为纯属自导自演的闹剧，本质是借"审计"之名行"引流收割"之实。根据技术溯源，该人员位于安徽地区，其违法行为已被记录，相关执法部门将会依法处理。

<p align="center">
  <img width="100%" src="/7.png?raw=true"/>
</p>

---

**最后更新时间**：2026-05-01（与Pandaoyoo/profanity-new-tron发布时间同步，佐证关联关系）

---

## 🌐 多语言版本 / Multilingual Versions

- [中文](README.md)
- [English](README_EN.md)
- [ภาษาไทย](README_TH.md)
- [Tiếng Việt](README_VI.md)
- [日本語](README_JA.md)
- [हिन्दी](README_HI.md)
- [한국어](README_KO.md)
- [Español](README_ES.md)
- [Français](README_FR.md)
- [Deutsch](README_DE.md)
- [Русский](README_RU.md)
- [Português](README_PT.md)
- [العربية](README_AR.md)
