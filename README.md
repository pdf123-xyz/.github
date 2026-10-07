# PDF123 — Every PDF tool you need

**[https://pdf123.xyz](https://pdf123.xyz)** · Free online PDF toolbox · No sign-in · Nothing to install

PDF123 is a practical, professional PDF toolbox for everyday document work: combining exports, splitting scans, shrinking attachments, converting formats, running OCR on image-only pages, and basic security hygiene. **56 tools** across organize, convert, edit, security and advanced categories — not just merge and split.

## ✨ New: Edit PDF text in your browser

**[Edit PDF](https://pdf123.xyz/edit-pdf)** lets you change the text that's already in a PDF — no source file needed.

- **Click a line, type, done** — hover over text, click to edit, press Enter to confirm or Esc to cancel.
- **Private by design** — editing, saving and exporting all happen in your browser. Your PDF is never uploaded, and no sign-in is required.
- **Undo anything** — step back with Ctrl/⌘+Z all the way to the original; clear a line to delete it.
- **Download a new copy** — Ctrl/⌘+S saves the edited PDF; your original file is never overwritten.
- **Fonts that match** — edits reuse the line's original font where possible, and fall back to a matching open-source font for characters the PDF doesn't contain. Only those few characters are requested — never your file or your other text.
- **Real removal** — the old text is removed from the page content, so it can't be found by copy or search.

Best for small corrections that keep the line length similar: an invoice total or date, a typo in a name, a phone number on a résumé. Password-protected files are supported (up to 32 MB).

**Limits:** it edits existing lines of text only — no adding new text, no automatic line wrapping, no scanned pages (use OCR for those), and no right-to-left or Indic scripts. For bigger rewrites, go back to the source file or convert to Word first.

## Why PDF123

- **Completely free** — every tool is free to use, with no hidden limits on the basics.
- **No sign-in required** — drop a file in and go; creating an account is optional.
- **Files aren't retained** — uploads are processed and deleted automatically once your download is ready. Edit PDF runs entirely in your browser and uploads nothing.
- **Nothing to install** — runs in your browser, no desktop app required.
- **A genuinely full toolset** — organize, convert, edit, secure and inspect PDFs.

## How it works

1. **Upload a file** — drop it in or choose one from your device. Multiple files are supported.
2. **Pick an operation** — use a recommended action or browse the full catalog.
3. **Download the result** — ready in seconds.

## Tools

### Organize (15)
Merge · Split PDF · Rotate PDF · Extract Pages · Remove Pages · Adjust page-scale · Add Page Numbers · Remove Blanks · Split by Chapters · Split by Page Count · Split by Sections · PDF to Single Page · Auto Split PDF · Overlay PDFs · Reorganize Pages (drag-and-drop)

### Convert (16)
PDF to Word · Image to PDF · PDF to Image · HTML to PDF · PDF to Presentation · PDF to RTF (Text) · PDF to PDF/A · PDF to Markdown · PDF to HTML · PDF to CSV · PDF to Excel · Markdown to PDF · eBook to PDF · File to PDF (Office via LibreOffice) · PDF to XML · URL to PDF

### Edit (15)
**Edit PDF Text (in-browser, no upload)** · Compress · Linearize PDF · Repair PDF · Flatten · Edit Metadata · Extract Images · Remove Image · Auto Rename · Replace & Invert Colors · Add Image · Add Attachments · Crop PDF · Extract Image Scans · Decompress PDF

### Security (8)
Add Password · Remove Password · Add Watermark · Sanitize PDF (remove JavaScript, embedded files, metadata and links) · Redact · Remove Certificate Signature · Validate PDF Signature · Add Stamp to PDF

### Advanced (3)
OCR to Markdown (native text plus OCR from image pages) · Document Info (metadata, permissions, fonts, structure) · Show JavaScript

## Use it from your terminal, AI agent or code

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

**Try it now → [pdf123.xyz](https://pdf123.xyz)**
