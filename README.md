# llemonAI PDF Annotator (formerly llemonAI Reader)

A free PDF reader, annotator and presentation tool for **Windows**, **macOS** and **Android**, from [llemonai](https://llemonai.in). Made for advocates and lawyers, online tutors, lecturers, students and corporate trainers.

- **Website:** https://llemonai.in/reader.html
- **Download:** https://llemonai.in/reader.html#download
- **Latest release:** https://github.com/llemonai/llemon-reader/releases/latest

## What it does

- **Presentation mode (Windows and macOS):** a separate audience window shows only the PDF page on a projector or video call, while you keep all the controls, thumbnails and notes.
- **Paper book mode (for advocates):** set the printed page numbers once; Go to page then takes the number the court uses, on a large keypad. Every appended file keeps its own page numbers, and Delete file removes appended files again.
- **Compare:** another page beside the one you are reading, such as two witnesses' statements or the evidence beside the judgment, to mark where they differ.
- **Switch to llemonAI Bare Acts:** when [llemonAI Bare Acts](https://github.com/llemonai/llemon-bare-acts) is on the same device, one button opens the act you need, with your notes on it, and another brings you back.
- **White paper:** numbered white pages beside the PDF with every whiteboard tool.
- **Whiteboard:** typed and handwritten notes, text and areas taken from pages, linked to their places in the PDF and grouped. Tapping a note opens each linked place in turn.
- **Scan with the camera:** a photo of a page is straightened, cleaned up and added as a new page.
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

| File (v2.0.5) | SHA256 |
|---|---|
| `llemonAI-Reader-2.0.5-android.apk` | `0D93166D4F09A81E479FB77AF6DCE816953CAC8EB526F24E3A6E394E58AB3D1F` |
| `llemonAI-Reader-2.0.5-macos.dmg` | `62C9CF0C21F786C7B53940D8B508E2D81565503B1805F67B80EC2E158E37AB8E` |
| `llemonAI-Reader-2.0.5-macos.zip` | `D6E45F321F23C17CF8B3C385294EE6E6F1553DECBAE1FB492B96A036DE36BEC3` |
| `llemonAI-Reader-2.0.5-win-x64.exe` | `D6EAAD0CC94382009663A0E147CB344F5A3BA22977B1FA07FC8EA1414EBF04DB` |
| `llemonAI-Reader-2.0.5-win-x86.exe` | `4D30646A20BB96EBA2A1D81A14DA251A7759D1F5DB9F7DE2A98210086FB4E210` |

## Repo contents

This repository holds only the release binaries and this README. The application source code is not public.

Third-party open-source components are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contact

llemonai.us@gmail.com

&copy; 2026 llemonAI (llemonai.in). All rights reserved.