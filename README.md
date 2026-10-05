# 🛍️ Claude Skill: Product Description Writer

![Claude Skill](https://img.shields.io/badge/Claude-Skill-D97757?style=for-the-badge)
![Shopify](https://img.shields.io/badge/Shopify-Ready-7AB55C?style=for-the-badge&logo=shopify&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

A custom **Claude skill** that writes conversion-focused product descriptions for **Shopify, WooCommerce, Amazon and Etsy**, in **your** brand voice, every time.

## ✨ What it does

- Writes an **SEO title**, a hook, **benefit-driven bullets**, product details and a **meta description**
- Follows your **brand voice file**, so every product page sounds the same
- Turns features into benefits customers care about
- Asks for missing info instead of inventing specs
- Offers a short version, a different tone and 3 alternative SEO titles

## 📁 What's inside

```
product-description-writer/
├── SKILL.md          # the skill instructions Claude follows
└── brand-voice.md    # fill in once with your brand's tone and words
examples/
└── ceramic-mug.md    # a full sample input and output
```

## 🚀 How to install

**Claude Code**
1. Copy the `product-description-writer` folder into `~/.claude/skills/`
2. Start Claude Code and ask: *"Write a product description for ..."*

**Claude app (claude.ai)**
1. Zip the `product-description-writer` folder
2. Upload it in **Settings → Capabilities → Skills**
3. Ask Claude for product copy and the skill is used automatically

## 🎨 Make it yours

Open `brand-voice.md` and replace the examples with your store name, tone, favorite words and words to avoid. The skill reads it every time it writes.

## 📝 Example

**Input:** handmade 350 ml speckled stoneware mug, dishwasher safe, gift box, for people who love slow mornings.

**Output (shortened):**

> **Morning Ritual Mug – Handmade Speckled Stoneware Mug, 350 ml**
>
> Your slow morning deserves more than a plain mug. The Morning Ritual Mug is shaped by hand and finished in a soft speckled glaze, so every coffee feels like a small celebration.
>
> **Why you'll love it**
> - **Made by hand:** no two mugs are exactly the same
> - **Just the right size:** 350 ml fits a full latte
> - **Easy everyday care:** dishwasher and microwave safe

See the full output in [`examples/ceramic-mug.md`](examples/ceramic-mug.md).

## 👋 About me

I'm **Michael Frank**, an AI developer. I build custom Claude skills, Claude websites and Shopify stores, and I set up and fix AI agents.

**Need a custom Claude skill for your business?** Message me on Fiverr.

## 📄 License

MIT, free to use and adapt.
