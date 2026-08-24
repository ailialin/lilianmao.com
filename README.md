# LiLianMao (利聯貿) — Non-Custodial B2B Crypto Compliance Specification

[![Website](https://img.shields.io/badge/Official_Website-lilianmao.com-059669?style=flat-square)](https://lilianmao.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Compliance](https://img.shields.io/badge/B2B_Compliance-Hong_Kong_AML-green?style=flat-square)](https://lilianmao.com/solutions/trading-companies/)

Open-source specifications, data schemas, and integration guidelines for **LiLianMao (利聯貿)** — non-custodial B2B crypto compliance software designed for Hong Kong trading companies, sourcing agents, and freight forwarders.

---

## 🌐 Official Links
* **Official Website:** [https://lilianmao.com](https://lilianmao.com)
* **Partnership Program:** [https://lilianmao.com/partners/](https://lilianmao.com/partners/)
* **Industry Solutions:** [Hong Kong Trading Companies](https://lilianmao.com/solutions/trading-companies/) | [Mainland Chinese Factories](https://lilianmao.com/solutions/chinese-factories/)

---

## 🛡️ The Problem We Solve
Paying Mainland Chinese suppliers via USDT or unscreened P2P networks creates severe compliance risks. Unscreened transfers trigger bank AML flags, leading to frozen Hong Kong corporate bank accounts ("Dong Ka" / 凍卡 risk) and rejected annual audits.

**LiLianMao** bridges cross-border crypto settlements with traditional banking compliance without taking custody of funds.

### Core Architecture Highlights
* **Pre-Transfer KYT Wallet Screening:** Identify tainted or high-risk crypto assets before transaction execution.
* **Automated Bank Evidence Packs:** Automatically link purchase invoices, contracts, customs documentation, and on-chain TxIDs into audit-ready files.
* **100% Non-Custodial:** Zero custody risk. Software layer only.

---

## 📄 Open Data Schemas
This repository contains reference JSON schemas for building compliant trade settlement payloads:

- [`schemas/bank-evidence-pack.json`](./schemas/bank-evidence-pack.json) — Reference JSON Schema for structuring bank-ready audit evidence packs.

---

## 🌐 Internationalization & Supported Locales
The LiLianMao platform natively supports 5 locales:
- `en`: English (Global Trade)
- `zh-Hant`: 繁體中文 (Hong Kong CSPs & Traders)
- `zh-Hans`: 简体中文 (Mainland Suppliers & Logistics)
- `ar`: العربية (MENA / UAE Import & Export)
- `ru`: Русский (CIS Cross-Border Trade)

---

## ⚖️ Disclaimer
*LiLianMao is a non-custodial software provider. KYT screening results are indicative and do not replace formal regulatory advice or guarantee individual banking outcomes.*
