# Learning AI Tools, One at a Time: What I Use Daily vs. What I Still Need to Explore

Every day, my toolkit looks pretty much the same: Claude Code and Claude for the heavy lifting, ChatGPT and Gemini for a second opinion, Bing when I need something searched. That's it. That's the rotation. And yet every time I scroll through a "tools you should know" list, I run into five names I've never touched — Kling, Lovable, ElevenLabs, Nano Banana, Higgsfield — tools that apparently have tens of millions of users and I've just... never opened them.

That gap is basically the reason for this piece. There are somewhere between 14,000 and 47,000 AI tools live on the internet right now, depending on whose directory you trust — and that range itself tells you something: nobody, not even the people counting, fully agrees on what qualifies anymore. What's not in dispute is the scale of adoption underneath all that noise. More than **1 billion people** use standalone AI tools every month, according to DataReportal's Digital 2026 report, and that climbs to roughly **1.5 billion** once you count AI quietly built into tools people already use — Gmail, Slides, Canva. ChatGPT alone crossed 900 million weekly users this year. Goldman Sachs expects the regular-user number to hit 3.5 billion by the end of 2027.

So instead of pretending I already know this landscape, I'm learning it out loud — one category at a time, figuring out not just *what* each tool does but *when* it actually beats the tools I already default to. Here's where I'm starting: a category-by-category breakdown, with the real adoption numbers where they exist, and honest notes on what I still need to go try myself.

---

## Image generation: Nano Banana

Google's Nano Banana (technically the Gemini image model family) has generated **more than 5 billion images** since its August 2025 launch. It's since been folded directly into Google Search, NotebookLM, Slides, Vids, and Photos — meaning most of its usage isn't even a deliberate "let me open an AI app" decision, it's just there when people are already working.

## Image → prompt: PromptHero / Lexica

If you've ever seen an AI image and wanted the exact prompt behind it, this is the category. Tools like PromptHero and Lexica work as searchable prompt libraries — you find an image style you like and reverse-engineer the brief. This corner of the AI tool world is genuinely crowded and low on independent usage data, so treat "popular" here more loosely than the other categories.

## AI voice that sounds real: ElevenLabs

