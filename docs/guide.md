# The tools, one by one

What each tool does, what it can't tell you, and what happens to what you type. Every tool is free, needs no sign-up, and never puts its result behind an email form.

**Privacy, for all of them:** each page loads one anonymous page-view counter that records the page was opened. It never sees what you type. Tools marked *runs in your browser* send nothing you enter anywhere.

- [Website Audit](#website-audit)
- [Digital Footprint Check](#digital-footprint-check)
- [Schema Generator](#schema-generator)
- [Meta & Headline Generator](#meta--headline-generator)
- [Quote & Invoice Generator](#quote--invoice-generator)
- [Project Brief Builder](#project-brief-builder)
- [Brand Kit Generator](#brand-kit-generator)
- [QR Code Generator](#qr-code-generator)
- [Image Compressor](#image-compressor)
- [Email Deliverability Check](#email-deliverability-check)
- [Fallback Font Check](#fallback-font-check)

---

## Website Audit

[Open it](https://debugswift.com/tools/website-audit)

Paste a web address. The page is fetched once, and 34 checks run on whether it gets found and whether a visitor can act on it. You get a score out of 100 and every answer, including the ones that pass.

**The score** is built only from the audit's own checks. Each group carries a share of the hundred (findability the most), every check in a group counts the same, and "worth a look" earns half marks. The method and each group's points are shown, so you can check the sum.

**The five groups:**
1. **Findability:** whether search engines can reach and index the page, including leftover rules that quietly keep it out.
2. **On the page:** title, description, heading structure and alt text.
3. **How it shares:** what the link looks like pasted into WhatsApp, and whether the preview image actually loads.
4. **Getting in touch:** whether a visitor on a phone can act in one tap.
5. **Delivery:** response time, the measured weight of your images, compression, caching, and what blocks the page from drawing.

**Deeper checks** add Google's Lighthouse scores, Mozilla's security grade and the domain's age. Each is labelled as whose figure it is, never mixed into the score, and has its own "ask again" button if it fails.

**Limits:** 100 means 34 specific things are in order on one page. It says nothing about whether the page persuades anyone. Response time is one request from one server at one moment: a hint, not a verdict.

**Your data:** the result goes straight back to your browser. No copy is kept.

## Digital Footprint Check

[Open it](https://debugswift.com/tools/digital-footprint)

When someone hears your business name, they search it. This checks what they find, in two halves:

- **Measured from your website and domain:** a secure address, your name in the title, structured data saying who you are and linking your profiles, a tap-to-call number used consistently, a WhatsApp link, email on your own domain, and the records that stop others sending as you.
- **Checked by you:** Google, Google Maps, Bing, Apple Maps, Justdial, IndiaMART, LinkedIn, Facebook and Instagram. You get the exact search to open; say whether you're listed and whether the details match.

**Why the second half is yours:** those platforms forbid automated reading, and a blocked request would look like "not found". We won't report something false about your business.

**The score** is out of 100, with the weights shown. Questions you haven't answered are left out, and domain age is shown but never scored.

**Your data:** your home page and domain records are read when you press the button. Your answers stay in your browser.

## Schema Generator

[Open it](https://debugswift.com/tools/schema-generator) · *runs in your browser*

Answer a few plain questions and get the structured data (JSON-LD) that tells search engines your name, address, phone number and opening hours, with a preview of what it says and where to paste it on WordPress, Wix, Squarespace, Shopify or a hand-built site.

**Also handles:** online-only businesses (no street address in the code), hour presets including 24 hours, and your Google Maps link as the map pin.

**Deliberately missing:** a star-rating field. A rating you type in about yourself is one of the more reliable ways to earn a manual penalty.

## Meta & Headline Generator

[Open it](https://debugswift.com/tools/meta-generator) · *runs in your browser*

Say what the page is about and get drafts for the headline and summary Google shows, each checked for where Google would cut it ("Google will cut the last 2 words"). Google cuts by pixel width, not character count, so this measures the real width: 600px for the title, 920px for the description.

**Then:** copy the tags, or paste the two lines into your site builder's SEO settings.

**Limits:** Google rewrites titles it judges unhelpful, whatever their length. The drafts are templates filled with your words, not AI writing.

## Quote & Invoice Generator

[Open it](https://debugswift.com/tools/quote-generator) · *runs in your browser*

Quotes and invoices with your logo, saved as PDFs from your browser. No watermark.

- **A list of your documents**, kept in your browser: duplicate one, turn a quote into an invoice, mark it sent or paid, back everything up, or export a spreadsheet.
- **GST (India):** both GSTINs (checked for typos), HSN or SAC and a rate per line, place of supply, CGST and SGST in your state or IGST outside it, and a tax summary by rate.
- **A UPI QR** on rupee invoices for the balance due, opening the customer's UPI app with the amount filled in.
- Discounts per line or on the whole document, amount paid, round-off, ten currencies.

Amounts are worked out in whole paise, so every figure re-adds. Check your first GST invoices with your accountant.

## Project Brief Builder

[Open it](https://debugswift.com/tools/project-scoper) · *runs in your browser*

Three quotes that differ by four times usually means three people were asked three different questions. This writes one brief you send to all of them: what you're after, why, how you'll know it worked, what you have now, your deadline, and every feature marked must-have, nice-to-have or not needed.

- **A build-time estimate** for the must-haves and for everything, with the days each item adds shown, plus or minus 25%.
- **A comparison table** for the quotes that come back. Anything an agency left out is marked "ask them".

**No prices from us.** The estimate is how long DebugSwift would budget, not a quote.

## Brand Kit Generator

[Open it](https://debugswift.com/tools/brand-kit) · *runs in your browser*

One colour, or your logo, in:

- **Even palettes** for your brand colour, a second colour that suits it, neutrals, and message colours.
- **Light and dark themes**, with the contrast of every text pairing measured.
- **Your colours on a website, business card and social post**, including a colour-blindness preview.
- **A font pairing**, linked to Google Fonts.
- **Exports:** CSS (with a dark theme), Tailwind, SCSS, design tokens, a palette image and a one-page brand sheet.

## QR Code Generator

[Open it](https://debugswift.com/tools/qr-generator) · *runs in your browser*

Links, Wi-Fi, contact cards, WhatsApp, email and SMS. Your content goes in the code itself, with no redirect through anyone's server, so it can't expire or start charging. Download as SVG (sharp at any size) or PNG.

**Your logo in the middle:** crop, zoom, rotate, pick a shape and remove a plain background. The tool switches to the highest error correction, clears the modules behind the logo, and decodes the finished code to check it still reads.

**The honest trade:** nothing routes through us, so there are no scan counts. Scan the proof before printing five hundred flyers.

## Image Compressor

[Open it](https://debugswift.com/tools/image-compressor) · *runs in your browser*

Drop photos or graphics and they're resized and converted on your device: WebP, AVIF where your browser can make it, JPEG, PNG, or a smaller 256-colour PNG for logos and screenshots. Aim for a file size, compare before and after, download one or all.

**When a file comes out bigger,** you get the original back, with a note saying so.

**Worth knowing:** re-encoding is lossy, so keep your originals. All metadata is dropped, including GPS coordinates from phone photos (usually a good thing).

## Email Deliverability Check

[Open it](https://debugswift.com/tools/email-deliverability)

Four plain answers about your domain's email: are you allowed to send, can receivers prove it's you, is there a rule for fakes, can you receive. It names your email provider when it can, links that provider's setup guide, and writes a message to forward to whoever runs your domain. The technical detail (SPF, DKIM, DMARC, MX) is one click away.

**It follows the SPF tree.** SPF allows ten DNS lookups counted across every record it refers to. Most free checkers count only your top-level includes.

**Limits:** DKIM keys live under a name your provider picks, and DNS can't list them, so "couldn't tell" means not on a guessable name, not missing.

## Fallback Font Check

[Open it](https://debugswift.com/tools/fallback-font-check) · [source](https://github.com/DebugSwiftHQ/fallback-font-check) · *runs on your machine*

An open-source command-line tool for developers. It measures your fallback font against your webfont on your real pages, one weight band at a time, and prints the `size-adjust` that stops text re-wrapping when the font loads. MIT licensed.
