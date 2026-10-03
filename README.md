# 🚀 Shopify App Listing Optimization Skill for Claude

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Claude Skills](https://img.shields.io/badge/Claude-Skills_Ready-6B46C1.svg)](https://claude.ai)
[![Shopify Partner](https://img.shields.io/badge/Shopify-App_Store_Optimization-95BF47.svg)](https://shopify.dev)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg)](CONTRIBUTING.md)

An industry-grade **Claude Skill** that audits, writes, and optimizes Shopify App Store listings for **App Store SEO (ASO)**, **high conversion rates (CVR)**, and **"Built for Shopify" merchant trust**.

Designed for Shopify app developers, product managers, SaaS founders, and e-commerce agencies looking to scale organic app installs.

---

## 🌟 Why This Skill?

The Shopify App Store is highly competitive. Great code alone does not guarantee installs. Top-ranking Shopify apps rely on:
- **Zero-truncation Titles & Subtitles** optimized for Shopify's search algorithm.
- **Outcome-driven copywriting** (P-A-S-O framework) targeting merchant ROI instead of feature dumps.
- **Strict compliance** with Shopify Partner character limits and trademark guidelines.
- **Narrative visual storyboards** built for mobile merchants scanning screenshots.
- **"Built for Shopify" standards** (Polaris UI, sub-50ms speed, 2.0 Theme App Extensions).

This Claude Skill acts as your dedicated in-house **Shopify ASO & Conversion Strategist**.

---

## 📂 Repository Structure

```text
├── SKILL.md                                 # Core Claude skill definition & master instructions
├── references/                              # Deep technical knowledge & official rules
│   ├── shopify-app-store-guidelines.md      # Character limits, banned claims & trademark rules
│   ├── ranking-factors-and-seo.md           # Algorithmic weights & search ranking mechanics
│   ├── built-for-shopify-criteria.md        # Speed benchmarks, Polaris UI & App Bridge guidelines
│   └── audit-rubric-100pt.md                # 100-point diagnostic audit scoring rubric
├── templates/                               # Plug-and-play copywriting & asset templates
│   ├── listing-copy-template.md             # Full listing copywriting structure with formulas
│   ├── screenshot-storyboard-template.md    # 6-frame visual narrative storyboard
│   └── review-reply-templates.md            # Merchant review response frameworks (5-star & 1-star)
├── examples/                                # Real-world demonstrations
│   ├── before-after-case-study.md           # Concrete optimization teardown & metrics lift
│   └── sample-audit-report.md               # Example Claude 100-point diagnostic audit output
├── LICENSE                                  # MIT License
└── README.md                                # Project documentation
```

---

## ⚡ Quick Start: How to Use with Claude

### Option A: Using with Claude.ai Projects (Recommended)
1. Go to [Claude.ai](https://claude.ai) and open or create a **Project** (e.g., `Shopify App Marketing`).
2. Add [`SKILL.md`](SKILL.md) and all files in [`references/`](references/) into the **Project Knowledge** section.
3. Paste the contents of [`SKILL.md`](SKILL.md) into the **Project Custom Instructions**.
4. Start prompting Claude!

### Option B: Using with Claude Code CLI
Clone this repository into your project directory or reference it in your Claude Code workflow:
```bash
git clone https://github.com/YOUR_USERNAME/shopify-app-listing-optimization.git
```
Invoke Claude Code and instruct it to load the skill:
```bash
claude "Read SKILL.md and audit my Shopify app listing located in ./listing-draft.md"
```

### Option C: Using with Claude Desktop / Custom Agent
Include [`SKILL.md`](SKILL.md) as a custom system instruction or context file in your agent configuration.

---

## 💬 Prompt Recipes & Command Modes

Once loaded, you can trigger specific modes using these prompt recipes:

### 1. Diagnostic Audit Mode (`/audit`)
```text
Audit my current Shopify App Store listing using your 100-point rubric:
- Title: [Your App Title]
- Subtitle: [Your Tagline]
- Key Benefits: [Your Bullets]
- Description: [Your Listing Text]
- Pricing: [Your Pricing Tiers]
```

### 2. Full Listing Generation (`/generate`)
```text
Generate a high-converting, compliant Shopify App Store listing for my app:
- App Name: BundleHero
- Core Value: Automated bundle discounts, quantity breaks, and volume pricing
- Target Merchant: High-volume fashion and electronics stores
- Key Competitors: FastBundle, Kaching Bundles
- Special Tech: 100% Theme App Blocks, sub-30ms load speed
```

### 3. ASO & Keyword Expansion (`/aso`)
```text
Perform an ASO keyword analysis for a Shopify "Order Tracking & Delivery Date" app. 
Provide:
1. 3 Title & Subtitle variations adhering to character limits
2. 5 high-intent keywords for the Partner Dashboard
3. Recommended semantic keyword distribution for the description
```

### 4. Screenshot Storyboarding (`/visuals`)
```text
Design a 6-frame screenshot storyboard for our Shopify returns and exchange management app.
Include exact headline overlays, UI composition guidance, and mobile readability notes.
```

---

## 📏 Shopify App Store Limits Quick Reference

| Field | Limit | Key Recommendation |
| :--- | :--- | :--- |
| **App Title** | **30 chars** (recommended)<br>50 chars (hard limit) | Keep under 30 chars to avoid mobile truncation. Formula: `[Brand]: [Core Keyword]` |
| **App Subtitle / Tagline** | **63 chars** (STRICT) | State primary value proposition + secondary keyword. Do not repeat title words. |
| **Key Benefits (3-5)** | Title: 30-40 chars<br>Desc: 100-140 chars | Focus on merchant ROI, time saved, and revenue boost. |
| **Detailed Description** | ~2,800 chars max | Use Markdown headers, P-A-S-O framework, FAQs, and speed reassurances. |
| **App Icon** | 1200 x 1200 px (1:1) | Clean vector, legible at 48x48px on mobile. No forbidden Shopify logos. |
| **Screenshots** | 1600 x 900 px (16:9) | 5-6 slides with large contrast text overlays. |

---

## 📊 100-Point Audit Rubric Summary

Claude evaluates listings across 5 pillars:
1. **Positioning & Value Proposition** (25 pts) — Problem-solution clarity, merchant persona fit, ROI focus.
2. **Search Visibility & ASO** (25 pts) — Title/subtitle indexing, keyword density, compliance.
3. **Visual Assets & Storyboard** (20 pts) — Hook power, slide narrative flow, mobile annotation contrast.
4. **Pricing Architecture** (15 pts) — Trial clarity, tier differentiation, zero hidden costs.
5. **Social Proof & Trust Engineering** (15 pts) — Theme safety (2.0 App Blocks), speed (<50ms), support guarantees.

👉 *See full scoring criteria in [`references/audit-rubric-100pt.md`](references/audit-rubric-100pt.md).*

---

## 🤝 Contributing

Contributions, feedback, and new templates are warmly welcome!
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewTemplate`)
3. Commit your Changes (`git commit -m 'Add new B2B wholesale listing template'`)
4. Push to the Branch (`git push origin feature/NewTemplate`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

Developed with ❤️ by **[JAKARIA](https://github.com/JAKARIA)** for the Shopify Developer Community.
