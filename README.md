# Smart Blur

**Chrome extension that blurs and redacts PII and sensitive data on any webpage.** Keeps emails, SSNs, credit cards, phone numbers, and more private—with **local AI** for names and addresses, and **auto-blur when you share your screen**. No account, no cloud, 100% private.

---

## Highlights

- **AI Mode** — Local AI (NER) detects and blurs **names, addresses, organizations**, and other PII in plain text. Runs entirely in your browser via Transformers.js; no data is sent to any server. Choose between Piiranha (English) or multilang (EN, DE, IT, FR).
- **Auto-enable when screen sharing** — As soon as you start sharing your screen (e.g. in Google Meet, Zoom), Smart Blur can automatically turn on blurring so sensitive information stays hidden from your audience.

---

## Features

### Manual mode — Pattern detection

- **Keyword & pattern detection**: Built-in presets for **email**, **SSN**, **credit card**, **phone** (US & international), **IPv4**, and **MAC addresses**.
- **Custom regex** and **keyword** matching; **domain- or URL-specific rules** so patterns apply only on selected sites.
- Blur matches in **form inputs** (inputs, textareas). **Adjustable blur intensity**.

### Manual mode — Selection tools

- **Click-to-blur**: Click any element to blur it.
- **Draw-to-blur**: Draw a rectangle over a region to blur it.
- **Per-page blur persistence**: Save keywords, click targets, and draw regions per URL so they reappear when you revisit.

### AI mode

- **Local AI PII detection**: NER models run in-browser (WebGPU/WASM). Detects **person names**, **locations/addresses**, **organizations**, and miscellaneous entities in unstructured text.
- **Multi-language** support (multilang model: English, German, Italian, French).
- **Confidence threshold** and **"Not PII" list** to tune detection and suppress false positives.

### General

- **Floating quick-access panel** for toggles and tools.
- **Import / export settings**.
- **Light / dark** panel theme.
- Works on **any website**; no server or account required.
