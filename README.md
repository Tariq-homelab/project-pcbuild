# project-pcbuild

This project documents the full assembly of a custom-built PC intended to host my Proxmox homelab environment. It includes part selection, hands-on assembly, BIOS configuration, and successful first boot. All components were sourced from Amazon.sa.

---

## Hardware List

| Component         | Model                              | Price (SAR) | Source     |
|------------------|-------------------------------------|-------------|------------|
| CPU              | AMD Ryzen 5 5600G                   | 611         | Amazon.sa  |
| Motherboard      | Biostar B550MH 3.0 Micro-ATX        | 364.16      | Amazon.sa  |
| RAM              | Crucial 32GB (2×16GB) DDR4-3200     | 246.71      | Amazon.sa  |
| SSD              | Kingston NV3 1TB NVMe Gen4          | 212.98      | Amazon.sa  |
| Case             | MSI MAG FORGE 100R w/ 4× RGB fans   | 213.58      | Amazon.sa  |
| PSU              | Cooler Master MWE 550W Bronze V2    | ~100        | Amazon.sa  |

**Total Cost:** ~SAR 1,750

---

## Build Log

### 1. Parts Overview
![Parts Overview](images/00-parts-overview.jpg)

### 2. Anti-Static Prep
![Wrist Strap](images/01-esd-wrist-strap.jpg)

### 3. CPU and Cooler Installation
![Installing CPU](images/02-installing-cpu.jpg)  
![Cooler Installed](images/03-cooler-installed.jpg)

### 4. RAM and NVMe SSD Installation
![RAM Installed](images/04-ram-installed.jpg)  
![NVMe Installed](images/05-nvme-installed.jpg)

### 5. Motherboard Shield and Fan Placement
![I/O Shield Installed](images/06-io-shield-installed.jpg)  
![Case Fans View](images/07-case-fans-view.jpg)

### 6. Motherboard and PSU Installation
![Motherboard Installed](images/08-motherboard-installed.jpg)  
![PSU Installed](images/09-psu-installed.jpg)

### 7. Cable Management and Final Routing
![Cable Routing](images/10-cable-routing.jpg)

### 8. Final Boot and BIOS Access
![Build Powered On](images/11-final-build-powered-on.jpg)  
![First Boot Success](images/12-first-boot-success.jpg)

---

## BIOS Configuration

- Enabled SVM Mode (AMD-V) for virtualization support
- Verified boot device priority
- Confirmed 1×32GB DDR4 recognized (second stick added after initial boot)
- No BIOS update required

---

## Result

The system booted successfully after an initial RAM debug LED issue. After reseating one RAM stick, the machine powered on and displayed the BIOS interface. This machine is now ready for Proxmox installation and lab virtualization work.

---

## Notes

All root credentials, BIOS notes, and system passwords were stored securely in Bitwarden.
