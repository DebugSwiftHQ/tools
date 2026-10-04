# The tools, one by one

What each tool does, what it can't tell you, and what happens to what you type. Every tool is free, needs no sign-up, and never puts its result behind an email form.

**Privacy, for all nine:** each page loads one anonymous page-view counter that records the page was opened. It never sees what you type. Tools marked *runs in your browser* send nothing you enter anywhere.

- [Website Audit](#website-audit)
- [Schema Generator](#schema-generator)
- [Email Deliverability Check](#email-deliverability-check)
- [Meta & Headline Generator](#meta--headline-generator)
- [Quote & Invoice Generator](#quote--invoice-generator)
- [Brand Kit Generator](#brand-kit-generator)
- [QR Code Generator](#qr-code-generator)
- [Image Compressor](#image-compressor)
- [Project Scoper](#project-scoper)

---

## Website Audit

[Open it](https://debugswift.com/tools/website-audit)

Paste a web address. The page is fetched once, and 34 checks run on whether it gets found and whether a visitor can act on it. Every answer is shown, including the ones that pass.

**The five groups:**
1. **Findability:** whether search engines can reach and index the page, including leftover rules that quietly keep it out.
2. **On the page:** title, description, heading structure and alt text.
3. **How it shares:** what the link looks like pasted into WhatsApp, and whether the preview image actually loads.
4. **Getting in touch:** whether a visitor on a phone can act in one tap.
5. **Delivery:** response time, the measured weight of your images, compression, caching, and what blocks the page from drawing.

Optional deeper checks add Google's Lighthouse scores, Mozilla's security grade and the domain's age. Each is labelled as whose figure it is and never mixed into the audit's own score.

**Limits:** a perfect score means 34 specific things are in order on one page. It says nothing about whether the page persuades anyone. Response time is one request from one server at one moment: a hint, not a verdict.

**Your data:** the result goes straight back to your browser. No copy is kept.

## Schema Generator

[Open it](https://debugswift.com/tools/schema-generator) · *runs in your browser*

Fill in your business details and get the structured data (JSON-LD) that tells search engines your name, address, phone number and opening hours. Paste it into the `<head>` of the page it describes.

**What it's for:** it doesn't boost rankings. It stops a search engine guessing, which is what lets it show your hours, phone number, location and the "Open now" line.

**Deliberately missing:** a star-rating field. A rating you type in about yourself is one of the more reliable ways to earn a manual penalty.

**Afterwards:** check the page with Google's Rich Results Test, and keep the markup in step with the visible page. Hours in the code that disagree with hours on the page get the whole block discounted.

## Email Deliverability Check

[Open it](https://debugswift.com/tools/email-deliverability)

Four DNS records decide whether a mail server trusts email from your domain. When they're wrong there's no bounce and no error; the message just doesn't arrive. This reads all four:

| Record | What it's for |
|---|---|
| **SPF** | The list of servers allowed to send email as your domain |
| **DKIM** | A signature proving a message wasn't altered and really came from you |
| **DMARC** | The rule that enforces the other two, and the only way to learn someone else is sending as you |
| **MX** | Where mail addressed to your domain is delivered |

**It follows the SPF tree.** SPF allows ten DNS lookups counted across every record it refers to. Go over and most receivers treat it as no SPF at all. Most free checkers count only your top-level includes.

**Limits:** DKIM keys live under a name your provider picks, and DNS can't list them. The tool tries the selectors the big providers use, so "couldn't tell" means not found on a guessable name, not missing. And correct records don't guarantee delivery: your sending history still counts.

**Your data:** public DNS only. No mailbox is touched and no message is sent.

## Meta & Headline Generator

[Open it](https://debugswift.com/tools/meta-generator) · *runs in your browser*

Google cuts titles by pixel width, not character count. This measures the real width as you type, against 600px for the title and 920px for the description. Two titles of the same length can differ by more than a hundred pixels.

**Tip it builds in:** put the specific thing first and the business name last, because the end of the line is what gets cut.

**Limits:** Google rewrites titles it judges unhelpful, whatever their length. The preview measures in Arial at Google's desktop sizes: close to their rendering, not identical. The drafts are templates filled with your words, not AI writing.

## Quote & Invoice Generator

[Open it](https://debugswift.com/tools/quote-generator) · *runs in your browser*

Fill in one quote or invoice, then print it or save it as PDF from your browser. No watermark. Amounts are worked out in whole paise, so the total always agrees with the lines above it. Leave the tax rate blank and no tax row appears.

**Not a GST tax invoice.** That also needs both GSTINs, HSN or SAC codes and the place of supply. If you're registered, check with your accountant.

**Your data:** your draft is saved in your own browser so a refresh doesn't lose it. "Clear everything" wipes it.

## Brand Kit Generator

[Open it](https://debugswift.com/tools/brand-kit) · *runs in your browser*

One colour in, a usable palette out:

- **Ten steps** built by walking perceptual lightness, so the gaps look even to a human eye.
- **Contrast on every step:** WCAG 2.1 ratios, saying whether black or white text passes.
- **Neutrals** carrying a trace of your hue, so the greys and the brand colour look like one family.
- **A pairing table:** every text colour on every background, measured.
- **A type scale** from one base size and a ratio.
- **CSS custom properties** to paste straight into a stylesheet.

## QR Code Generator

[Open it](https://debugswift.com/tools/qr-generator) · *runs in your browser*

Links, Wi-Fi, contact cards, email and SMS. Your content goes in the code itself, with no redirect through anyone's server, so it can't expire or start charging. Download as SVG (sharp at any size) or a 1024px PNG.

**The honest trade:** nothing routes through us, so there are no scan counts. If you need them, encode a link you control.

**Printing tips:** medium error correction for most print; keep the white border (the "quiet zone"), because cropping it is the most common reason a printed code won't scan; dark code on a light background. Scan the proof before printing five hundred flyers.

## Image Compressor

[Open it](https://debugswift.com/tools/image-compressor) · *runs in your browser*

Camera photos are often three or four megabytes; on a website they need to be a few dozen kilobytes. Drop up to 20 images and they're resized and re-encoded on your device. Defaults: longest edge 1600px, quality 75, WebP.

**When a file comes out bigger,** you get the original back, with a note saying so.

**Worth knowing:** re-encoding is lossy, so keep your originals. All metadata is dropped, including GPS coordinates from phone photos (usually a good thing), the colour profile and any copyright field.

## Project Scoper

[Open it](https://debugswift.com/tools/project-scoper) · *runs in your browser*

Three quotes that differ by four times usually means three people were asked three different questions. Pick what you're building (website, online shop, web app or portal, automation), tick what applies, and get:

- A **written brief** to send to every supplier unchanged.
- The **questions any of them will ask you next**, and the ones to make them answer in their quote.
- A **build-time estimate** in days, with the days each choice adds shown beside it, plus or minus 25%.

**No prices.** The estimate is how long DebugSwift would budget, not a survey of anyone else and not a quote.
