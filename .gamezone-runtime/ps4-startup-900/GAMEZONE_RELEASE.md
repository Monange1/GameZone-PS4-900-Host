# GameZone managed PS4 9.00 startup package

This package is the approved local browser host for the GameZone PS4 firmware 9.00 route.

## What it does

1. The Hub PC serves this folder on the game-zone LAN.
2. The operator opens `start.html` from the PS4 browser once to save the offline startup files.
3. After every cold boot, the operator opens the cached GameZone startup page and starts GoldHEN.
4. GoldHEN PayLoader AutoRun starts the installed GameZone tracker.

## Certified runtime

| Item | Value |
| --- | --- |
| Firmware | PS4 9.00 only |
| GoldHEN | 2.4b18.10 |
| Payload | `payload.bin` |
| SHA-256 | `c6329401d1810e16c84e6474ac30977dbdc951987c10cdb559370de7d59db0b0` |
| Payload size | 290016 bytes |

The branding in `start.html` may change. Do not modify the exploit modules, cache resources, or `payload.bin` without a new hardware-certification run.

## Field use

Use the Hub’s PS4 Setup screen to inspect the console first. Install only when it reports firmware 9.00 and the managed runtime activation receipt is present. Consoles on older 9.00 GoldHEN releases are migrated to this package before the tracker is installed.
