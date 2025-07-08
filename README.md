# project-pcbuild

## Overview

This project documents the assembly of a custom-built PC to host my Proxmox homelab environment. It includes part selection, BIOS configuration, and final testing.

---

## Hardware List

| Component    | Model                                                             | Price (SAR) |
|-------------|--------------------------------------------------------------------|-------------|
| CPU         | AMD Ryzen 5 8500G 6-Core 3.5GHz (AM5)                              | 590         |
| Motherboard | MSI PRO A620M-B AM5 mATX                                           | 335         |
| RAM         | Kingston FURY Beast DDR5 64GB (2×32GB) 6000MHz CL30               | 824         |
| SSD         | Kingston NV3 NVMe PCIe 4.0 1TB                                     | 225.30      |
| Case        | GAMEON Emperor Midnight II Series                                  | 269         |
| PSU         | FSP HYPER 80+ PRO 650W 80PLUS Bronze ATX 3.0                       | 245         |

**Total Cost:** ~SAR 2,488

---

## BIOS Configuration

- Enabled SVM Mode (AMD-V) for virtualization support  
- Verified boot device priority  
- Confirmed 1×32GB DDR5 recognized (second stick added after initial boot)  
- No BIOS update required  

---

## Result

The system booted successfully after a RAM debug LED issue (resolved by reseating). The machine is now ready for Proxmox installation.

---

## Build Log Screenshots

### Parts & Preparation

- ![](images/00-parts-overview.jpg)  
- ![](images/01-esd-wrist-strap.jpg)

### Hardware Installation

- ![](images/02-installing-cpu.jpg)  
- ![](images/03-cooler-installed.jpg)  
- ![](images/04-ram-installed.jpg)  
- ![](images/05-nvme-installed.jpg)  
- ![](images/06-io-shield-installed.jpg)  
- ![](images/08-motherboard-installed.jpg)  
- ![](images/09-psu-installed.jpg)  
- ![](images/10-cable-routing.jpg)

### Power On & Boot

- ![](images/11-final-build-powered-on.jpg)  
- ![](images/12-first-boot-success.jpg)

---

## Notes

All passwords and BIOS settings are secured using Bitwarden CLI and GUI.
