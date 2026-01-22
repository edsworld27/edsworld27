# Instagram → YouTube Deep Link Redirect (Self-Hosted & Free)

This repository hosts a lightweight **redirect page** on **GitHub Pages** that allows your Instagram bio link to open the **YouTube app** when possible, with a clean and reliable fallback to the YouTube website.

It is functionally equivalent to paid tools like URLGenius or AppURL — but **free**, **self-hosted**, and **fully under your control**.

---

## What problem this solves

Instagram forces all external links to open inside its **in-app browser**, which:
- Reduces YouTube app opens
- Hurts watch time and session depth
- Adds friction before users reach long-form content

This project solves that by:
- Attempting a YouTube **deep link** immediately
- Falling back gracefully if Instagram blocks auto-open
- Providing a **manual “Open in YouTube app” button** (gesture-based, highly reliable)

---

## What this does (flow)

When a user taps your Instagram bio link:

1. Instagram opens the link in its in-app browser
2. The page attempts to open the YouTube app using deep-link URL schemes
3. If auto-open is blocked, a clear **“Open in YouTube app”** button is shown
4. If the app still can’t open, the user is sent to YouTube on the web

This is the **maximum success rate possible** without building a native app.

---
