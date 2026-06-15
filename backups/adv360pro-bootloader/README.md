# Adv360 Pro Bootloader Snapshot

Captured from `/Volumes/ADV360PRO` on 2026-06-15 while each keyboard half was in UF2 bootloader mode.

The bootloader exposes `CURRENT.UF2`, which is a firmware image for the connected half. It does not expose the original ZMK source keymap. The source config in this repository is based on the Kinesis Adv360 Pro V3.0 config, which matches the visible firmware strings from the connected keyboard, including Zephyr 3.5, ZMK Studio strings, and Kinesis macro names.

Captured images:

- `left-half-CURRENT.UF2`
  - SHA-256: `46b5efa869f37a7e73fb69da6f101d4add8cf219137af9eb639ebac51c68a7db`
- `right-half-CURRENT.UF2`
  - SHA-256: `5c9424061431883bd12a812f9008377688a0184856fef6fbf0d60ab66a11f2fa`
  - Contains `Adv360 Pro rt`, confirming it is the right-side image.

Observed boot string from both images:

```text
*** Booting Zephyr OS build dacab4875df7 ***
```
