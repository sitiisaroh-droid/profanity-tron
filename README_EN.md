# TRX Vanity Address Generator Malicious Repository Exposure Report

This document aims to publicly present evidence focusing on malicious repositories related to TRX vanity address/Tron vanity address/USDT wallet vanity address generators. It proves that **Powercodess** and **Pandaoyoo** are controlled by the same person, orchestrating a scheme through multiple repositories of "backdoor exposure → synchronized defamation → launching a 'clean version'". The essence is to maliciously attack legitimate TRX vanity address/Tron vanity address/USDT wallet vanity address generation projects and harvest user trust. Their associated repositories pose extremely high security risks.

---

## ⚠️ Core Statement

After comparing evidence from multiple sources, the following two accounts and their associated repositories are controlled by the same person, primarily targeting TRX vanity address/Tron vanity address/USDT wallet vanity address generation tools. The purpose is to maliciously defame others, stage "backdoor exposure" incidents, and then promote their own so-called "fixed version" TRX vanity address generation repositories, posing risks of coin theft and traffic harvesting:

- **Account 1**: Powercodess, Associated Repository: https://github.com/Powercodess/profanity-tron (Claiming to expose TRX vanity address generator backdoors)
- **Account 2**: Pandaoyoo, Associated Repository 1: https://github.com/Pandaoyoo/profanity-tron (Replicated defamation content); Associated Repository 2: https://github.com/Pandaoyoo/profanity-new-tron (Self-proclaimed "safe version" TRX vanity address/Tron vanity address/USDT wallet vanity address generator)

---

## 📅 Key Timeline (Synchronized Updates, Proof of Same Person)

| Time | Account | Repository Operation | Core Behavior (Related to TRX Vanity Address Generator) |
|------|---------|---------------------|----------------------------------------------------------|
| Unclear time (before 2026.04.25) | Powercodess | https://github.com/Powercodess/profanity-tron | Published "profanity-tron-backdoor-stealing-u-solid-evidence-audit-report", claiming that related TRX vanity address/Tron vanity address generator repositories have backdoors such as private key exfiltration |

<p align="center">
  <img width="100%" src="/1.png?raw=true"/>
</p>

| Time | Account | Repository Operation | Core Behavior (Related to TRX Vanity Address Generator) |
|------|---------|---------------------|----------------------------------------------------------|
| Synchronized with above time | Pandaoyoo | https://github.com/Pandaoyoo/profanity-tron | 1:1 replication of Powercodess's audit report, with identical content, formatting, code line numbers, and evidence links without any modifications, expanding the scope of TRX vanity address generator "backdoor" defamation |

| Time | Account | Repository Operation | Core Behavior (Related to TRX Vanity Address Generator) |
|------|---------|---------------------|----------------------------------------------------------|
| 2026-05-01 21:00:00 | Pandaoyoo | https://github.com/Pandaoyoo/profanity-new-tron | Batch uploaded all source code, claiming to "fix backdoors, remove hidden malicious code", launching a self-proclaimed safe TRX vanity address/Tron vanity address/USDT wallet vanity address generator, forming synchronized linkage with the previous two repositories |

<p align="center">
  <img width="100%" src="/2.png?raw=true"/>
</p>

| Time | Account | Repository Operation | Core Behavior (Related to TRX Vanity Address Generator) |
|------|---------|---------------------|----------------------------------------------------------|
| 2026-04-25 | Powercodess (Account switch) | https://github.com/GenTronx/gpu | Powercodess deleted repository and switched account to avoid risk, Pandaoyoo synchronized follow-up operations, maintaining malicious TRX vanity address generator related repository operations, forming a complete control chain |

---

## 🔍 Core Evidence Chain (Proof of Same Person Control, Related to TRX Vanity Address Generator)

### Evidence 1: 1:1 Replication of Audit Report, Not Independent Audit, Pure Defamation of TRX Vanity Address Generator

The audit report in the Pandaoyoo/profanity-tron repository is completely identical to the report from Powercodess/profanity-tron, both revolving around TRX vanity address/Tron vanity address/USDT wallet vanity address generators, including but not limited to:

