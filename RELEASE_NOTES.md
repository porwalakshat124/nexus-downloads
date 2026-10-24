# Nexus 0.8.0 - Ready when Windows starts

- Start Nexus automatically after Windows sign-in. The installer offers startup registration, and Settings > General lets you change it. Startup stays quiet; duplicate startup launches do not open a message box.
- Uninstall removes the startup entry, including when startup was enabled later from Settings.
- Update checking now reads a public download feed while the application source repository stays private. The download page is always accessible, even if an automatic check fails.
- New Nexus website with real application screenshots, keyboard-accessible feature tabs, responsive layouts and direct version-labelled setup downloads. The website refreshes its download feed automatically after each published release.
- Public binary distribution runs only after build, installer, UI smoke and uninstall checks. SHA-256 checksums accompany each installer and portable ZIP. Desktop debug symbols are excluded from new release packages.
- Expanded UI diagnostics cover all Settings categories as well as normal and short layouts across 21 tool pages. Startup command validation is included in Windows checks.

Website: https://nexus-island.vercel.app
Public downloads: https://github.com/porwalakshat124/nexus-downloads/releases

Windows 10 2004+ / Windows 11 x64. Runtime included. Exit Nexus before updating; local settings are retained. This is an unsigned Windows preview.
