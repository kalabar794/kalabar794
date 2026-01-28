# Hi, I'm Jonathon 👋

**Marketer who got tired of waiting for tools to exist, so I started building them.**

I'm not a developer by trade — I come from marketing and got obsessed with AI. Now I spend my time duct-taping Claude APIs to smart home devices and wondering why my coffee machine needs OAuth.

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-CC785C?style=flat&logo=anthropic&logoColor=white)

---

## 🤖 Moltbot — [molt.bot](https://molt.bot)

An AI assistant that actually controls things in my house. Started as "what if Claude could make me coffee?" and spiraled from there.

**What it does:**
- ☕ **Bosch Home Connect** — Makes coffee, runs the dishwasher, controls the cup warmer (yes, really)
- 💡 **Philips Hue** — Lights, scenes, room controls
- 🎵 **Sonos + Spotify** — Music across rooms, playlist search, volume control
- 🗣️ **ElevenLabs Voice** — Text-to-speech with custom voices
- 📧 **Google Workspace** — Gmail, Calendar, Drive integration
- 🔄 **Auto-refreshing OAuth** — Tokens refresh themselves so things don't break at 3am

Built with MCP (Model Context Protocol) so it plugs directly into Claude. Runs on Railway.

---

## 🔍 SEO-Powerpack — [View Repo](https://github.com/kalabar794/SEO-Powerpack)

A real-time SEO analysis tool because I got sick of waiting for Screaming Frog to load.

**Features:**
- 📊 D3.js visualizations that actually look good
- 🔒 Privacy-first — no data leaves your browser
- ⚡ Built on Next.js 15 with all the modern stuff
- 📋 Actionable recommendations, not just scores

---

## ✍️ Blog-Agent-Worker — [View Repo](https://github.com/kalabar794/Blog-Agent-Worker)

Multi-agent content pipeline for dental practice marketing. One prompt → research → outline → draft → edit → publish-ready content.

Uses Claude's multi-agent architecture to break content creation into specialized steps instead of one giant prompt.

---

## 📊 Ad Extractor — [View Repo](https://github.com/kalabar794/ad-extract)

Competitive ad intelligence tool that pulls ads from:
- Meta Ad Library
- TikTok Ad Library  
- Google Ads Transparency Center
- LinkedIn Ad Library

**What it extracts:**
- Ad copy, CTAs, hashtags
- Landing page analysis (forms, trust signals, conversion elements)
- Auto-categorization into 11 marketing angles (testimonial, promo, educational, etc.)
- Screenshots of creatives

Uses Playwright for browser automation with API fallbacks. Has an MCP server so Claude can search competitor ads directly.

---

## 🛠️ How I Build

I'm learning as I go. Most of this is TypeScript/Node.js because that's what I could figure out. Heavy user of Claude for code review and debugging (and sometimes writing entire functions when I'm stuck).

**Current stack:**
- Railway for hosting
- MCP servers for Claude integration  
- Playwright for anything that needs a browser
- Way too many OAuth tokens

---

*If you're also a non-dev building AI tools, happy to chat. We're all figuring this out together.*
