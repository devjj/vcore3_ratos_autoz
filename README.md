My Auto-Z Calibration setup for RatOS. My goal here
was to be able to include this single file in my
printer.cfg and have everything "just work"

If you use this, PLEASE ensure you review EVERY SINGLE
SETTING with regard to safe homing location, z hop,
probe locations, etc. I STRONGLY suggest lowering your
RatOS macro move speed so you have time to react
if something needs tweaking.

This file is provided as-is with no warranty.
Use at your own risk!

These plugins must be installed FIRST:
- PAM (https://github.com/HelgeKeck/pam)
- klipper_z_calibration (https://github.com/protoloft/klipper_z_calibration)

STLs were created by Stephen Lebed of the Rat-Rig Unofficial Discord community.
STEPs were created *from* the STLs via Fusion 360, as the originals were created
in 3ds max.

- Code is MIT licensed.
- STLs are CC BY-NC-SA 4.0

Better documentation will be forthcoming, and this repository will
eventually be a plug-in that can be installed in Moonraker.
