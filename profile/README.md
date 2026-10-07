<div align="center">

# PDF123

### Every PDF tool you need — free, private, and in your browser.

[![Website](https://img.shields.io/badge/Website-pdf123.xyz-2563eb?style=for-the-badge)](https://pdf123.xyz)
[![Tools](https://img.shields.io/badge/Tools-56-16a34a?style=for-the-badge)](#-all-tools)
[![No sign-in](https://img.shields.io/badge/Sign--in-not%20required-f59e0b?style=for-the-badge)](https://pdf123.xyz)

**[Try it now → pdf123.xyz](https://pdf123.xyz)**

[Edit PDF](https://pdf123.xyz/edit-pdf) · [All tools](#-all-tools) · [CLI](#command-line) · [MCP](#ai-agents-mcp) · [SDK](#typescript-sdk)

</div>

---

PDF123 is a practical PDF toolbox for everyday document work: combining exports, splitting scans, shrinking attachments, converting formats, running OCR on image-only pages, and basic security hygiene. **56 tools** across organize, convert, edit, security and advanced categories — far beyond merge and split.

## ✨ Highlight: Edit PDF text in your browser

**[Edit PDF](https://pdf123.xyz/edit-pdf)** changes the text that's already in a PDF — no source file needed.

| | |
|---|---|
| ✏️ **Click, type, done** | Hover over text, click to edit, press `Enter` to confirm or `Esc` to cancel. |
| 🔒 **Private by design** | Editing, saving and exporting all happen in your browser. Your PDF is never uploaded. |
| ↩️ **Undo anything** | Step back with `Ctrl/⌘+Z` all the way to the original. Clear a line to delete it. |
| 💾 **Safe export** | `Ctrl/⌘+S` downloads a new copy; your original file is never overwritten. |
| 🔤 **Fonts that match** | Reuses the line's original font where possible, and falls back to a matching open-source font for missing characters. Only those few characters are requested — never your file or text. |
| 🧹 **Real removal** | Old text is removed from the page content, so it can't be found by copy or search. |

**Best for** small corrections that keep the line length similar: an invoice total or date, a typo in a name, a phone number on a résumé. Password-protected files are supported (up to 32 MB).

**Limits:** edits existing lines of text only — no adding new text, no automatic line wrapping, no scanned pages (use OCR for those), and no right-to-left or Indic scripts. For bigger rewrites, go back to the source file or convert to Word first.

## Why PDF123

- 🆓 **Completely free** — every tool is free, with no hidden limits on the basics.
- 🚪 **No sign-in** — drop a file in and go; creating an account is optional.
- 🗑️ **Files aren't retained** — uploads are processed and deleted automatically once your download is ready. Edit PDF runs entirely in your browser and uploads nothing.
- 🌐 **Nothing to install** — runs in your browser, no desktop app required.
- 🧰 **A genuinely full toolset** — organize, convert, edit, secure and inspect PDFs.

## How it works

1. **Upload** — drop a file in or choose one from your device. Multiple files are supported.
2. **Pick an operation** — use a recommended action or browse the full catalog.
3. **Download** — your result is ready in seconds.

## 🧰 All tools

| Category | Count | Tools |
|---|:---:|---|
| **Organize** | 15 | Merge · Split PDF · Rotate PDF · Extract Pages · Remove Pages · Adjust Page Scale · Add Page Numbers · Remove Blanks · Split by Chapters · Split by Page Count · Split by Sections · PDF to Single Page · Auto Split PDF · Overlay PDFs · Reorganize Pages (drag-and-drop) |
| **Convert** | 16 | PDF to Word · Image to PDF · PDF to Image · HTML to PDF · PDF to Presentation · PDF to RTF (Text) · PDF to PDF/A · PDF to Markdown · PDF to HTML · PDF to CSV · PDF to Excel · Markdown to PDF · eBook to PDF · File to PDF (Office via LibreOffice) · PDF to XML · URL to PDF |
| **Edit** | 15 | **Edit PDF Text (in-browser, no upload)** · Compress · Linearize PDF · Repair PDF · Flatten · Edit Metadata · Extract Images · Remove Image · Auto Rename · Replace & Invert Colors · Add Image · Add Attachments · Crop PDF · Extract Image Scans · Decompress PDF |
| **Security** | 8 | Add Password · Remove Password · Add Watermark · Sanitize PDF (remove JavaScript, embedded files, metadata and links) · Redact · Remove Certificate Signature · Validate PDF Signature · Add Stamp to PDF |
| **Advanced** | 3 | OCR to Markdown (native text plus OCR from image pages) · Document Info (metadata, permissions, fonts, structure) · Show JavaScript |

## 💻 Use it from your terminal, AI agent or code

The same tools are available as a command line, an MCP server and a TypeScript SDK.

### Command line

```bash
npx @pdf123/cli merge a.pdf b.pdf -o merged.pdf
```

### AI agents (MCP)

Give Claude, Cursor and other MCP clients the PDF tools:

```bash
claude mcp add pdf123 -e PDFX_API_BASE=https://pdf123.xyz -- npx -y @pdf123/mcp
```

### TypeScript SDK

```bash
npm install @pdf123/sdk
```

Call the tools from Node.js or Bun with typed methods. See the guides on the [website](https://pdf123.xyz).

## Learn more

Each tool page explains when to use it, how processing works, and what the limits are. The site also has About, Privacy and Blog pages with deeper explainers on compression, OCR and machine-readable publishing.

---

<div align="center">

**[Try PDF123 now → pdf123.xyz](https://pdf123.xyz)**

</div>
