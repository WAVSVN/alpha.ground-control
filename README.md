# Ground Control — alpha installs

**Friend-test Windows and Mac (Apple Silicon) builds.** There is no application source in this repository.

| | |
|--|--|
| **Download** | [Latest release](https://github.com/WAVSVN/alpha.ground-control/releases/latest) |
| **Source** | Private (not published here) |

## Install (Windows)

1. Open the latest release and download the `.exe` installer (NSIS).
2. If SmartScreen warns: **More info → Run anyway** (unsigned alpha).
3. Launch **Ground Control**. Newer alphas can prompt to update in-app (`latest.json` on the Release).

## Install (macOS, Apple Silicon)

1. Open the latest release and download the `.dmg`.
2. Open the DMG and drag **Ground Control** to Applications (or run from the volume).
3. Gatekeeper may block unsigned alphas: **right-click the app → Open**, then confirm Open. If needed:
   ```bash
   xattr -dr com.apple.quarantine "/Applications/Ground Control.app"
   ```
4. Intel Mac is not supported in this alpha channel yet.

## Support

Ping the person who sent you this link. Do not open security issues against this empty releases repo.
