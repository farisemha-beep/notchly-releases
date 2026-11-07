# Notchly downloads

Public app archives and the update feed (`latest.json`) only. Source is private.

Apple Silicon, macOS 13+. Builds are ad-hoc signed and not notarized.

**First install (once):** download `Notchly.zip` from the latest Release, unzip, drag `Notchly.app` to Applications, then right-click > Open the first time. After that Notchly updates itself: it checks this feed at launch and every 6 hours, downloads and verifies the new build in the background, and swaps it in when the shelf is closed. Tray menu > Check for Updates… checks now.

**Rollback:** the previous version is kept in `~/Library/Application Support/Notchly/Previous`; every release stays in Releases.
