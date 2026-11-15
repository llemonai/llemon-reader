# llemonAI Reader

A free PDF reader, annotator and presentation tool for **Windows**, **macOS** and **Android**, from [llemonai](https://llemonai.in). Made for advocates and lawyers, online tutors, lecturers, students and corporate trainers.

- **Website:** https://llemonai.in/reader.html
- **Download:** https://llemonai.in/reader.html#download
- **Latest release:** https://github.com/llemonai/llemon-reader/releases/latest

## What it does

- **Presentation mode (Windows and macOS):** a separate audience window shows only the PDF page on a projector or video call, while you keep all the controls, thumbnails and notes.
- **Whiteboard:** collect selected text, rectangular or freehand areas with their annotations, and connect them with arrows. Each box shows its page number and opens that page when clicked.
- **Side panel:** docked on the left and independent of the document, with the PDF's index, page thumbnails, notes, bookmarks and search.
- **Type and paste onto pages:** type on any page, such as an inserted blank page, with font, size, bold, italic, underline and colour, and paste text or pictures (screenshots, pictures from other apps) with Ctrl+V. Each also gets a whiteboard box that leads back to its page.
- **Annotations:** highlight, underline, circle, freehand pen, an eraser, sticky notes, notes on text or whole pages, and bookmarks for pages or comments.
- **Search:** finds single words or whole sentences.
- **Page management:** add blank pages, delete, drag to reorder, rotate, hide, or insert another PDF or Word file at any position.
- **Merging:** append PDF and Word (.docx) files.
- **Saving:** Save keeps annotations editable, Export master PDF burns them in and adds a notes appendix, and Print includes everything.
- **Privacy:** documents never leave your device.
- **Updates:** About → Check for updates downloads a newer release, checks its SHA-256 checksum and installs it. Nothing is checked unless you click it.

## Requirements

| Platform | Requirement |
|---|---|
| Windows | Windows 10 or 11, 64-bit or 32-bit. It's a single portable `.exe` with no installer and no admin rights, and it uses the Microsoft Edge WebView2 runtime built into Windows. |
| macOS | macOS 12 or later, Apple Silicon or Intel. Open the `.dmg` and drag the app to Applications. It isn't notarized by Apple, so the first time allow it in **System Settings → Privacy & Security → Open Anyway** ([steps](https://llemonai.in/reader.html#mac-open)). |
| Android | Android 8.0 (API 26) or later, as a sideloaded `.apk`. |

## Verifying downloads

The builds are signed with llemonai's own self-signed certificate (Windows), release key (Android) and an ad-hoc signature (macOS). Windows SmartScreen may show "Unknown Publisher", Android may warn about an unknown source, and macOS blocks the first launch until you click Open Anyway in Privacy & Security; all are expected.

To confirm a file is genuine, compare its SHA256 checksum. On Windows, run `certutil -hashfile <file> SHA256`; on a Mac, `shasum -a 256 <file>`.

| File (v2.0.3) | SHA256 |
|---|---|
| `llemonAI-Reader-2.0.3-android.apk` | `E4CC6F3F7138DEEED3B3272E1F444B588B8C3492BED0E6EB14F0C574FA921A20` |
| `llemonAI-Reader-2.0.3-macos.dmg` | `4C0FAE465E416E1C3CD480B5F06C389382E243D39A26A0DE590E38EF1CA5A6DE` |
| `llemonAI-Reader-2.0.3-macos.zip` | `5E396741BEA1F4823EC49630B663F8EEE103CF638027BBCE41059658544A62A2` |
| `llemonAI-Reader-2.0.3-win-x64.exe` | `A4461B6184E0D6891D2BC64CA8685DFC65C1C0D119CDAB88867857C3CB1648D2` |
| `llemonAI-Reader-2.0.3-win-x86.exe` | `72924FB7A4571C8154489D51169B1041758E1CDFBC05E44784F8FFB64F792788` |

## Repo contents

This repository holds only the release binaries and this README. The application source code is not public.

Third-party open-source components are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contact

llemonai.us@gmail.com

&copy; 2026 llemonAI (llemonai.in). All rights reserved.