ElevenLabs reports **10 million registered users**, including 1 million daily active users, with 5 million mobile downloads and monthly active users up 300% year-over-year. It's also become the default voice layer other AI tools plug into — Lovable, Replit, and Cursor all integrate ElevenLabs' API directly. (Worth flagging: those specific figures come from a third-party stats aggregator rather than ElevenLabs' own investor reporting, so treat them as directionally accurate rather than exact.)

## AI video: Higgsfield and Kling

Kling is the one with hard numbers: **over 60 million creators** have used it to generate more than 600 million videos, and its monthly active users passed 12 million in January 2026, with paid users up 350% in a single quarter. Higgsfield is real and used, but I couldn't find independently verified usage numbers for it — it shows up mostly as a platform that gives people easier access to models like Nano Banana rather than as a standalone breakout.

## Building landing pages fast: Lovable

Lovable has around **8 million users** as of February 2026, with people launching over 1 million new projects a week and apps built on the platform pulling roughly 600 million visits a month. Sacra estimates the company hit $500 million in annualized revenue in May 2026 — real revenue is one of the more honest signals that usage is genuine, not just sign-ups.

## Design: Claude Design

Anthropic's newer entry into visual/prototype work. It's early enough that independently verified adoption numbers aren't available yet — worth watching rather than citing hard stats on.

## Writing emails: Claude

Claude has become one of the default assistants for drafting and rewriting email, alongside ChatGPT. Precise usage-by-task numbers (e.g., "X million people use Claude specifically for email") aren't publicly broken out, but Claude's overall consumer share has been climbing — one tracker cited it moving from roughly 7% to 21% of the AI chatbot market over the past year.

## Clean, sharp presentations: Chronicle HQ

A newer, more design-forward alternative to traditional deck tools. As with Claude Design, I couldn't find solid independent usage numbers — it's real and used in specific professional/creative circles, but not yet at a scale with published stats.

## Automating repetitive work: Claude Cowork

Anthropic's agentic tool for handing off multi-step knowledge work. Too new for independent adoption data — it's positioned for exactly the "automate the boring stuff" niche you'd expect, but there's no public usage number to cite yet.

## Research and notes: NotebookLM

Google's research assistant has been getting steady feature investment — it recently gained Nano Banana-powered infographics, slide-deck generation, and short video overviews, all pulled directly from a user's own source documents. It doesn't have a standalone public user count, but its increasing integration into core Google Workspace products (Slides, Vids, Search) is itself a signal of how seriously Google is betting on it.

---

## The honest caveat

Notice the pattern above: the tools with the biggest, most verifiable numbers (Nano Banana, Kling, ElevenLabs, Lovable) are also the ones that have existed long enough, or are tied to a large enough parent company, to generate real reporting. The newer or more niche tools (Chronicle HQ, Claude Design, Claude Cowork, Higgsfield) are plausibly popular in their lane, but "popular" is doing more marketing work than data work until someone publishes real numbers.

And one more number worth sitting with: despite over a billion monthly AI users globally, **49% of US workers say they've never used AI at work**, and only 12% use it daily. The tools above are genuinely reshaping how a lot of people create — but "everyone's using AI now" and "most people barely touch it" are both true at the same time, depending on which stat you want to lead with.

## What's next

Knowing a tool exists isn't the same as knowing when to reach for it over what I already use. So here's the first pass at a "use this tool when..." cheat sheet — built around the tools I actually use daily, plus the ones from above.

| Task | Reach for | Not this one when |
|---|---|---|
| Writing/refactoring code, running multi-step dev work | **Claude Code** | You just need a quick one-off script — Claude (chat) is faster for that |
| General reasoning, writing, analysis, long documents | **Claude** | You need live web results — pair it with search, or use ChatGPT/Gemini/Bing instead |
| Brainstorming, quick everyday Q&A, broad general knowledge | **ChatGPT** | You need very current, sourced info — Bing/Gemini's search grounding is stronger |
| Anything needing live, sourced web results | **Gemini or Bing** | You want a long creative or technical draft — that's Claude's/ChatGPT's lane |
| A working prototype or landing page, no dev team | **Lovable** | You need fine-grained custom code control — go straight to Claude Code instead |
| An image from a text prompt, fast and free | **Nano Banana** | You need ultra-high-end commercial artwork — Midjourney still edges it out on polish |
| Turning an image into a reusable prompt | **PromptHero / Lexica** | The image is copyrighted or a real photo — reverse-prompting real photos isn't the use case |
| Realistic voiceover or voice cloning | **ElevenLabs** | You just need basic text-to-speech — most video/deck tools now have this built in |
| AI-generated video from text or image | **Kling** | You want simple slide/video overviews — NotebookLM does that from your own docs already |
| Turning your own notes/docs into a briefing, slides, or infographic | **NotebookLM** | You're starting from nothing (no source material) — that's a generation tool's job, not a research tool's |

## How to actually get started (no downloads needed for most)

Good news: almost none of these require a real "download" — they're browser-based, some with optional mobile apps. Here's how to get into each one and run a first test, free where possible.

**Nano Banana (image generation)**
1. Go to gemini.google.com and sign in with any Google account — no separate signup.
2. Type a plain description of what you want ("a watercolor illustration of a cat reading a book") and generate.
3. Free tier is usable; higher-res/Pro generation needs a Google AI Pro or Workspace plan.
4. Test idea: generate the same prompt in Nano Banana and Midjourney/ChatGPT to compare quality.

**Lovable (landing pages/apps)**
1. Go to lovable.dev and sign up with email or Google.
2. Type what you want built in plain English ("a landing page for a coffee subscription with an email signup form").
3. Lovable builds a live, working preview you can click through immediately.
4. Free tier gives limited credits; paid plans start around $20/month if you want to keep building.
5. Test idea: describe one page, generate it, then ask Lovable to change one section — see how well it iterates.

**ElevenLabs (AI voice)**
1. Go to elevenlabs.io and create a free account.
2. Under the Text to Speech tool, paste a paragraph, pick a voice, and generate.
3. Free tier gives a limited monthly character allowance — enough to properly test quality.
4. Test idea: generate the same paragraph in ElevenLabs and Bing/Gemini's built-in TTS and compare naturalness.

**Kling (AI video)**
1. Go to klingai.com and sign up.
2. Start with a text-to-video prompt or upload a still image to animate.
3. Free tier includes limited daily credits; paid tiers unlock longer clips and 4K.
4. Test idea: try the same short prompt as image-to-video vs. text-to-video and compare control/quality.

**NotebookLM (research/notes)**
1. Go to notebooklm.google.com and sign in with a Google account.
2. Upload a document, PDF, or paste in text/links as a "source."
3. Ask it questions about your source, or generate an Audio Overview, Video Overview, or Infographic from the same material.
4. Fully free for standard use; NotebookLM Plus (via Google One AI Premium) raises usage limits.
5. Test idea: upload this article and ask NotebookLM to turn it into a slide deck.

## Free vs. paid, tool by tool

| Tool | Free tier | Paid, starting at | What paid unlocks |
|---|---|---|---|
| **Nano Banana** (Google/Gemini) | Yes — usable for free with any Google account | Google AI Pro (~$19.99/mo) | Higher-res/4K generation, priority access, higher limits |
| **Lovable** | Yes — 5 credits/day, ~30/month, no card required | $25/month (Pro) | Private projects, custom domains, more credits, credit rollover |
| **ElevenLabs** | Yes — 10,000 credits/month (~10 min of speech), no commercial rights | $5/month (Starter) for commercial rights; $22/month (Creator) for pro voice cloning | Commercial usage rights, voice cloning, higher quality, more monthly minutes |
| **Kling** | Yes — 66 credits/day | ~$7–10/month (Standard) | 1080p/4K, no watermark, more credits, longer/priority generations |
| **NotebookLM** | Yes — 100 notebooks, 50 sources each, 50 chats/day, forever free | $7.99/month (bundled into Google AI Plus) | Higher source/chat limits; Pro tier ($19.99/mo) and Ultra add Deep Research and cinematic video overviews |

The pattern across all five: **the free tier is genuinely enough to test the tool properly** — none of them are locked demos. What you're paying for later is volume (more credits, more minutes, more sources) and commercial rights, not a fundamentally different product. So there's no reason to pull out a credit card before you've actually tried each one on a real task.

## Where to sign up and short videos to watch first

| Tool | Sign up / try it here | A quick video to watch first |
|---|---|---|
| **Nano Banana** | [gemini.google.com](https://gemini.google.com) | ["Create videos with Nano Banana, Runway, ElevenLabs"](https://www.youtube.com/watch?v=S4pjkkcBXy8) — short, practical demo of the image model in action |
| **Lovable** | [lovable.dev](https://lovable.dev) | ["Build Any Website in Minutes with Lovable — Full Tutorial + Demo"](https://www.youtube.com/watch?v=3bdD45EjYkE) — builds a real site start to finish |
| **ElevenLabs** | [elevenlabs.io](https://elevenlabs.io) | ["Eleven Labs Tutorial: Start HERE! (Free AI Voices)"](https://www.youtube.com/watch?v=WnYRKL6nGsg) — shortest, most beginner-focused walkthrough |
| **Kling** | [klingai.com](https://klingai.com) | Search "Kling AI beginner tutorial" on YouTube for a current walkthrough — Kling ships new versions often enough that older tutorials can look outdated fast |
| **NotebookLM** | [notebooklm.google.com](https://notebooklm.google.com) | ["How to Use Google NotebookLM (Step-by-Step Guide) (2026)"](https://www.youtube.com/watch?v=iQGdKNaJnKE) — current, walks through uploading sources and generating overviews |

A word of caution on tutorial videos generally: these tools update fast (Lovable, Kling, and NotebookLM have all shipped major changes just in the past few months), so a video from even 6 months ago can show an outdated interface. The official product pages linked above are the most reliable source of truth if a video ever looks different from what you see on screen.

---

## This weekend: going deep on one

Reading about ten tools is easy. Actually knowing one is different. So instead of trying to touch all of them, the plan for this weekend is to pick just one — probably **Lovable**, since it has the clearest real numbers behind it and the fastest path to something tangible — and spend real time in it: not a five-minute poke, but building something small and real from scratch, hitting its limits, and figuring out exactly where it fits next to Claude Code in my actual workflow.

Next post in this series will be that write-up: what Lovable was actually like to use, where it impressed me, where it fell short, and whether it earns a permanent spot in the rotation.
