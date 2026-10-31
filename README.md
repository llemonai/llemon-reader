# llemonAI Reader

A free PDF reader and annotator for **Windows** and **Android**, from [llemonai](https://llemonai.in).

- **Website:** https://llemonai.in/reader.html
- **Download:** https://llemonai.in/reader.html#download
- **Latest release:** https://github.com/llemonai/llemon-reader/releases/latest

## What it does

- **Side panel:** docked on the left and independent of the document, with the PDF's index, page thumbnails, notes, bookmarks and search.
- **Annotations:** highlight, underline, circle, freehand pen, an eraser, sticky notes, notes on text or whole pages, and bookmarks for pages or comments.
- **Search:** finds single words or whole sentences.
- **Page management:** add blank pages, delete, drag to reorder, rotate, or insert another PDF or Word file at any position.
- **Merging:** append PDF and Word (.docx) files.
- **Saving:** Save keeps annotations editable, Export master PDF burns them in and adds a notes appendix, and Print includes everything.
- **Privacy:** documents never leave your device.

## Requirements

| Platform | Requirement |
|---|---|
| Windows | Windows 10 or 11, 64-bit or 32-bit. It's a single portable `.exe` with no installer and no admin rights, and it uses the Microsoft Edge WebView2 runtime built into Windows. |
| Android | Android 8.0 (API 26) or later, as a sideloaded `.apk`. |

## Verifying downloads

The builds are signed with llemonai's own self-signed certificate (Windows) and release key (Android). Windows SmartScreen may show "Unknown Publisher" and Android may warn about an unknown source; both are expected.

To confirm a file is genuine, compare its SHA256 checksum. On Windows, run `certutil -hashfile <file> SHA256`.

| File (v1.0.2) | SHA256 |
|---|---|
| `llemonAI-Reader-1.0.2-android.apk` | `30E422A47FF3926F88FAABBDE6721841C45ECF36C6359F634189AB8BAF7A9159` |
| `llemonAI-Reader-1.0.2-win-x64.exe` | `97F69E8066A5AC5F6AB9C07F317EDEF212EC6AFD0CC7EB92EA2834D8DC064990` |
| `llemonAI-Reader-1.0.2-win-x86.exe` | `F0C473B94279E764E05AE8E1DF47A38F79ED73BDEC78B73A598E3746E562B83F` |

## Repo contents

This repository holds only the release binaries and this README. The application source code is not public.

Third-party open-source components are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contact

llemonai.us@gmail.com

&copy; 2026 llemonAI (llemonai.in). All rights reserved.