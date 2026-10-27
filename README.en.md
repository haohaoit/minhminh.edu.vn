# MinhMinh AI Templates — minhminh.edu.vn

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fminhminh.edu.vn&label=minhminh.edu.vn)](https://minhminh.edu.vn)
[![Repo Library](https://img.shields.io/badge/Repo%20Library-16.5k%20repo%20%C2%B7%2062%20fields-d97757)](https://minhminh.edu.vn/repos)
[![Prompt Library](https://img.shields.io/badge/Prompt%20Library-4.7k%20prompt%20%C2%B7%2029%20fields-d97757)](https://minhminh.edu.vn/prompts)
![Updated](https://img.shields.io/badge/updated-weekly-4ade80)
[![GitHub stars](https://img.shields.io/github/stars/haohaoit/minhminh.edu.vn?style=social)](https://github.com/haohaoit/minhminh.edu.vn/stargazers)

[Tiếng Việt](README.md) · **English**

A free AI resource hub in Vietnamese: ready-to-use templates for Claude Code, more than 16,000 open-source GitHub projects in 62 fields, and nearly 4,700 ready-to-paste prompts for Claude and ChatGPT, close to 1,500 of them written for people in Vietnam.

🌐 **https://minhminh.edu.vn**

![minhminh.edu.vn home page](docs/images/home.jpg)

---

## What's on minhminh.edu.vn

### 1. Claude Code templates in Vietnamese
Nearly 2,000 ready-made components for [Claude Code](https://claude.com/claude-code): skills, agents, slash commands, hooks, MCP servers, settings, mods and plugins. Descriptions and all documentation pages (1,675) are translated into Vietnamese. Each one installs with a single command.

![A component page in Vietnamese](docs/images/component-vi.jpg)

### 2. Repo Library — https://minhminh.edu.vn/repos
- **16,000+ popular open-source projects** from GitHub in **62 fields**: AI and Claude, education, accounting and finance, marketing, HR, office work, design, video, health, law, real estate, beauty and spas, restaurants, travel, logistics, agriculture, IoT, robotics and more.
- Only **maintained** projects (updated within the last year) with an **open licence**; malicious and scam projects are filtered out.
- A **Vietnamese description** for every project; search, field filters and a **"Newly added"** view.
- When the library has no match, the page **searches all of GitHub** for you.

![Repo Library](docs/images/repo-library.jpg)

### 3. Prompt Library — https://minhminh.edu.vn/prompts
- **4,695 prompts** in **29 job-based fields**: teachers, students, accounting and tax, HR, marketing, sales, business owners, law, health, real estate, spas, restaurants, travel, programming, Excel and data, AI images, video and TikTok scripts…
- **1,457 prompts written for Vietnam**: lesson plans following Vietnamese Ministry of Education guidelines (Official Letters 5512/2345), primary-school student assessment (Circular 27), e-invoices, bookkeeping under Circulars 200/133, gross-to-net payroll, selling on Zalo and TikTok Shop…
- **3,238 curated open-licence prompts**, translated and adapted for Vietnamese users.
- **Fill in the blanks**, then **copy** or **open directly in Claude or ChatGPT**.

![Prompt Library](docs/images/prompt-library.jpg)

### 4. Always up to date
| Job | When (Vietnam time) |
|---|---|
| Sync Claude Code templates from the upstream project, translate new descriptions | Every night, 03:30 |
| Collect and translate new projects for the Repo Library, send a Telegram report | Mondays, 02:00 |
| Collect and translate new prompts for the Prompt Library | Mondays, 03:00 |

The site is **bilingual** (EN | VI switch), works well on phones, needs no sign-up, and counts page views with Cloudflare Web Analytics **without tracking cookies**.

---

## Tech stack

| Part | Built with |
|---|---|
| Front end | Astro 5, React, Tailwind CSS |
| Hosting | Cloudflare Pages (free plan), Cloudflare Web Analytics |
| Automation | GitHub Actions: sync, translate, build and deploy |
| Translation and writing | Claude (Anthropic API): Opus for key content, Sonnet for volume; Claude Code cloud sessions for long documents |
| Vietnamese layer | In-browser translation layer plus server-side pre-translated content, without changing the upstream code |

---

## Credits and licences

minhminh.edu.vn is built on these open projects. Thank you to their authors:

- **[Claude Code Templates](https://github.com/davila7/claude-code-templates)** (aitmpl.com) — © Daniel Ávila and contributors, **MIT**. The Claude Code template catalog and the original interface.
- **[prompts.chat](https://github.com/f/prompts.chat)** (Awesome ChatGPT Prompts) — **CC0 1.0**.
- **[Fabric](https://github.com/danielmiessler/Fabric)** — Daniel Miessler, **MIT**.
- **[Microsoft Prompts for Edu](https://github.com/microsoft/prompts-for-edu)** — **MIT**.
- **[Awesome NotebookLM Prompts](https://github.com/serenakeyitan/awesome-notebookLM-prompts)** — **MIT**.
- **[Awesome Nano Banana Pro](https://github.com/ZeroLu/awesome-nanobanana-pro)** and **[Awesome Seedance](https://github.com/ZeroLu/awesome-seedance)** — ZeroLu, **MIT**.
- **[GPT-Image-2 API Prompts](https://github.com/Evolink-AI/awesome-gpt-image-2-API-Prompts)** — Evolink AI, **CC0 1.0**.
- **[Nano Banana Pro Prompts](https://github.com/YouMind-OpenLab/awesome-nano-banana-pro-prompts)** and **[GPT Image 2 Prompts](https://github.com/YouMind-OpenLab/awesome-gpt-image-2)** — YouMind OpenLab, **CC BY 4.0**.
- The Repo Library lists projects found on GitHub; each project belongs to its authors and keeps its own licence.

Vietnamese text on the site is machine-translated with Claude and may contain mistakes. Feedback is welcome at **admin@minhminh.edu.vn**.

---

⭐ **Find it useful?** Click **Star** at the top of this repo so more people discover minhminh.edu.vn. Thank you!

---

## Contact

- Website: https://minhminh.edu.vn
- Email: admin@minhminh.edu.vn
- GitHub: [@haohaoit](https://github.com/haohaoit)

This README and the screenshots are shared under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
