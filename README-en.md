# DOCL — Dsls Open Core License

> A license framework balancing commercial sustainability with community trust.

**DOCL (Dsls Open Core License) v1.0** is a source-available license framework designed by the Dsls Team.
It seeks a balance between **commercial sustainability** and **community trust**: all modifications and derivative works must publicly disclose source code,
commercial use requires separate authorization, and pricing is subject to community governance.

---

## Why DOCL?

Existing license models each have their own limitations:

| License | The Problem |
|---------|-------------|
| **GPL/AGPL** | Strong copyleft, zero business model built in. Licensors can't monetize through the license itself |
| **BSL** | Time-limited commercial restrictions; pricing controlled entirely by licensor, no community voice |
| **ELv2 / RSAL** | Only prevents cloud providers, not other commercial use; opaque pricing |
| **MIT / Apache 2.0** | Fully open, but maintainers are exploited by large corporations with no obligation to contribute back |

**DOCL's answer:**

The license itself is a governance contract — not just a legal text, but a **power-sharing agreement** between the project and its community.

---

## Three-Layer Architecture

DOCL is not a single license, but a **license system**:

```
┌─────────────────────────────────────────┐
│  ① Main License (DOCL v1.0)            │
│  ┌─────────────────────────────────────┐│
│  │ • Mandatory source disclosure       ││
│  │ • Anti-malicious fork + trademark   ││
│  │ • CLA + code backport rights        ││
│  │ • Commercial use requires license   ││
│  │ • Disclaimer & liability limits     ││
│  └─────────────────────────────────────┘│
│           Non-Overrideable               │
├─────────────────────────────────────────┤
│  ② Additional Terms                     │
│  ┌─────────────────────────────────────┐│
│  │ • Freely defined by licensor        ││
│  │ • E.g., exemptions, moat clauses    ││
│  │ • Must not conflict with core terms ││
│  └─────────────────────────────────────┘│
│           Customizable                   │
├─────────────────────────────────────────┤
│  ③ Pricing & Community Governance       │
│  ┌─────────────────────────────────────┐│
│  │ • Initial price is public           ││
│  │ • Changes require 51% community vote││
│  │ • Increases ≥15% require ≥15 day    ││
│  │   public notice                     ││
│  │ • Existing users grandfathered      ││
│  └─────────────────────────────────────┘│
│           Non-Overrideable               │
└─────────────────────────────────────────┘
```

---

## Key Features

### Mandatory Source Disclosure (GPLv3-aligned)

Any modification or derivative work, whether internal or external, commercial or non-commercial, must publicly disclose its Corresponding Source in full. Five methods of conveyance: physical media, written offer, offer relay, network distribution, and P2P transmission.

### Anti-Tivoization

When software is distributed in a User Product (consumer electronics, etc.), Installation Information must be provided to ensure modified versions can run on that hardware — closing the "give source but prevent installation" loophole.

### Anti-Malicious Fork

Forks that rename substantially identical code without meaningful functional differentiation, with intent to replace the original project, have their license automatically terminated. Forks with independent roadmaps or substantive differences are unaffected.

### CLA + Code Backport

All contributors must sign a CLA; contribution copyright vests in the project. The licensor retains the right to backport code from any fork, preventing community improvements from being locked away by competitors.

### Commercial Pricing + Community Governance

Commercial use requires a paid license. Initial price is publicly transparent ($100,000/month). Any price change requires a 51% community vote; increases ≥15% require ≥15 days public notice. Existing users are grandfathered.

### Additional Terms

Licensors may add project-specific terms in Article 8, provided they do not conflict with the core terms or violate applicable law. Pricing governance, exemptions, and technical protection measures can all be defined here.

---

## Comparison with Other Licenses

| | GPLv3 | BSL | ELv2 | DOCL |
|--|-------|-----|------|------|
| Source disclosure | ✅ Mandatory | ✅ Mandatory | ✅ Mandatory | ✅ Mandatory |
| Anti-Tivoization | ✅ | ❌ | ❌ | ✅ |
| Commercial restriction | ❌ | ✅ Time-limited | ✅ Hosted service only | ✅ Full commercial |
| Pricing transparency | N/A | ❌ Not public | ❌ Not public | ✅ Public + governance |
| Community pricing power | N/A | ❌ | ❌ | ✅ 51% vote |
| CLA | Optional | Optional | Optional | ✅ Required |
| Additional terms | ⚠️ Whitelist only | ✅ Free | ✅ Free | ✅ Free |

---

## Using DOCL in Your Project

1. **Copy the license text**: Place [DOCL-v1.0-en.txt](DOCL-v1.0-en.txt) in your project root as `LICENSE`;
2. **Fill in Additional Terms**: Define project-specific pricing governance, exemptions, etc., in Article 8;
3. **Prepare a CLA**: Use the DOCL CLA template for contributor agreements;
4. **Prepare a Commercial Exemption Agreement**: Template for commercial user contracts.

> ⚠️ **Disclaimer**: DOCL is a license framework, not legal advice. Consult legal professionals before using it to ensure compliance with your project's needs and applicable law.

---

## License Files

| File | Description |
|------|-------------|
| [DOCL-v1.0-en.md](DOCL-v1.0-en.md) | English (markdown) |
| [DOCL-v1.0-en.txt](DOCL-v1.0-en.txt) | English (plain text) |
| [DOCL-v1.0-zh.md](DOCL-v1.0-zh.md) | Chinese (markdown) |
| [DOCL-v1.0-zh.txt](DOCL-v1.0-zh.txt) | Chinese (plain text) |

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
*Copyright © Dsls Team*
