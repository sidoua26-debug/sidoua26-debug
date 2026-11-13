# ExtensionGuy (`sidoua26-debug`)

I build browser extensions and web tools for document conversion, PDFs, tables and tab management. The Word-to-LaTeX web converter and PDF Studio process selected documents on your device.

- **Website**: [extensionguy.me](https://extensionguy.me/)
- **Documentation & Portfolio**: [sidoua26-debug/extensions-portfolio](https://github.com/sidoua26-debug/extensions-portfolio)
- **Privacy Policy**: [extensionguy.me/privacy](https://extensionguy.me/privacy)

---

## Featured Web Utilities & Guides

### Word to LaTeX Converter
- **Live Tool**: [extensionguy.me/word-to-latex-converter](https://extensionguy.me/word-to-latex-converter/)
- Client-side `.docx` and table converter running Pandoc WebAssembly in an isolated Web Worker. Supports LaTeX Fragment and Complete Document output modes. (The web converter does not include OCR.)
- **Companion Guides**:
  - [Offline DOCX to LaTeX Conversion](https://extensionguy.me/guides/docx-to-latex-offline/)
  - [Converting Word Tables to LaTeX](https://extensionguy.me/guides/word-tables-to-latex/)

### Offline PDF Studio
- **Live Tool**: [extensionguy.me/pdf-tools](https://extensionguy.me/pdf-tools/)
- **Repository**: [sidoua26-debug/offline-pdf-studio](https://github.com/sidoua26-debug/offline-pdf-studio)
- Browser-based PDF tools with local document processing for merging, splitting, rotating, compressing, and redacting PDFs.
- **Redaction Mechanics**: Pages with redactions are rasterized, removing their original selectable text layer. Unmarked pages are copied, retaining selectable text where present.
- **Featured Guide**: [How to Redact a PDF Without Uploading It](https://extensionguy.me/guides/redact-pdf-without-uploading/) — Practical walkthrough covering coordinate entry, drag regions, zoom inspection, and verifying exported output.

---

## Published Browser Extensions

| Extension | Availability | Features & Scope | Repository |
| :--- | :--- | :--- | :--- |
| **Word to LaTeX (Offline)** | [Edge](https://microsoftedge.microsoft.com/addons/detail/word-to-latex-offline/lpehnpdkdiddlppobkcicdondaebijlf) · [Chrome](https://chromewebstore.google.com/detail/word-to-latex-offline/appokjanohamffjlecncdegihoelkhco) | Free DOCX and table conversion. The extension also includes experimental local image-to-LaTeX OCR that requires manual review. | [word-to-latex-extension](https://github.com/sidoua26-debug/word-to-latex-extension) |
| **Table Extractor** | [Edge](https://microsoftedge.microsoft.com/addons/detail/table-extractor-export-h/pekammppimoaikllkhhebocbkbidoboe) · [Chrome](https://chromewebstore.google.com/detail/table-extractor-export-h/fjpbjpmccomonleefghgalfoioekhlhm) | **Free**: HTML `<table>` capture to CSV, Excel (XLSX), JSON.<br>**Pro**: Adds capture for supported virtualized grids (AG Grid, scroll containers). | [table-extractor](https://github.com/sidoua26-debug/table-extractor) |
| **BulkGrab** | [Edge](https://microsoftedge.microsoft.com/addons/detail/bulkgrab-batch-file-dow/cphidoikhnjdkeldgelkpddnkojlfccc) · [Chrome](https://chromewebstore.google.com/detail/bulkgrab-batch-file-downl/lnmmneljpgdefilkokfpmiohjgfjcljn) | Free allows up to seven individual file downloads per browser session. Pro removes that session limit and adds on-device ZIP bundling. | [bulkgrab](https://github.com/sidoua26-debug/bulkgrab) |
| **SEO Inspector** | [Edge](https://microsoftedge.microsoft.com/addons/detail/seo-inspector-meta-tags/jbnjjkfkcmfkjamakndojbkjanijlfmd) *(Edge only)* | On-page technical SEO diagnostics evaluating headings, meta tags, OpenGraph, JSON-LD schema, and Navigation Timing. | [seo-inspector-extension](https://github.com/sidoua26-debug/seo-inspector-extension) |
| **Bilexi** | [Edge](https://microsoftedge.microsoft.com/addons/detail/mheomahlcfddgjlemnolopfbhojfpmpb) *(Edge only)* | 100% offline bilingual autocorrect for English and French text fields with accent restoration. | [bilexi](https://github.com/sidoua26-debug/bilexi) |
| **Tab Vault** | [Edge](https://microsoftedge.microsoft.com/addons/detail/paedfgpjmkmmodbcimbkjkkdlfibfpbc) *(Edge only)* | Local tab organization and browser memory management with session recovery snapshots and JSON backups. | [tab-vault](https://github.com/sidoua26-debug/tab-vault) |
