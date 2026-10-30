# Shovel Windows downloads

Windows installers and signed update feeds for Shovel, published by GlebHmarsky.

## Current update test: 0.30.105 → 0.30.106

1. Close Shovel and install [Shovel 0.30.105](https://github.com/GlebHmarsky/shovel-releases/releases/download/v0.30.105-win-stable/Shovel-Setup.exe).
2. Open Help → Shovel updates → Check and download.
3. Choose Restart and update to install 0.30.106.

If 0.30.103 or 0.30.104 reports a blocked restart with a newer settings profile, install 0.30.105 once over it. Those older builds do not support schema-6 settings. Do not delete settings or manually downgrade their schema number. The repaired build preserves the supported profile and saved layout.

The older Shovel Local Test 0.30.102 is an offline-only fixture and does not fetch these releases.

Windows publisher signing is not yet configured; Windows may show an unknown-publisher warning. The update feed is independently RSA-signed and package hashes are verified.

Source repository: https://github.com/GlebHmarsky/Shovel (currently private).