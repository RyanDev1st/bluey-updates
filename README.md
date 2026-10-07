# Bluey Android updates

This public repository is Bluey's official APK release feed. The Android app reads `manifest.json` and verifies each APK against its SHA-256 checksum before opening the system installer. The Windows companion caches a verified release so a paired phone can update without internet after the PC has downloaded it.

The app's source code is kept in a separate private repository. Phone-to-PC pairing uses local Wi-Fi or Tailscale, not this update feed.
