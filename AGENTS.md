# AGENTS.md — jonathanmccallum-fa (Persian (فارسی) mirror of jonathanmccallum.com)

Persian (فارسی) mirror site. Same theme and design as the main site (Paper Light),
content translated into Persian (فارسی), meaning-first. Repo: streamjonathan/jonathanmccallum-fa.
Live (when approved): fa.jonathanmccallum.com. Proof: jonathanmccallum-fa.pages.dev.

## Mission

Mirror jonathanmccallum.com in Persian (فارسی) — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Persian (فارسی) site goes live on fa.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Script: Persian, right-to-left.
- Register: plain, warm, honest; short sentences; "تو" for the reader throughout,
  never "شما" (matches the French "tu" / German "du" proofs). FLAG for Jonathan:
  if he prefers formal "شما", the "تو" forms change throughout.
- Names (never vary): عیسی, خدا (standard Persian Bible usage, not الله), مسیح,
  پطرس, آدم و حوا, اصلان, نارنیا, لوسی, دیگوری, تیریان, سی. اس. لوئیس.
  Book titles use the published Persian titles where they exist: سرگذشت نارنیا,
  آخرین نبرد, خواهرزاده جادوگر. طلاق بزرگ and سه‌گانه فضایی were translated
  for this site — no published Persian titles found, flagged.
- Bible verses: no direct verse quotations appear in these 5 articles. The
  bread/water of life lines are Jonathan's paraphrase — نان حیات / آب حیات
  (matching Tarjomeh-ye Qadim, John 6:35) — never quoted as Scripture.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
