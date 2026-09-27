# SwiftyTool releases

Downloads for the SwiftyTool Mac apps — https://swiftytool.com

This repository only hosts the release files (the apps' source is not here).
Each release is tagged `<app>-v<version>` and contains:

- `Swifty<App>-<version>.dmg` — signed with a Developer ID certificate, notarized by Apple and stapled
- `Swifty<App>-<version>.zip` — the same app, zipped
- `SHA256SUMS.txt` — checksums of both files

Check a download: `shasum -a 256 -c SHA256SUMS.txt`

| App | Releases |
|---|---|
| SwiftyHosts | Coming soon |

Questions and bug reports: hello@swiftytool.com
