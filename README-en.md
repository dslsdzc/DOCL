# DOCLFE — Dsls Open Core License (Free Edition)

> A free license framework with source disclosure stricter than GPLv3. Not OSI-approved open source.

**DOCLFE (Dsls Open Core License Free Edition) v1.0** is the non-commercial variant of the DOCL license family, designed by the Dsls Team.
All modifications and derivative works must publicly disclose source code, with requirements stricter than GPLv3 (including anti-Tivoization and AGPL-style network triggering),
but **no commercial terms** — free for any use.

This repository also hosts **DOCL v1.0 Standard Edition** (with commercial terms), detailed below.

---

## Why DOCL/DOCLFE?

Existing license models each have their own limitations:

| License | The Problem |
|---------|-------------|
| **GPL/AGPL** | Strong copyleft, zero business model built in. Licensors can't monetize through the license itself |
| **BSL** | Time-limited commercial restrictions; pricing controlled entirely by licensor, no community voice |
| **ELv2 / RSAL** | Only prevents cloud providers, not other commercial use; opaque pricing |
| **MIT / Apache 2.0** | Fully open, but maintainers are exploited by large corporations with no obligation to contribute back |

**DOCLFE's answer:**

The license itself is a governance contract — not just a legal text, but a **power-sharing agreement** between the project and its community.

---

## Three-Layer Architecture

DOCL/DOCLFE is not a single license, but a **license system**:

| Layer | Status | Content |
|-------|--------|---------|
| **① Main License** DOCLFE v1.0 / DOCL v1.0 | **Non-Overrideable** | Mandatory source disclosure · Anti-competitive fork · CLA + backport · Commercial terms apply only to DOCL v1.0 · Disclaimer |
| **② Additional Terms** | **Customizable** | Licensor-defined exemptions, moat clauses, etc. Must not conflict with main license |
| **③ Pricing & Community Governance** | **Non-Overrideable** | Initial price $100k/mo · Changes require 51% community vote · ≥15% increase needs public notice · Grandfathering |

---

## Key Features

### Mandatory Source Disclosure (GPLv3-aligned)

Any modification or derivative work, whether internal or external, commercial or non-commercial, must publicly disclose its Corresponding Source in full. Five methods of conveyance: physical media, written offer, offer relay, network distribution, and P2P transmission.

### Anti-Tivoization

When software is distributed in a User Product (consumer electronics, etc.), Installation Information must be provided to ensure modified versions can run on that hardware — closing the "give source but prevent installation" loophole.

### Anti-Competitive Fork

Forks that offer the Software or its derivatives to third parties on a paid basis (including hosted services, embedded form, or paid support) with functionality that significantly overlaps with the Licensed Work's capabilities shall have their license automatically terminated (based on the HashiCorp BSL model). Internal use, non-paid distribution, and products that were not competitive when first released are unaffected.

### CLA + Code Backport

All contributors must sign a CLA; contribution copyright vests in the project. The licensor retains the right to backport code from any fork, preventing community improvements from being locked away by competitors.

### Commercial Pricing + Community Governance

Commercial use requires a paid license. Initial price is publicly transparent ($100,000/month). Any price change requires a 51% community vote; increases ≥15% require ≥15 days public notice. Existing users are grandfathered.

### Additional Terms

Licensors may add project-specific terms in Article 8, provided they do not conflict with the core terms or violate applicable law. Pricing governance, exemptions, and technical protection measures can all be defined here.

---

## Comparison with Other Licenses

| | GPLv3 | BSL | ELv2 | DOCL Standard | **DOCLFE** |
|--|-------|-----|------|-------------|----------|
| Source disclosure | ✅ Mandatory | ✅ Mandatory | ✅ Mandatory | ✅ Mandatory | ✅ Mandatory |
| Anti-Tivoization | ✅ | ❌ | ❌ | ✅ | ✅ |
| Commercial restriction | ❌ | ✅ Time-limited | ✅ Hosted service only | ✅ Full commercial | ❌ Free |
| Pricing transparency | N/A | ❌ Not public | ❌ Not public | ✅ Public + governance | N/A |
| Community pricing power | N/A | ❌ | ❌ | ✅ 51% vote | N/A |
| CLA | Optional | Optional | Optional | ✅ Required | ✅ Required |
| Additional terms | ⚠️ Whitelist only | ✅ Free | ✅ Free | ✅ Free | ✅ Free |

