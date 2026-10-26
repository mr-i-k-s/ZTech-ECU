<h1 align="center">ZTech ECU</h1>

<p align="center">
  <img src="docs/assets/logo.png" alt="ZTech ECU" width="640">
</p>

<p align="center">
  <img alt="Status"   src="https://img.shields.io/badge/Status-in%20Entwicklung-yellow">
  <img alt="MCU"      src="https://img.shields.io/badge/MCU-ATmega32U4-orange">
  <img alt="Tuning"   src="https://img.shields.io/badge/Tuning-TunerStudio-informational">
  <img alt="License"  src="https://img.shields.io/badge/License-GPLv3-green">
  <img alt="Issues"   src="https://img.shields.io/github/issues/mr-i-k-s/ztech-ecu">
  <img alt="Commit"   src="https://img.shields.io/github/last-commit/mr-i-k-s/ztech-ecu">
</p>

<p align="center">
  <b>Ein quelloffenes, DIY-freundliches Motorsteuergerät (ECU) auf STM32-Basis.</b>
</p>

---

## Über das Projekt

Die ZTech ECU v3 ist ein frei verfügbares Motorsteuergerät – Hardware, Firmware und
Konfiguration an einem Ort. Abgestimmt wird über TunerStudio (Signatur `speeduino`),
geflasht wird komfortabel per DFU. Ziel ist eine nachbausichere, bezahlbare ECU für
Bastler und Enthusiasten.

## Features

- STM32-basiert, kompakt, für den realen Motoreinbau
- TunerStudio-kompatibel (Signatur `speeduino`)
- Offene Firmware, per DFU flashbar
- Schaltplan, Pinbelegung und Stückliste frei verfügbar

## Dokumentation

Die ausführliche Anleitung folgt in Kürze. *(Platzhalter für den späteren Wiki-Link.)*

## Firmware flashen

> [!WARNING]
> Firmware **ausschließlich per DFU** flashen – kein ISP-Erase, sonst ist der
> Bootloader weg. Bootloader-Modus nur über den BOOT-Taster aktivieren.

## Mitmachen

Issues und Pull Requests sind willkommen. Aufbau des Repos und Hinweise folgen.

## Lizenz

Veröffentlicht unter der GPL-3.0-Lizenz.
