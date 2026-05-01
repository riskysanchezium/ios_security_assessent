# iOS Security Assessment Toolkit (iOS‑SAT)

## ⚠ Authorized Use Only

**iOS‑SAT is a security research and penetration testing toolkit intended ONLY for devices you own or have explicit, written authorization to assess.**

Unauthorized use against devices you do not own or control may violate:
- Computer Fraud and Abuse laws
- Wiretap laws
- Local and international regulations

By using this tool, you accept full responsibility for its use.

---

## Overview

iOS‑SAT is a modular Bash‑based toolkit designed for **iOS security assessments on checkm8‑vulnerable devices (A5–A11)**.

It consolidates:
- Device enumeration
- Backup and artifact analysis
- SSH ramdisk workflows
- Jailbreak‑assisted runtime testing
- Application inspection
- Frida script generation

---

## Supported Targets

| Category | Supported |
|--------|----------|
| SoCs | A5–A11 |
| Devices | iPhone 5S → iPhone X |
| iOS | 12.x – 16.x (partial 17.x/18.x research) |
| OS | Kali / Debian‑based Linux |

⚠ A12+ (iPhone XS and newer) are **NOT supported** for bootROM exploitation.

---

## Features

- Dependency validation & automated setup
- libimobiledevice built from source
- SSH ramdisk workflows via checkm8
- Backup discovery & analysis guidance
- Application & AFC inspection
- Frida script templates for:
  - SSL pinning checks
  - Biometric logic testing
  - Jailbreak detection evaluation

---

## Installation

```bash
git clone https://github.com/your-org/ios-sat.git
cd ios-sat
chmod +x ios-sat.sh
./ios-sat.sh
