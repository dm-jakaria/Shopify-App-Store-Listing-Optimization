# Shopify App Listing Optimization Skill for Claude

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Claude Skills](https://img.shields.io/badge/Claude-Skills_Ready-6B46C1.svg)](https://claude.ai)
[![Shopify Partner](https://img.shields.io/badge/Shopify-App_Store_Optimization-95BF47.svg)](https://shopify.dev)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Security Policy](https://img.shields.io/badge/Security-Protected-success.svg)](SECURITY.md)

An industry-grade **Claude Skill** that audits, writes, and optimizes Shopify App Store listings for **App Store SEO (ASO)**, **high install conversion rates (CVR)**, and **"Built for Shopify" merchant trust**.

Built on **[DM Jakaria's 10-Step Shopify ASO Roadmap](https://dm-jakaria.com/shopify-app-store-optimization/)**, official [Shopify Developer Documentation](https://shopify.dev/docs/apps/launch/shopify-app-store/best-practices), and empirical benchmarks across 400+ active Shopify apps (average listing CVR **19.34%**, top quartile **30.67%**, and elite listings **40%+**).

---

## Why This Skill?

The Shopify App Store hosts over 13,000+ apps competing for merchant attention:
- **~70% of all app discoveries begin with Search**: Merchants search for jobs-to-be-done (`inventory sync`, `preorder`, `volume discount`), not brand names or technical architecture.
- **Install Velocity & 48-Hour Retention Shape Rank**: Early uninstalls (<48h) penalize search rankings. Clear listing expectations and friction-free onboarding are essential ASO levers.
- **Visuals Drive Installs**: In an experiment by DM Jakaria on the **Essential Grid Gallery** app, simply updating the featured image drove an **+11.8% lift in organic installs and doubled paid subscriptions** in two weeks without altering code or pricing.
- **Strict Character Limits**: Exceeding Shopify's limits causes dashboard rejections or mobile truncation.

This skill equips Claude to act as your full-time **Shopify ASO Strategist & Copy Chief**.

---

## DM Jakaria's 10-Step ASO Roadmap

```
+-----------------------------------------------------------------------------------+
|                  DM JAKARIA'S 10-STEP SHOPIFY ASO ROADMAP                         |
+-----------------------------------------------------------------------------------+
  [Step 1]  App Name (30 chars) & Subtitle (62 chars) - High keyword rank weight
  [Step 2]  App Introduction (100 chars) & Details (500 chars) - Value clarity
  [Step 3]  Primary & Secondary Category Selection - Search placement & density
  [Step 4]  5-Part Feature List (80 chars each) - Benefit-focused scannability
  [Step 5]  5 Backend Search Terms - High intent, zero duplicate keywords
  [Step 6]  Live Demo Store URL - Eliminates merchant hesitation with mock data
  [Step 7]  Business Address & Website URL - Legitimacy & Google/AI SEO discovery
  [Step 8]  Visual Optimization - Featured Image, Video & 4-part Story Screenshots
  [Step 9]  Integrations ("Works With", max 6) & Support Hours - Credibility
  [Step 10] Localized ASO & Continuous Weekly Tracking - Global scaling
```

*Read the full framework breakdown in [`references/jakaria-10-step-aso-framework.md`](references/jakaria-10-step-aso-framework.md).*

---

## 📂 Repository Structure

```text
├── SKILL.md                                 # Core Claude skill definition & master instructions
├── references/                              # Deep technical knowledge & official rules
│   ├── jakaria-10-step-aso-framework.md     # Complete breakdown of DM Jakaria's 10-step methodology
│   ├── shopify-app-store-guidelines.md      # Official character limits, banned claims & speed weights
│   ├── ranking-factors-and-seo.md           # Algorithmic weights, install velocity & churn signals
│   ├── built-for-shopify-criteria.md        # Speed benchmarks, Polaris UI & App Bridge guidelines
│   └── audit-rubric-100pt.md                # 100-point diagnostic audit scoring rubric
├── templates/                               # Plug-and-play copywriting & asset templates
│   ├── listing-copy-template.md             # Full listing copy blueprint with 5-part feature formulas
│   ├── screenshot-storyboard-template.md    # Problem-Feature-Solution-Result visual storyboard
│   └── review-reply-templates.md            # Merchant review response frameworks (5-star & 1-star)
├── examples/                                # Real-world demonstrations
│   ├── before-after-case-study.md           # Analytics app optimization teardown (+143% CVR)
│   └── sample-audit-report.md               # Example Claude 100-point diagnostic audit output
├── CONTRIBUTING.md                          # Contribution guidelines & branch protection
├── SECURITY.md                              # Security policy & safe AI usage guidelines
├── LICENSE                                  # MIT License
└── README.md                                # Project documentation
```

---

## Quick Start: How to Use with Claude

### Option A: Using with Claude.ai Projects (Recommended)
1. Go to [Claude.ai](https://claude.ai) and open or create a **Project** (e.g., `Shopify App Listing Optimization`).
2. Add [`SKILL.md`](SKILL.md) and all files in [`references/`](references/) into the **Project Knowledge** section.
3. Paste the contents of [`SKILL.md`](SKILL.md) into the **Project Custom Instructions**.
4. Prompt Claude using the command modes below.

### Option B: Using with Claude Code CLI
Clone this repository to your machine or project workspace:
```bash
git clone https://github.com/dm-jakaria/Shopify-App-Store-Listing-Optimization.git
```
Run Claude Code with the skill context:
```bash
claude "Read SKILL.md and audit my Shopify app listing located in ./listing-draft.md"
```

### Option C: Download as ZIP
Anyone can download this skill for offline or private team use:
- Click the green **Code** button at the top of this repository and select **Download ZIP**.

---

## Command Modes & Prompt Recipes

### 1. 10-Step Diagnostic Audit Mode (`/audit`)
```text
Audit my current Shopify App Store listing using DM Jakaria's 10-step framework and 100-point rubric:
- Title: [Your App Title]
- Subtitle: [Your Tagline]
- Introduction (100 chars): [Your Intro text]
- Details (500 chars): [Your Description]
- Features: [Your 5 Feature bullets]
- Categories: [Primary & Secondary]
- Pricing: [Your Pricing Tiers]
```

### 2. Full Character-Compliant Listing Generation (`/generate`)
```text
Generate a high-converting, compliant Shopify App Store listing for my app:
- App Name: ProfitGuard
- Core Problem: Merchants losing money on hidden ad costs and negative shipping margins
- Target Merchant: High-volume apparel and electronics stores ($200k+ GMV)
- Integrations: Google Ads, Meta Ads, TikTok Ads, Klaviyo
- Key Differentiators: Sub-30ms load speed, 100% Theme App Blocks, instant net profit sync
```

### 3. ASO & Keyword Architecture (`/aso`)
```text
Perform an ASO keyword analysis for a Shopify "Order Tracking & Estimated Delivery Date" app. 
Provide:
1. Title (<30 chars) and Subtitle (<62 chars) combinations
2. 5 high-intent backend keywords for the Partner Dashboard
3. 5 structured benefit bullets (<80 chars each) based on Jakaria's 5-part blueprint
```

### 4. Visual Storyboarding (`/visuals`)
```text
Design a 4-frame screenshot storyboard for our Shopify returns and exchange management app following the Problem -> Feature -> Solution -> Result arc. Include exact overlay captions (20+ pt) and mobile readability checks.
```

---

## Official Character Constraints Quick Reference

| Field | Official Limit | Key Strategy |
| :--- | :--- | :--- |
| **App Title** | **Max 30 chars** (hard limit) | Lead with brand name. Append exact keyword: `[Brand]: [Keyword]`. |
| **App Card Subtitle** | **Max 62 chars** (hard limit) | Highlight outcome + secondary keyword. Complete sentence. |
| **App Introduction** | **Max 100 chars** (hard limit) | Explains what the app does & who it helps. First text under featured image. |
| **App Details** | **Max 500 chars** (hard limit) | Concise problem-solution overview. Judge.me style clarity. |
| **Feature List (5 items)**| **Max 80 chars per item** | Describe functionality and merchant value, not technical code mechanics. |
| **Backend Search Terms** | **Up to 5 terms** | Single concepts. Complete words. Zero duplicate words with title. |
| **Integrations** | **Up to 6 tools** | Only tools you directly integrate with. Never list Shopify. |
| **Google Title & Meta** | **60 chars / 160 chars** | Off-platform indexing on Google, ChatGPT, and Perplexity. |

---

## Security & Repository Integrity

This repository is publicly accessible for the benefit of the global Shopify developer community:
- **Download & Fork**: Anyone is welcome to download, clone, or fork this repository.
- **Protected Live Code**: Direct pushes to the `main` branch are restricted. Community improvements must be submitted via Pull Requests and undergo review before merging.
- **No Embedded Credentials**: Contains zero API keys, secrets, or sensitive tokens.

*Read the full security policy in [`SECURITY.md`](SECURITY.md).*

---

## License & Community

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

Developed with ❤️ by **[JAKARIA](https://dm-jakaria.com)** ([@dm-jakaria](https://github.com/dm-jakaria)) for the Shopify Partner & Developer Community.
