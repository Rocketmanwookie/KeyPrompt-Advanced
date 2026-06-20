# Versioning Policy

Date created: 2026-06-20

## Product Documentation

Use semantic versioning for documentation packages:

- `v0.1.0` — initial repository skeleton
- `v0.2.0` — baseline requirements and architecture
- `v0.3.0` — BOM and safety model complete
- `v0.4.0` — diagrams complete
- `v0.5.0` — verification and validation plans complete
- `v1.0.0` — build-ready release

## Hardware

Use revision letters:

- `Rev A` — first bench prototype
- `Rev B` — corrected prototype
- `Rev C` — enclosure-integrated prototype
- `Rev D` — manufacturable preproduction concept

## Firmware

Use semantic versioning per firmware package:

- `esp32-hmi v0.x`
- `rp2040-keyboard-hid v0.x`

## Rule

Every change affecting safety behavior, power architecture, wiring, battery protection,
HID output, or enclosure interlock must be recorded in `CHANGELOG.md` and the applicable
decision log.
