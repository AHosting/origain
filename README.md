# Origain

**Your prompts have an origin. Origain remembers it.**

A Chrome extension that composes a prompt out of the page you are on, puts it into an AI
conversation you already have open, and keeps a local record linking the page, the question and the
answer — so the thing you asked about is findable from the page you asked it about.

Every chat application files your thinking by time, under a title it generated for you. That is why
nobody ever finds anything in one again. The better index is the page you were looking at when you
asked, and nothing can build that index except something standing in both places.

---

## What is in this repository

**The privacy policy**, published at
[ahosting.github.io/origain/privacy.html](https://ahosting.github.io/origain/privacy.html), and
the issue tracker.

**The source is not here.** This repository exists to host the policy at a stable address and to
give the extension a public place to receive reports.

---

## Reporting something

Open an issue here, or write to **origain.support@gmail.com**. Either is read.

**Please do not paste a prompt or an answer into it.** Origain keeps those on your machine and they
are not wanted here — and an issue is public, so anything in it stays public. Almost any defect can
be placed from three things:

1. **The build**, from the top of the side panel — it reads like `0.26.1020.046`
2. **Which site** you were on, by name. The address is not needed, and should not be sent if it is
   a private one
3. **Which button** you pressed, and what appeared on screen

If a bug is about how a particular site is laid out, the useful thing is the **markup of one
element** — right-click the message box → Inspect, and copy the highlighted line. That is
structure, not content, and it is what actually fixes site-specific problems.

---

## What it does not do

- **No server, and no network requests of any kind.** No analytics, no tracking, no account, no
  remotely hosted code.
- **It installs able to reach no website at all.** Every site, including every AI provider, is
  allowed by you one at a time and revocable one at a time in `chrome://extensions`.
- **It never carries text out of one conversation into another**, and never reads a conversation it
  did not put a prompt into.
- **It reads a page only when you press a button**, and only on a site you have allowed.

Everything it stores stays on your computer, and anything in the record can be deleted in a press.

The full detail is in the [privacy policy](https://ahosting.github.io/origain/privacy.html).