---

## Using DOCL/DOCLFE in Your Project

In your project's `LICENSE` file, reference DOCL or DOCLFE by URL — no need to copy the full text:

**Pin to a specific version (recommended, stable terms):**
```
This project uses DOCL v1.0.
Full license text: https://github.com/dslsdzc/DOCL/blob/main/DOCL-v1.0-en.txt
```

**Reference the latest version (auto-follows updates):**
```
This project uses DOCL.
Full license text: https://github.com/dslsdzc/DOCL/blob/main/DOCL-latest-en.txt
```

Additional files (optional, as needed):
- **`ADDITIONAL_TERMS.md`** — Project-specific terms for Article 8, including pricing governance, exemptions, etc.;
- **`COMMERCIAL_EXEMPTION.md`** — Commercial license pricing, conditions, and execution instructions;
- **`CLA.md`** — Contributor License Agreement template, or link to your CLA URL.

> ⚠️ **Disclaimer**: DOCL/DOCLFE is a license framework, not legal advice. Consult legal professionals before using it to ensure compliance with your project's needs and applicable law.

---

## License Files

| File | Description |
|------|-------------|
| [DOCL-v1.0-en.md](DOCL-v1.0-en.md) | DOCL v1.0 Standard (with commercial terms) |
| [DOCL-v1.0-zh.md](DOCL-v1.0-zh.md) | DOCL v1.0 标准版（含商业授权） |
| [DOCLFE-en.md](DOCLFE-en.md) | **DOCLFE v1.0 Free Edition (no commercial terms, not OSI-approved)** |
| [DOCLFE-zh.md](DOCLFE-zh.md) | **DOCLFE v1.0 免费版（无商业条款，非 OSI 开源）** |
| [DOCL-latest-en.txt](DOCL-latest-en.txt) | DOCL latest plain text |
| [DOCL-latest-zh.txt](DOCL-latest-zh.txt) | DOCL 最新版纯文本 |

---

## DOCLFE — Free Edition

DOCLFE is a free variant of DOCL, with commercial authorization and pricing governance terms removed. Suitable for projects that do not wish to involve commercial licensing.

**Differences from DOCL v1.0 Standard:**

| | DOCL v1.0 | DOCLFE |
|---|---|---|
| Commercial license | ✅ $100k/month | ❌ Free |
| Mandatory source disclosure | ✅ Stricter than GPLv3 | ✅ Same |
| CLA + backport | ✅ | ✅ |
| Anti-competitive fork | ✅ | ✅ |
| Patent retaliation | ✅ | ✅ |
| OSI-approved | ❌ | ❌ |

Project reference example:
```
This project uses DOCLFE v1.0.
Full license text: https://github.com/dslsdzc/DOCL/blob/main/DOCLFE-en.txt
```

---

## Design Philosophy

DOCL is built on the following principles:

1. **Openness is a precondition, not a favor** — Community improvements should flow back to the entire ecosystem, not be privatized. Mandatory source disclosure is fairness for all users.
2. **Sustainable business models are essential for long-term openness** — Projects without revenue either die or silently extract from users. Transparent monetization is healthier than hidden exploitation.
3. **Trust requires institutions, not promises** — Pricing power is shared with the community not out of idealism, but because it is more trustworthy than "trust us, we won't raise prices."
4. **A license is a contract, not a slogan** — Every party's rights and obligations should be clearly stated in the license, not left in the vague territory of "open source spirit."

---

## About Dsls Team

DOCL is designed by the Dsls Team, a group focused on **software license governance** and **open source commercial sustainability**.

---

*DOCL v1.0 — Dsls Open Core License*
*License texts in this repository are licensed under CC-BY-4.0.*
*Copyright © Dsls Team*
