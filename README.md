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

| File (v2.0.2) | SHA256 |
|---|---|
| `llemonAI-Reader-2.0.2-android.apk` | `7E47C785EFA86FA9AF26541451D5EDF50C5DD060EFF57AD4BBB60AEAA0E3FF7D` |
| `llemonAI-Reader-2.0.2-macos.dmg` | `36E5F59B13B3266340CE7C0CA97B8C22784D73B585FC3BCE50EA89315F501A78` |
| `llemonAI-Reader-2.0.2-macos.zip` | `D7E5E1F9157BF1E5F47F4693FA3DBA4DDC786A4090EFC6CF47C69AA288362348` |
| `llemonAI-Reader-2.0.2-win-x64.exe` | `54D1FF5CC60C0E0E6D9A6109FE2EFBD774BE84B8145F02DCD3503607AC65A359` |
| `llemonAI-Reader-2.0.2-win-x86.exe` | `37CC16941C3EC980F9E61236AABFB8D6A3B85A03F03AB8ED8FB976D239EB2B3C` |

## Repo contents

This repository holds only the release binaries and this README. The application source code is not public.

Third-party open-source components are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contact

llemonai.us@gmail.com

&copy; 2026 llemonAI (llemonai.in). All rights reserved.