- **Core Conclusion**: "TRX vanity address generator source code contains private key + address exfiltration logic, hidden parameters, TLS verification disabled"
- **Code Details**: The location of function `postResult(privateKey, address, postUrl)` (Dispatcher.cpp:L378-L403), core code snippets, line number annotations all point to TRX vanity address generation related logic
- **Hidden Parameters**: The obfuscation construction process of `pptt` (profanity.cpp:L163-L166), explanation of short parameter `-p`, used to control private key exfiltration during TRX vanity address generation
- **Supporting Evidence**: Kanxue analysis link (https://bbs.kanxue.com/thread-289060.htm), account switch records, image placeholders are all identical, used to support the "backdoor" in TRX vanity address generator

**Conclusion**: Pandaoyoo did not conduct any independent audit, only copied and pasted Powercodess's report, aiming to expand the scope of defamation against legitimate TRX vanity address/Tron vanity address/USDT wallet vanity address generation projects, creating an illusion of "multiple people providing solid evidence".

### Evidence 2: Synchronized Update Rhythm, Clear Division of Labor, Traffic Diversion Around TRX Vanity Address Generator

- Powercodess is responsible for "first publishing" the TRX vanity address generator backdoor audit report, playing the role of "justice exposer", guiding users to question legitimate projects;
- Pandaoyoo is responsible for "synchronized forwarding" of the report, reinforcing the negative impression of TRX vanity address generator "backdoor", while launching the "profanity-new-tron" repository, self-proclaimed "safe version" TRX vanity address/Tron vanity address/USDT wallet vanity address generator, harvesting misled users;
- After Powercodess deleted repository and switched account (GenTronx), Pandaoyoo synchronized maintenance of related repository operations, forming a complete closed loop of "exposing and defaming TRX vanity address generator → diverting traffic to own project".

### Evidence 3: Behavioral Logic Contradiction, Obvious Signs of Self-Orchestration, Profiting from TRX Vanity Address Generator

If Pandaoyoo is truly a "justice restorer", why not independently publish an audit report for TRX vanity address/Tron vanity address/USDT wallet vanity address generators, but instead completely replicate Powercodess's content? Why immediately launch a "fixed version" TRX vanity address generator after Powercodess exposed the "backdoor"?

**Core Logic Flaw**: First defame legitimate TRX vanity address generation projects through Powercodess → then expand influence through Pandaoyoo replicating the report → finally launch "fixed version" to harvest traffic. The essence is "thief crying stop thief", self-orchestrating a scheme to attack competitors and profit from TRX vanity address/Tron vanity address/USDT wallet vanity address generation tools.

### Evidence 4: Hard Proof of Backdoor in [Pandaoyoo/profanity-new-tron](https://github.com/Pandaoyoo/profanity-new-tron/) Release (C2 Remote Control Confirmed)

Through reverse engineering analysis of the `tron_vanity.exe` binary file published in the [Pandaoyoo/profanity-new-tron](https://github.com/Pandaoyoo/profanity-new-tron/) repository, it has been confirmed that the executable contains a malicious backdoor that steals generated private keys and sends them to a remote C2 server. **The repository's source code does not contain this backdoor logic; the backdoor was injected at compile time**, which is a classic "clean source, poisoned binary" attack technique.

**C2 Exfiltration Address**: `https://dns.telemetrymicrosof.com/report.php` (Thought using Cloudflare would hide your IP? Corresponding C2 backdoor IP: `45.128.12.32`)

This domain impersonates Microsoft telemetry:
- `telemetrymicrosof.com` is intentionally misspelled (missing a `t`), disguised as `telemetrymicrosoft.com`
- Uses `dns.` subdomain prefix to further disguise as a legitimate Microsoft telemetry service

**Backdoor Communication Mechanism**:
- Network Library: WinHTTP (WINHTTP.dll)
- HTTP Method: POST
- User-Agent: `tron-vanity/1.0` (wide character/UTF-16LE)
- Content-Type: `application/json`

**Custom Authentication Headers (all wide characters)**:

| Header | Purpose |
|--------|---------|
| X-Auth-Signature | HMAC-SHA256 signature |
| X-Auth-Timestamp | Request timestamp |
| X-Auth-Nonce | Random number (anti-replay) |
| X-Auth-Token | Authentication token |

**Stolen Data (JSON format)**:
```json
{"address":"<Tron address>","private":"<private key>","score":<score>,"seconds":<elapsed time>}
```

The backdoor sends the generated Tron address and its corresponding private key to the attacker's server! Once the attacker obtains the private key, they can fully control all assets under that address.

**Backdoor Function List (none exist in source code, injected at compile time)**:

| Function Name | Purpose |
|---------------|---------|
| `sendReportLocalhost(std::string const&, std::string const&, int, long long)` | Send private key data to C2 server |
| `localAuth()` | Generate local authentication information |
| `initLocalhostAuth()` | Initialize authentication mechanism |
| `hmacSha256Hex(std::vector<unsigned char> const&, std::string const&)` | Generate HMAC-SHA256 signature |

**Cryptography-related APIs (BCrypt)**:
- `BCryptOpenAlgorithmProvider` / `BCryptCreateHash` / `BCryptHashData` / `BCryptFinishHash` → HMAC computation
- `BCryptGenRandom` → Generate random Nonce

**Other Backdoor Identifiers**:
At binary offset `0x2B38`, a constructed HTTP header parameter name `tron-vanity-session-key` was found, assembled from three segments: `tron-van` + `ity-sess` + `ion-key` (assembled on the stack at runtime to evade static detection).

**Backdoor Technical Summary**:

| Item | Details |
|------|---------|
| C2 Server | `dns.telemetrymicrosof.com` |
| Backdoor Path | `/report.php` |
| Full URL | `https://dns.telemetrymicrosof.com/report.php` |
| Stolen Data | Tron address + private key + score + elapsed time |
| Communication Method | HTTPS POST (WinHTTP), JSON format |
| Authentication Method | HMAC-SHA256 signature + timestamp + Nonce + Token |
| Disguise Technique | Domain impersonating Microsoft telemetry, stack-based string concatenation to evade detection |

🚨 **This directly confirms that the so-called "safe version" repository of [Pandaoyoo/profanity-new-tron](https://github.com/Pandaoyoo/profanity-new-tron/) actually has a more stealthy C2 remote control backdoor implanted than the original version. The source code is public but the compiled binary is tampered with — a classic "clean source, poisoned binary" attack technique. If you have already used this program to generate addresses, please immediately transfer your assets to a new secure address, as your private keys may have been leaked to the attacker.**

⚠️ **Traceability Warning**: If your C2 address can be traced, you can be found. Enjoy your freedom while you're still out there — your time is running short, cherish it. Thought you were some big APT organization, hehe, little bro your skills really aren't all that!

---

## ⚠️ Security Risk Warning for TRX Vanity Address Generator Related Repositories

Whether Powercodess or Pandaoyoo's associated TRX vanity address/Tron vanity address/USDT wallet vanity address generator repositories, they all pose extremely high security risks. Do not use them:

1. **Powercodess/profanity-tron**: Claims TRX vanity address generator has backdoors (private key exfiltration, hidden parameters, TLS verification disabled), even if the report content is true, it may have been planted by themselves;
2. **Pandaoyoo/profanity-tron**: Pure defamation tool, without any actual TRX vanity address generation functionality, only used to defame legitimate projects, and highly associated with malicious accounts;
3. **Pandaoyoo/profanity-new-tron**: Self-proclaimed "backdoor fixed" TRX vanity address/Tron vanity address/USDT wallet vanity address generator, but provides no third-party security audit proof, cannot rule out the possibility of planting backdoors in a different way, and the release time is synchronized with defamation activities, with impure motives.

---

## 🔧 Security Recommendations (For TRX Vanity Address/Tron Vanity Address/USDT Wallet Vanity Address Generation Tool Users)

- ⛔ Immediately stop using all TRX vanity address/Tron vanity address/USDT wallet vanity address generators and related tools associated with Powercodess, Pandaoyoo, GenTronx;
- 💰 If you have used the above tools to generate private keys (for TRX/USDT wallets), it is recommended to immediately transfer assets from corresponding addresses to avoid coin theft due to private key leakage;
- ✅ When choosing TRX vanity address/Tron vanity address/USDT wallet vanity address generation tools, prioritize legitimate projects that have passed third-party security audits, have good community reputation, and are open-source traceable. Do not trust tools claiming "fast generation, GPU acceleration" without audit proof.

---

## 📌 Report/Rights Protection Instructions

All evidence in this document comes from public GitHub repositories, focusing on malicious repositories related to TRX vanity address/Tron vanity address/USDT wallet vanity address generators, and can be directly used as reporting basis. Reporting directions:

- **GitHub Official**: Report Powercodess, Pandaoyoo accounts for malicious defamation of legitimate TRX vanity address generation projects, false advertising, self-orchestration;
- **Related Communities (TRX/USDT related communities)**: Forward this evidence to remind other TRX vanity address/Tron vanity address/USDT wallet vanity address generation tool users to avoid risks and not be misled.

---

## 📎 Evidence Links Summary (Directly Clickable for Verification, All Related to TRX Vanity Address Generator)

1. **Powercodess Defamation TRX Vanity Address Generator Repository**: https://github.com/Powercodess/profanity-tron

<p align="center">
  <img width="100%" src="/3.png?raw=true"/>
</p>

2. **Pandaoyoo Replicated Defamation Repository**: https://github.com/Pandaoyoo/profanity-tron

<p align="center">
  <img width="100%" src="/4.png?raw=true"/>
</p>

3. **Pandaoyoo So-Called "Safe Version" TRX Vanity Address Generator Repository**: https://github.com/Pandaoyoo/profanity-new-tron

<p align="center">
  <img width="100%" src="/5.png?raw=true"/>
</p>

4. **Powercodess Deleted Repository and Switched Account Repository**: https://github.com/GenTronx/gpu (Web page parsing failed, this is the account switch address officially claimed by Powercodess)

5. **Kanxue Analysis Link (Cited in Audit Report, Related to TRX Vanity Address Generator Backdoor)**: https://bbs.kanxue.com/thread-289060.htm (Published in 2025, confirming the existence of TRX vanity address generator backdoor, but unrelated to this self-orchestrated incident)

6. **Evidence of Malicious Attack on Legitimate Repository**: https://github.com/ninazero/tron

   ⚠️ **Important Notice**: This repository is a completely independent, legitimate and compliant open-source project. After audit confirmation, it has **NO CONNECTION WHATSOEVER** to the above-mentioned Powercodess/Pandaoyoo self-orchestrated defamation incident. This repository is an innocent victim of attacks, NOT a participant. Malicious accounts conducted fake star-boosting and other attack behaviors on this legitimate repository (see evidence image below) in an attempt to damage its reputation. The accounts used were all low-activity zombie accounts with obvious operational traces, seriously violating open-source community guidelines. According to technical traceability, the attacker is located in Anhui region, and such illegal activities will eventually face legal sanctions.

<p align="center">
  <img width="100%" src="/6.png?raw=true"/>
</p>

7. **Powercodess Malicious Star-Boosting Evidence**: https://github.com/Powercodess/profanity-tron - This repository used a large number of zombie accounts to maliciously boost stars to create fake popularity. The purpose was to defame legitimate TRX vanity address generation projects, creating an illusion of "multiple people providing solid evidence" for their self-orchestrated "backdoor exposure" farce, ultimately diverting traffic to their own controlled "fixed version" repository to harvest users.

8. **Browser Bookmark Exposure Evidence**: Through browser bookmark analysis, it can be seen that the operator has long been engaged in gray-black industry activities, yet impersonates security audit personnel for false promotion, attempting to use "justice" as a disguise to commit fraud. Their behavior is purely a self-orchestrated farce, essentially using "audit" as a pretext for "traffic diversion and harvesting". According to technical traceability, the person is located in Anhui region, and their illegal activities have been recorded. Relevant law enforcement agencies will handle it according to law.

<p align="center">
  <img width="100%" src="/7.png?raw=true"/>
</p>

---

**Last Updated**: 2026-05-01 (Synchronized with Pandaoyoo/profanity-new-tron release time, supporting the association relationship)

---

## 🌐 Multilingual Versions

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
