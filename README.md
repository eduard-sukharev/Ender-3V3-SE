# Marlin 3D Printer Firmware for Ender3 V3 SE printer

## What is this

This is a development fork for Creality Ender-3 V3 SE firmware, based off Marlin firmware for 3D Printers.

There're following new features:

 - Added auto-resizing bed-leveling grid cells to better fit larger grids on screen. Added new option for compact bed leveling grid view which allows viewing and editing up to 10x10 leveling grid.
 - Added "Input Shaping" menu to edit input shaping parameters that are enabled in stock firmware.
 - Added function to render a QR-code. No actual cutsom QR codes are added, only the basic implementation to add possibility to do so.
 - Added parsing print model metadata from GCode file to show correct print times, layer height and filament use.

## How to get these features

This is for developing and backporting features only, this is not intended for building end user firmware. If you want features from this fork, find different fork that builds binaries and ask them to merge these features to them.

