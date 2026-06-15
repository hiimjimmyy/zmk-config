# Adv360 Pro Bootloader Snapshot

Captured from `/Volumes/ADV360PRO` on 2026-06-15 while the connected keyboard half was in UF2 bootloader mode.

The bootloader exposes `CURRENT.UF2`, which is a firmware image for the connected half. It does not expose the original ZMK source keymap. The source config in this repository is based on the Kinesis Adv360 Pro V3.0 config, which matches the visible firmware strings from the connected keyboard, including Zephyr 3.5, ZMK Studio strings, and Kinesis macro names.

Observed boot string from `CURRENT.UF2`:

```text
*** Booting Zephyr OS build dacab4875df7 ***
```
