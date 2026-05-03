---
layout: default
title: MarkyMD — Privacy Policy
description: Privacy policy for MarkyMD, a macOS Markdown viewer.
---

# Privacy Policy for MarkyMD

**Effective Date:** May 4, 2026
**Last Updated:** May 4, 2026

MarkyMD ("the App") is a read-only Markdown viewer for macOS developed by n-hgc (the "Developer"). This Privacy Policy explains how the App handles your information.

## Summary

**MarkyMD does not collect, transmit, or share any personal data.** The App performs no network communication — all processing happens entirely on your Mac.

## Information the App Accesses

To display Markdown files, the App accesses the following:

- The file and directory structure within the folder (Workspace) you select via the Open Panel
- The contents of `.md` files inside that folder (read-only)
- The last-modified timestamp of files (used for freshness badges and sorting)

This information is loaded into memory for display purposes only. The App does not copy, transmit, or persist it.

## Information the App Stores Locally

The App stores only the following inside its macOS Application Container:

- A Security-Scoped Bookmark that lets the App reopen the folder you selected
- Display preferences (whether the window stays in front, and whether it returns to the front on update)

This information is used solely to provide the App's core features and is never sent off your device.

## Information We Do Not Collect

- We do **not** collect any personally identifiable information (name, email, phone number, address, etc.).
- We do **not** use analytics or telemetry.
- We do **not** track you across apps or websites.
- We do **not** use advertising identifiers.
- We do **not** include any third-party SDKs.
- We do **not** transmit any data over the network.
- We do **not** send crash reports automatically.

## Network Communication

The App performs no network communication. All Markdown rendering libraries (markdown-it, Mermaid, KaTeX, shiki) are bundled with the App and are not fetched from external servers.

When you activate a link inside a document, the link is handed off to the system default browser. The App itself does not connect to the linked resource.

## Data Storage and Backup

Your data lives on your device. If you have iCloud Drive, Time Machine, or other macOS backup mechanisms enabled, Apple or the operating system may include the App's container data as part of those backups. Such backups are encrypted and managed by Apple or the OS — the Developer does not have access to them. For details, see [Apple's privacy practices](https://www.apple.com/legal/privacy/).

## Data Deletion

You can delete your data at any time:

- **By uninstalling the App:** remove MarkyMD from the Applications folder and delete `~/Library/Containers/com.nhgc.marky/` to remove all stored data.
- **From Terminal:** run `defaults delete com.nhgc.marky` to remove stored preferences.

## Children's Privacy

MarkyMD is suitable for users of all ages. We do not knowingly collect any data from children under 13 (or the equivalent age in your jurisdiction). Because the App does not collect any data at all, this condition is automatically met.

## Third-Party Components

The App bundles the following open-source libraries for Markdown rendering. These libraries run locally within the App and do not collect or transmit any data:

- [markdown-it](https://github.com/markdown-it/markdown-it) (MIT License) — Markdown parser
- [Mermaid](https://github.com/mermaid-js/mermaid) (MIT License) — Diagrams
- [KaTeX](https://github.com/KaTeX/KaTeX) (MIT License) — Math typesetting
- [shiki](https://github.com/shikijs/shiki) (MIT License) — Syntax highlighting

## Changes to This Policy

If we update this Privacy Policy, the new version will be reflected in a future update of the App and on this page. The Effective Date above will be revised accordingly.

## Contact

If you have any questions about this Privacy Policy, please reach out via our contact form:

[https://forms.gle/9KxrB2wHoNntRdCw5](https://forms.gle/9KxrB2wHoNntRdCw5)
