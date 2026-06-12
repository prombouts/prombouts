# Conviction Structure Overview
## Digital Product Productization Framework — v4.0

> **Purpose**: This one-pager summarises the 8 convictions, their dimensions, component
> counts, and the core consumer question each conviction answers.
> Use it as a reference card alongside the full assessment prompt.

---

## The 8 Convictions at a Glance

```
┌─────────────────────────────────────────────────────────────────────────────┐
│          DIGITAL PRODUCT PRODUCTIZATION — CONVICTION STRUCTURE              │
│                  Consumer Lifecycle · 8 Convictions · 15 Dimensions         │
└─────────────────────────────────────────────────────────────────────────────┘

  DISCOVER & START          USE & OPERATE            TRUST & EXIT
  ─────────────────         ─────────────────         ─────────────────
  1. Onboarding Quality     3. Service Model          7. Security & Access
  2. Platform Experience    4. Financial Clarity      8. Exit & Reversibility
                            5. Product Roadmap
                            6. Contribution Openness
```

---

## Conviction Details

### 1. 🚀 Onboarding Quality
**Core question**: *Can a new consumer reach first value in ≤30 minutes without any
provider assistance?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|-----------------|
| Purpose | 3 components | Value proposition, target audience, goal & impact |
| Strategy | 4 components | Delivery approach, dependencies, success metrics, **self-service activation** |
| Digital Product Features | 6 components | CIA rating, functionality, context of use, exposure, lifecycle, contribution to purpose |
| Component Features | 7 components | How-to guides, common issues, contribution guides, explanations, troubleshooting, reference docs, **≤30-min quickstart** |

**Conviction Score** = Average of all 4 dimension percentages
**Total scoreable components**: 20

---

### 2. ⚙️ Platform Experience
**Core question**: *Can consumers deploy, version, and configure the product on their own
terms?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|-----------------|
| Versioning | 100% | Semantic versioning + transparent change management |
| Concurrent Versions | 100% / N/A | Support for multiple live versions simultaneously |
| Configuration Options | 100% | Depth of self-service customisation and extensibility |

**Conviction Score** = Average of applicable dimension percentages (N/A excluded)
**Scoring type**: Percentage-based (not component count)

---

### 3. 📡 Service Model
**Core question**: *Can consumers monitor, diagnose, and remediate issues without contacting
the provider?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|-----------------|
| Product Performance | 5 components | Dashboards, scalability transparency, monitoring integration, **actionable errors**, **self-service logs** |

**Conviction Score** = Product Performance %
**Total scoreable components**: 5

---

### 4. 💰 Financial Clarity
**Core question**: *Can consumers understand, estimate, and predict costs before and during
usage?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|-----------------|
| Pricing | 3 components | Costing model, charging model (P×Q), **published pricing / no special arrangements** |

**Conviction Score** = Pricing %
**Total scoreable components**: 3

---

### 5. 🗺️ Product Roadmap
**Core question**: *Is the product's future direction visible enough for consumers to plan
their own integrations?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|-----------------|
| Product Roadmap | 4 components | Roadmap visibility, feedback loops, version history & changelogs, migration notes |

**Conviction Score** = Product Roadmap %
**Total scoreable components**: 4

---

### 6. 🤝 Contribution Openness
**Core question**: *Is the product genuinely open to external collaboration and
contribution?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|-----------------|
| Contribution Accessibility | 3 components | Open contribution policy, contributor onboarding, Inner Source or contractual model |
| Consumer Communication | 3 components | Discussion boards, issue tracker access, backlog transparency |
| Contribution Guides | 3 components | Code contribution guide, quality & testing standards, governance & review process |

**Conviction Score** = Average of 3 dimension percentages
**Total scoreable components**: 9

---

### 7. 🔐 Security & Access
**Core question**: *Can consumers manage their own access safely and independently from
day one?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|-----------------|
| Security & Access | 2 components | Self-managed credentials/keys/scopes, secure defaults for experimentation |

**Conviction Score** = Security & Access %
**Total scoreable components**: 2

---

### 8. 🚪 Exit & Reversibility
**Core question**: *Can consumers leave the product cleanly, independently, and with
their data?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|-----------------|
| Exit & Reversibility | 2 components | Self-service de-provisioning, data retention/deletion/portability |

**Conviction Score** = Exit & Reversibility %
**Total scoreable components**: 2

---

## Scoring Quick Reference

| Indicator | Label | Threshold | Meaning |
|-----------|-------|-----------|---------|
| 🟢 | Elite | 100% | All components present — fully productised |
| 🟡 | Top | 66–99% | Strong coverage — minor gaps only |
| 🟠 | Medium | 33–65% | Partial coverage — significant work needed |
| 🔴 | Low | 0–32% | Critical gaps — not yet fit for autonomous consumption |

---

## Component Count Summary

| # | Conviction | Dimensions | Components | Type |
|---|-----------|-----------|-----------|------|
| 1 | Onboarding Quality | 4 | 20 | Component count |
| 2 | Platform Experience | 3 | — | Percentage-based |
| 3 | Service Model | 1 | 5 | Component count |
| 4 | Financial Clarity | 1 | 3 | Component count |
| 5 | Product Roadmap | 1 | 4 | Component count |
| 6 | Contribution Openness | 3 | 9 | Component count |
| 7 | Security & Access | 1 | 2 | Component count |
| 8 | Exit & Reversibility | 1 | 2 | Component count |
| **Total** | **8 Convictions** | **15 Dimensions** | **45 components + 3 % dimensions** | |

---

## Consumer Lifecycle Mapping

```
[Discover] ──► [Activate] ──► [Onboard] ──► [Operate] ──► [Evolve] ──► [Exit]
    │               │              │              │             │           │
    C1              C1,C7          C1,C2          C3,C4         C5,C6       C8
 Purpose         Strategy       Component      Service       Roadmap    Exit &
 Features        Activation     Features       Model         Contribution Reversibility
                 Security       Quickstart     Pricing       Openness
```

---

## Framework Metadata

| Field | Value |
|-------|-------|
| **Version** | 4.0 |
| **Last Updated** | 2026-06-12 |
| **Convictions** | 8 |
| **Dimensions** | 15 |
| **Total Scoreable Components** | 45 component-based + 3 percentage-based |
| **Autonomy Benchmark** | ≤30 minutes, zero provider assistance |
| **Compatible Prompt** | prompt_productization_v4.md |
| **Distribution** | Internal — freely shareable across teams |
