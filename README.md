# llemonAI Reader

A free PDF reader, annotator and presentation tool for **Windows** and **Android**, from [llemonai](https://llemonai.in). Made for advocates and lawyers, online tutors, lecturers, students and corporate trainers.

- **Website:** https://llemonai.in/reader.html
- **Download:** https://llemonai.in/reader.html#download
- **Latest release:** https://github.com/llemonai/llemon-reader/releases/latest

## What it does

- **Presentation mode (Windows):** a separate audience window shows only the PDF page on a projector or video call, while you keep all the controls, thumbnails and notes.
- **Whiteboard:** collect selected text, rectangular or freehand areas with their annotations, and connect them with arrows. Each box shows its page number and opens that page when clicked.
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

| File (v2.0.0) | SHA256 |
|---|---|
| `llemonAI-Reader-2.0.0-android.apk` | `61FEE69B66F9CF0D6401BD7B64A8E5C73D3C780273549CF3150682A8AD4D65D9` |
| `llemonAI-Reader-2.0.0-win-x64.exe` | `02AEF96CF572E95EE93CA66B6C14CEF4DD3D9DF4D554272A61FCCD66D3930C21` |
| `llemonAI-Reader-2.0.0-win-x86.exe` | `9B8B037C7748848150E3D714FA35EFA98B0F131C62E06AB9D208293AA3228566` |

## Repo contents

This repository holds only the release binaries and this README. The application source code is not public.

Third-party open-source components are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contact

llemonai.us@gmail.com

&copy; 2026 llemonAI (llemonai.in). All rights reserved.