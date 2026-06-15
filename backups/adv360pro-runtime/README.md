# Adv360 Pro Runtime Snapshots

This folder contains live runtime data read from the keyboard through Kinesis
Clique / ZMK Studio RPC.

`clique-keymap-2026-06-15.json` was captured from the connected Adv360 Pro with
the read-only `keymap.getKeymap` RPC after unlocking the keyboard for Clique
access. It records the keyboard's runtime layer names and raw binding IDs:

- `MAC`
- `WINDOWS`
- `FUNCTIONS`
- `Kp`
- `Mod`

The numeric `behaviorId`, `param1`, and `param2` values are the raw values
reported by the firmware. This is not decompiled source and does not replace
`config/adv360.keymap`; it is a faithful runtime snapshot for backup and
comparison.
