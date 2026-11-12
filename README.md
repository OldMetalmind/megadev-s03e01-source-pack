# S03E01 source collection

Private working repository for gathering and reviewing the five Challenge sources for MEGA.dev S03E01, **status for the night**.

## Source order

| ID | Source | File location | Status |
|---|---|---|---|
| SRC-01 | Memo | `sources/SRC-01/` | Awaiting delivery |
| SRC-02 | Screenshot | `sources/SRC-02/` | Awaiting delivery |
| SRC-03 | Recording | `sources/SRC-03/` | Awaiting delivery |
| SRC-04 | PDF | `sources/SRC-04/` | Awaiting delivery |
| SRC-05 | Whiteboard photo | `sources/SRC-05/` | Awaiting delivery |
| SRC-06 | Live tram 3 board | Challenge page only | Reviewed outside this repository |

## Intake rules

1. Preserve each original file unchanged under its source directory.
2. Do not commit credentials, upload tokens, cookies, or private URLs with tokens.
3. Record the original filename, byte size, MIME type, SHA-256, arrival time, and delivery method in `manifest.csv`.
4. Put extracted text, screenshots, audio derivatives, and review notes under `review/`, never over the original.
5. Cite every requirement to a source ID and locator such as page, timestamp, or image region.
6. Record conflicts without deciding them. Product decides.

The repository is for source evidence and review preparation. It is not the final requirements submission and does not contain the `UPLOAD_TOKEN`.

## Upload endpoint

The deployed Worker endpoint is documented in the parent project’s `UPLOAD.md`. The upload token must be transferred through a secure channel and must not be stored here.

## Local checks

```bash
find sources review -type f -print
sha256sum sources/SRC-*/original/* 2>/dev/null
```
