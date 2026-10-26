<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo-dark.png">
    <img alt="ZTech ECU" src="logo-light.png" width="180">
  </picture>
  <h2>Engine Control Unit</h2>
</div>

<p align="center">
  <img alt="Status"   src="https://img.shields.io/badge/Status-in%20development-yellow">
  <img alt="Firmware" src="https://img.shields.io/badge/Firmware-v0.01-blue">
  <img alt="MCU"      src="https://img.shields.io/badge/MCU-ATmega32U4-orange">
  <img alt="Tuning"   src="https://img.shields.io/badge/Tuning-TunerStudio-informational">
  <img alt="License"  src="https://img.shields.io/badge/License-GPLv3-green">
  <img alt="Issues"   src="https://img.shields.io/github/issues/mr-i-k-s/ztech-ecu">
  <img alt="Commit"   src="https://img.shields.io/github/last-commit/mr-i-k-s/ztech-ecu">
</p>

<p align="center">
  <b>An open-source, DIY-friendly Engine Management System (ECU) based on ATmega32U4.</b>
</p>

---

## About

ZTech ECU is an open engine management system – hardware, firmware and
configuration in one place. Tuning is done through TunerStudio, and flashing is done conveniently over USB. The goal is an affordable, simple, reproducible ECU for hobbyists and enthusiasts.

## Features

- ATmega-based, compact, built for real in-vehicle use
- TunerStudio compatible
- Open firmware, flashable over USB DFU Bootloader
- Schematic and Code freely available

## Documentation

Full documentation coming soon.

## Flashing the firmware

> [!WARNING]
> Flash the firmware **over USB DFU Bootloader only** – no ISP erase, or the bootloader will be
> lost. Enter bootloader mode only via the BOOT button.

## Contributing

Issues and pull requests are welcome.

## License

Released under the GPL-3.0 license.
