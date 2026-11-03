# Blogging with Free AI: A Beginner Manual

A plain-English, step-by-step guide to writing and publishing blog posts using **only free AI tools**. No subscriptions, no coding, no experience required.

---

## Who this is for

This manual is for beginners who want to start a blog without spending money on AI subscriptions. You do not need to be a coder, a designer, or a tech expert. If you can write an email, you can use this guide.

It was written by **Asdale Dynamics, LLC**, an Indiana company (formed October 2026) focused on beginner-friendly AI education, books, and practical tools. Founder Dylan Asdale (a registered nurse turned AI author) explains AI "like a friend would" — plain English, step by step, never condescending. Learn more at the hub site [dylanasdale.github.io](https://dylanasdale.github.io).

---

## What you need before you start

- A free blog platform account (Blogger, WordPress.com, or Substack — all covered in Section 1)
- Access to any free AI chat tool (examples in Section 1)
- 20–30 minutes per post once you know the workflow
- **The privacy rule memorized** (see below)

---

## The one rule: Privacy first

> **Never paste personal information into an AI tool.**

That means no names, addresses, phone numbers, emails, patient/client details, passwords, or account numbers — yours or anyone else's. Free AI tools are run by companies that may store or review what you type. See [Section 9: Privacy](docs/09-privacy.md) for details.

---

## What is inside

| Section | Markdown | HTML | What you will learn |
|---------|----------|------|---------------------|
| **01 Getting Started** | [docs/01-getting-started.md](docs/01-getting-started.md) | [site/pages/01-getting-started.html](site/pages/01-getting-started.html) | Pick a blog platform, choose free AI tools, learn the privacy rule |
| **02 Topic Ideas** | [docs/02-topic-ideas.md](docs/02-topic-ideas.md) | [site/pages/02-topic-ideas.html](site/pages/02-topic-ideas.html) | Brainstorm what to write about using free AI |
| **03 Outlines** | [docs/03-outlines.md](docs/03-outlines.md) | [site/pages/03-outlines.html](site/pages/03-outlines.html) | Turn a topic into a simple outline before you draft |
| **04 Drafting** | [docs/04-drafting.md](docs/04-drafting.md) | [site/pages/04-drafting.html](site/pages/04-drafting.html) | Write your post with AI help, one section at a time |
| **05 Headlines** | [docs/05-headlines.md](docs/05-headlines.md) | [site/pages/05-headlines.html](site/pages/05-headlines.html) | Write honest, useful titles without clickbait |
| **06 Images** | [docs/06-images.md](docs/06-images.md) | [site/pages/06-images.html](site/pages/06-images.html) | Find and make free images for your posts |
| **07 Scheduling** | [docs/07-scheduling.md](docs/07-scheduling.md) | [site/pages/07-scheduling.html](site/pages/07-scheduling.html) | Publish on a simple, repeatable schedule |
| **08 Repurposing** | [docs/08-repurposing.md](docs/08-repurposing.md) | [site/pages/08-repurposing.html](site/pages/08-repurposing.html) | Turn one blog post into many pieces of content |
| **09 Privacy** | [docs/09-privacy.md](docs/09-privacy.md) | [site/pages/09-privacy.html](site/pages/09-privacy.html) | The one rule to keep you safe |
| **Printable Planner** | [docs/planner.md](docs/planner.md) | [site/pages/planner.html](site/pages/planner.html) | A one-page planner to print and fill out by hand |

---

## How to use this guide

1. **Start at Section 1** and work through in order. Each section builds on the last.
2. **Do the "Quick check" boxes** at the end of each section before moving on.
3. **Use the printable planner** (Section 10 / `planner.md`) to track your weekly posts.
4. **Refer back anytime** — each section stands alone if you need a refresher.

**Time estimate:** Your first post (including setup) takes about 45–60 minutes. Subsequent posts take 20–30 minutes once you know the workflow.

---

## Static HTML site (no build required)

A complete, ready-to-use HTML version lives in `site/`. Just open `site/index.html` in any browser — no server, no build step, no JavaScript required.

```bash
# Open directly (pick one for your OS)
xdg-open site/index.html        # Linux
open site/index.html            # macOS
start site/index.html           # Windows
```

Or serve locally if you prefer:
```bash
cd site && python3 -m http.server 8000
# Then visit http://localhost:8000
```

The planner page (`site/pages/planner.html`) has print-specific CSS — open it and press **Ctrl+P / Cmd+P** to print a clean planner page.

---

## Free AI tools this manual works with

The prompts and workflows work with any free AI chat tool, including:
- Free tiers of major chat AIs (Claude, ChatGPT, Gemini, etc.)
- Local models via Ollama, LM Studio, or similar
- Any tool where you can paste text and get a response

No specific tool is required. Use what you have access to.

---

## Credit

Written and published by **Asdale Dynamics, LLC** (Indiana, formed October 2026).

Part of a series of beginner-friendly AI manuals from Asdale Dynamics, LLC:
- AI tools & agents / MCP
- Local AI & free AI coding
- GitHub & automation
- Privacy-first AI workflows
- Small-business & author tools (KDP, marketing, bookkeeping)
- Accessible life-admin helpers (ADHD-friendly productivity)
- Healthcare-worker AI aids (education only, never medical advice)

---

## License

MIT License. Copyright (c) 2026 Asdale Dynamics, LLC. See [`LICENSE`](LICENSE).

---

*This manual contains no personal data, API keys, or secrets. All content is safe to share publicly.*