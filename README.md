# llemonAI Reader

A free PDF reader, annotator and presentation tool for **Windows**, **macOS** and **Android**, from [llemonai](https://llemonai.in). Made for advocates and lawyers, online tutors, lecturers, students and corporate trainers.

- **Website:** https://llemonai.in/reader.html
- **Download:** https://llemonai.in/reader.html#download
- **Latest release:** https://github.com/llemonai/llemon-reader/releases/latest

## What it does

- **Presentation mode (Windows and macOS):** a separate audience window shows only the PDF page on a projector or video call, while you keep all the controls, thumbnails and notes.
- **Whiteboard:** collect selected text, rectangular or freehand areas with their annotations, and connect them with arrows. Each box shows its page number and opens that page when clicked.
- **Side panel:** docked on the left and independent of the document, with the PDF's index, page thumbnails, notes, bookmarks and search.
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
| macOS | macOS 12 or later, Apple Silicon or Intel. Open the `.dmg` and drag the app to Applications. It isn't notarized by Apple, so the first time, right-click it and choose **Open**. |
| Android | Android 8.0 (API 26) or later, as a sideloaded `.apk`. |

## Verifying downloads

The builds are signed with llemonai's own self-signed certificate (Windows), release key (Android) and an ad-hoc signature (macOS). Windows SmartScreen may show "Unknown Publisher", Android may warn about an unknown source, and macOS asks you to confirm the first launch; all are expected.

To confirm a file is genuine, compare its SHA256 checksum. On Windows, run `certutil -hashfile <file> SHA256`; on a Mac, `shasum -a 256 <file>`.

| File (v2.0.1) | SHA256 |
|---|---|
| `llemonAI-Reader-2.0.1-android.apk` | `C98FAA65F4FDB4FD9C78C5217B8B62AEC2ADB35F3DF0D8716367C398D070DCFE` |
| `llemonAI-Reader-2.0.1-macos.dmg` | `666325E55168F3E5924809B0536DA3E0D4ECBAB3613C2FF09DC931FD011A4DF6` |
| `llemonAI-Reader-2.0.1-macos.zip` | `87D6A23139EC7E31C9E284A4603F4C2CCDE92046B1A9C7D6779FF399A63E688F` |
| `llemonAI-Reader-2.0.1-win-x64.exe` | `6BF9590E1DEB3514DEAD53182EBCEDB435B8A3DFEC5556D6AC7AA46F0B34774D` |
| `llemonAI-Reader-2.0.1-win-x86.exe` | `231E899C5ABE8130B5F90E2C7E0AA740C885C46C2D6EAAA3B71C70EC9DB66763` |

## Repo contents

This repository holds only the release binaries and this README. The application source code is not public.

Third-party open-source components are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contact

llemonai.us@gmail.com

&copy; 2026 llemonAI (llemonai.in). All rights reserved.