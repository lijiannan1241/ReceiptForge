<p align="center">
  <a href="https://apps.microsoft.com/detail/9nfjv0wbjw9z?cid=DevShareMCLPCS&hl=en-US&gl=US">
    <img src="https://img.shields.io/badge/Microsoft_Store-Download_ReceiptForge-0078D4?logo=microsoft&logoColor=white&style=for-the-badge" alt="Download ReceiptForge from Microsoft Store" />
  </a>
  <br />
  <a href="https://apps.microsoft.com/detail/9nfjv0wbjw9z?cid=DevShareMCLPCS&hl=en-US&gl=US">
    <img src="https://img.shields.io/badge/Platform-Windows-0078D4?logo=windows&logoColor=white" alt="Platform: Windows" />
  </a>
</p>

# ReceiptForge

**Offline-first batch receipt OCR and Excel exporter for Windows.**

ReceiptForge turns folders of receipt photos, PDFs, and scans into structured spreadsheets — entirely on your device. No cloud upload, no account, no network access required.

## Download

[![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Download_ReceiptForge-0078D4?logo=microsoft&logoColor=white)](https://apps.microsoft.com/detail/9nfjv0wbjw9z?cid=DevShareMCLPCS&hl=en-US&gl=US)

**Microsoft Store:**  
https://apps.microsoft.com/detail/9nfjv0wbjw9z?cid=DevShareMCLPCS&hl=en-US&gl=US

> This GitHub repository is used for public documentation and feedback. The ReceiptForge application is distributed through the Microsoft Store.

## Why ReceiptForge

| Feature | What it means |
|---|---|
| **100% local processing** | Receipts never leave your machine. Network access is blocked at the application level. |
| **Batch automation** | Point ReceiptForge at a folder and process every receipt in one run. |
| **Broad input support** | Accepts 18 source formats: 11 image types, PDF, and 6 text formats. |
| **Multi-receipt images** | Automatically splits images that contain more than one receipt. |
| **Duplicate detection** | SHA-256 deduplication helps avoid double-processing the same receipt. |
| **17 receipt layouts** | Covers common Chinese invoices and receipts, including VAT invoices, taxi receipts, train tickets, flight itineraries, and shopping receipts. |
| **Auditable results** | Every field carries a confidence score with color, icon, and text indicators. Click a field to highlight its location in the source image. |
| **No silent hallucination** | Unrecognized values are left blank and flagged — never silently replaced with `0.00`. |
| **Export without data loss** | Warnings and failures do not block export. Every receipt is written to the output, with issues collected in a separate list. |
| **Practical export formats** | Excel, CSV, and JSON outputs designed for real accounting workflows. |

## How it works

1. **Import** — Select a folder of receipt images, PDFs, or text files.
2. **Review** — Inspect confidence scores and correct fields in place when needed.
3. **Export** — Generate Excel, CSV, or JSON for downstream use.

## Export formats

- **Excel** — 4 worksheets: main data, issue list, correction log, and summary statistics.
- **CSV** — UTF-8 with BOM, so it opens correctly in Excel without garbled characters.
- **JSON** — Includes confidence scores and bounding boxes for further automation.

## What ReceiptForge does not do

ReceiptForge is intentionally focused. It does **not**:

- Verify invoice authenticity.
- Generate accounting entries or vouchers.
- Replace professional financial review.

These boundaries are deliberate: ReceiptForge is designed to make receipt data extraction faster and more auditable, not to pretend to be an accounting system.

## Feedback

Found a bug or need support for another receipt layout?

- Open an issue in this repository.
- Include the receipt type, expected fields, and a description of the current behavior.
- Do **not** upload real receipts containing sensitive personal or financial information.

For downloads and updates, use the Microsoft Store link above.

## Keywords

`receipt-ocr` · `invoice-recognition` · `offline-first` · `windows-app` · `excel-export` · `privacy-tools` · `batch-processing` · `finance-automation`
