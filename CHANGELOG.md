# DebugSwift Free Tools changelog

What changed in the tools, newest first. Written from the history of their private source.

## October 2026

- **The hub became a dashboard:** a usable Website Audit at the top, compact tiles grouped by job, each saying where it runs.
- **New: Digital Footprint Check.** How findable and believable a business is online, scored out of 100 with a to-do list.
- **New: Fallback Font Check**, an open-source CLI for developers.
- **Website Audit:** a score out of 100 built from its own checks, and an "ask again" button for each outside check.
- **QR Code Generator:** your logo in the middle with an editor, codes up to version 40, and fixes for downloads and for codes overflowing their frame on phones.
- **Quote & Invoice Generator v2:** a list of documents, GST invoices with CGST/SGST or IGST, a UPI pay QR, your logo.
- **Brand Kit Generator v2:** colours from your logo, a second colour, light and dark themes, mockups, font pairings and a brand sheet.
- **Image Compressor:** AVIF, PNG and a smaller 256-colour PNG, a target file size and a before/after view.
- **Email check, Schema and Meta generators** rewritten in plain words, step by step.
- **Project Scoper is now Project Brief Builder**, with must/nice/no per feature and a table to compare quotes.
- Better contrast on breadcrumbs, input placeholders and excluded items.
- Security update to the framework underneath the tools.

## September 2026

- Moved hosting to Cloudflare.
- **The hub became a rack of tools:** filter by group, search, and see what each tool produces before you open it.
- A Tools menu in the site header, so the free tools stop hiding behind one word.
- Pages load faster: the next page is fetched when you hover a link, and text no longer jumps when the font arrives.
- Website Audit shows its layout while the report is being filled in.
- Website Audit weighs the page a visitor actually downloads, and the saved report is worth keeping.
- Security update to the framework underneath the tools.

## August 2026

- **Ninth tool: Email Deliverability Check.** SPF, DKIM, DMARC and MX, read straight from public DNS.
- **Deeper checks in Website Audit:** Google's Lighthouse scores, Mozilla's security grade and the domain's age, each labelled as whose figure it is and never mixed into our own score.
- The audit shows where its score went, not just what it was.
- QR Code Generator learned Wi-Fi, contact cards, email and SMS.
- Every tool has a figure of its own output on the hub.
- Fixed a security issue in the QR Code Generator's colour input.
- Image Compressor no longer reports a 100 per cent saving that didn't happen.
- The www check no longer calls a working redirect a duplicate site.
- **22 Aug: live at debugswift.com/tools.**

## July 2026: first release

All built on 29 July:

- Website Audit
- Meta & Headline Generator: titles measured in pixels, not characters
- Quote & Invoice Generator, including the amount in words
- Brand Kit Generator, with contrast measured on every step
- QR Code Generator, with its own encoder and a contrast guard
- Image Compressor, including telling you when compressing would make a file bigger
- Project Scoper: a written brief instead of a price guess
- Schema Generator
