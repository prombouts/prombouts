# Conviction Structure Overview
## Digital Product Productization Framework — v4.1

> **Purpose**: This one-pager summarises the 7 convictions, their dimensions, component
> counts, and the core consumer question each conviction answers.
> Use it as a reference card alongside the full assessment prompt.

---

## The 7 Convictions at a Glance

```
┌─────────────────────────────────────────────────────────────────────────────┐
│          DIGITAL PRODUCT PRODUCTIZATION — CONVICTION STRUCTURE              │
│                  Consumer Lifecycle · 7 Convictions · 13 Dimensions         │
└─────────────────────────────────────────────────────────────────────────────┘

  DISCOVER & START          USE & OPERATE            TRUST & EXIT
  ─────────────────         ─────────────────         ─────────────────
  1. Onboarding Quality     3. Service Model          6. Security & Access
  2. Platform Experience    4. Financial Clarity      7. Exit & Reversibility
                            5. Product Roadmap
```

> **Note**: Contribution Openness (Inner Source / contribution guides) has been removed
> from the core framework as it measures developer collaboration quality, not consumer
> autonomy. It is available as an **Optional Inner Source Maturity Appendix** in the
> full assessment prompt for programmes with an explicit Inner Source target.

---

## Conviction Details

### 1. 🚀 Onboarding Quality
**Core question**: *Can a new consumer reach first value in ≤30 minutes without any
provider assistance?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|------------------|
| Purpose | 3 components | Value proposition, target audience, goal & impact |
| Strategy | 4 components | Delivery approach, dependencies, success metrics, **self-service activation** |
| Digital Product Features | 6 components | CIA rating, functionality, context of use, exposure, lifecycle, contribution to purpose |
| Component Features | 7 components | How-to guides, common issues, contribution guides, explanations, troubleshooting, reference docs, **≤30-min quickstart** |
| Consumer Communication | 3 components | **Discussion boards**, **issue tracker access**, **backlog transparency** |

**Conviction Score** = Average of all 5 dimension percentages
**Total scoreable components**: 23

> **Why Consumer Communication belongs here**: A consumer who cannot get help, report a
> bug, or see what is coming cannot reliably reach or sustain first value independently.
> It is a consumer-facing necessity, not a developer collaboration concern.

---

### 2. ⚙️ Platform Experience
**Core question**: *Can consumers deploy, version, and configure the product on their own
terms?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|------------------|
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
|-----------|-----------|------------------|
| Product Performance | 5 components | Dashboards, scalability transparency, monitoring integration, **actionable errors**, **self-service logs** |

**Conviction Score** = Product Performance %
**Total scoreable components**: 5

---

### 4. 💰 Financial Clarity
**Core question**: *Can consumers understand, estimate, and predict costs before and during
usage?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|------------------|
| Pricing | 3 components | Costing model, charging model (P×Q), **published pricing / no special arrangements** |

**Conviction Score** = Pricing %
**Total scoreable components**: 3

---

### 5. 🗺️ Product Roadmap
**Core question**: *Is the product's future direction visible enough for consumers to plan
their own integrations?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|------------------|
| Product Roadmap | 4 components | Roadmap visibility, feedback loops, version history & changelogs, migration notes |

**Conviction Score** = Product Roadmap %
**Total scoreable components**: 4

---

### 6. 🔐 Security & Access
**Core question**: *Can consumers manage their own access safely and independently from
day one?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|------------------|
| Security & Access | 2 components | Self-managed credentials/keys/scopes, secure defaults for experimentation |

**Conviction Score** = Security & Access %
**Total scoreable components**: 2

---

### 7. 🚪 Exit & Reversibility
**Core question**: *Can consumers leave the product cleanly, independently, and with
their data?*

| Dimension | Max Score | What is assessed |
|-----------|-----------|------------------|
| Exit & Reversibility | 2 components | Self-service de-provisioning, data retention/deletion/portability |

**Conviction Score** = Exit & Reversibility %
**Total scoreable components**: 2

---

## Scoring Quick Reference

| Indicator | Label | Threshold | Meaning |
|-----------|-------|-----------|--------|
| 🟢 | Elite | 100% | All components present — fully productised |
| 🟡 | Top | 66–99% | Strong coverage — minor gaps only |
| 🟠 | Medium | 33–65% | Partial coverage — significant work needed |
| 🔴 | Low | 0–32% | Critical gaps — not yet fit for autonomous consumption |

---

## Component Count Summary

| # | Conviction | Dimensions | Components | Type |
|---|-----------|-----------|-----------|------|
| 1 | Onboarding Quality | 5 | 23 | Component count |
| 2 | Platform Experience | 3 | — | Percentage-based |
| 3 | Service Model | 1 | 5 | Component count |
| 4 | Financial Clarity | 1 | 3 | Component count |
| 5 | Product Roadmap | 1 | 4 | Component count |
| 6 | Security & Access | 1 | 2 | Component count |
| 7 | Exit & Reversibility | 1 | 2 | Component count |
| **Total** | **7 Convictions** | **13 Dimensions** | **39 components + 3 % dimensions** | |
| *(Appendix)* | *Inner Source Maturity* | *2* | *6* | *Optional — not in core scores* |

---

## Consumer Lifecycle Mapping

```
[Discover] ──► [Activate] ──► [Onboard] ──► [Operate] ──► [Evolve] ──► [Exit]
    │               │              │              │             │           │
    C1              C1,C6          C1,C2          C3,C4         C5          C7
 Purpose         Strategy       Component      Service       Roadmap    Exit &
 Features        Activation     Features       Model                    Reversibility
                 Security       Quickstart     Pricing
                                Consumer
                                Communication
```

---

## What Changed from v4.0

| Area | v4.0 | v4.1 |
|------|------|------|
| Convictions | 8 | **7** |
| Dimensions | 15 | **13** (core) + 2 optional |
| Core scoreable components | 45 | **39** |
| Contribution Openness | Conviction 6 (core) | **Removed from core** |
| Consumer Communication | Part of Contribution Openness | **Promoted to Conviction 1** |
| Contribution Accessibility | Core Dimension 11 | **Optional Appendix A** |
| Contribution Guides | Core Dimension 13 | **Optional Appendix B** |
| Security & Access | Conviction 7 | **Conviction 6** |
| Exit & Reversibility | Conviction 8 | **Conviction 7** |

---

## Framework Metadata

| Field | Value |
|-------|-------|
| **Version** | 4.1 |
| **Last Updated** | 2026-06-15 |
| **Convictions** | 7 |
| **Dimensions** | 13 (core) + 2 optional |
| **Total Scoreable Components** | 39 component-based + 3 percentage-based (core) |
| **Autonomy Benchmark** | ≤30 minutes, zero provider assistance |
| **Compatible Prompt** | prompt_consolidated.md (v4.1) |
| **Distribution** | Internal — freely shareable across teams |
