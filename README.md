# llemonAI Reader

A free PDF reader and annotator for **Windows** and **Android**, from [llemonai](https://llemonai.in).

- **Website:** https://llemonai.in/reader.html
- **Download:** https://llemonai.in/reader.html#download
- **Latest release:** https://github.com/llemonai/llemon-reader/releases/latest

## What it does

- **Side panel:** docked on the left and independent of the document, with the PDF's index, page thumbnails, notes, bookmarks and search.
- **Annotations:** highlight, underline, circle, freehand pen, sticky notes, notes on text or whole pages, and bookmarks for pages or comments.
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

| File (v1.0.1, latest) | SHA256 |
|---|---|
| `llemonAI-Reader-1.0.1-android.apk` | `DE3F80C6B3B15E05248D0B80537401D667D13BF61792D154CD111F4A431F169D` |
| `llemonAI-Reader-1.0.1-win-x64.exe` | `559D4A0CC8590E71CE2F3E5ADDE0A5539D926A7D85D307A11209C07C8629B39B` |
| `llemonAI-Reader-1.0.1-win-x86.exe` | `6D85ADF03D58BC12D0B7E9E578D23611D815574BF98AF2C18B700DE8B897F5A1` |

Previous version:

| File (v1.0.0) | SHA256 |
|---|---|
| `llemonAI-Reader-1.0.0-android.apk` | `49046C676427DE5DA3C0B3103664BDCA0852B6FB43FB347276679DE7E63E0237` |
| `llemonAI-Reader-1.0.0-win-x64.exe` | `CA430579EF5CA4F04D08E0ACA47F2D6CFF74D5B7A75938490E5EB7995C299FC3` |
| `llemonAI-Reader-1.0.0-win-x86.exe` | `7B733114494D54BF816A15317C1726C084251A39970A07D22A05BE1C7028F6B4` |

## Repo contents

This repository holds only the release binaries and this README. The application source code is not public.

Third-party open-source components are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contact

llemonai.us@gmail.com

&copy; 2026 llemonAI (llemonai.in). All rights reserved.