# YASHIL Creative Studio — concept demo

Live: https://misterrenok.github.io/testcodexa0101/yashil-demo/ru/

## What this demo includes
- Self-hosted, no third-party runtime services; CSS and JS are plain local files.
- Languages: ru / en / tm (Russian content fallback), responsive catalogue, filters, model pages, shortlist.
- Public inquiry form with honeypot and 60s browser-side cooldown.
- Local-only demo administrator at /testcodexa0101/yashil-demo/admin/, with models, language fields, photos, custom fields, page blocks, settings, and sample inquiries.

## Explicit limitations
This is a **static frontend proof of concept**, not a production site.
- There is no authenticated server-side /admin or cross-device data persistence.
- Demo inquiries are saved to browser localStorage only and do not notify anyone.
- Browser-side anti-spam and localStorage are not server security.
- Model faces are AI-generated fictional demo visuals, not studio-licensed talent portraits.
- Work portfolio blocks are demo concepts, not real commissions.
- Font choices are system fallbacks rather than bundled licensed font files.
- Production launch needs backend, secure login, protected media, Telegram+email notification tests, real studio content, consent/privacy review and on-site connectivity testing in Turkmenistan.

Cleanup: delete only the `yashil-demo/` subtree from repo `Misterrenok/testcodexa0101`; do not touch existing assets.
