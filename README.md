# MakoAnswer Glance — releases

Signed Windows installers for **MakoAnswer Glance**, a small always-on-top
monitor for [makoanswer.com](https://makoanswer.com).

There is no source code here. This repository exists only to host release
artifacts, so the app can check for and download updates without carrying a
credential — a token shipped inside a desktop binary is a token given away.

## Install

Download the latest `MakoAnswerGlance-Setup.exe` from
[Releases](../../releases/latest) and run it. It installs per-user, so it never
asks for an administrator prompt, and it updates itself from here after that.

Every installer is signed by **Mako Logics LLC** via Azure Trusted Signing.
If Windows ever warns you that an installer is unsigned or from an unknown
publisher, it did not come from us — do not run it.

## Requirements

- Windows 10 or 11, 64-bit
- Microsoft Edge WebView2 (already present on Windows 11 and anywhere Edge is
  installed; the app tells you and links to it if it is missing)

A MakoAnswer admin sign-in is required to see any data.

---

© Mako Logics LLC
