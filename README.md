# project-pcbuild

This project documents the full assembly of a custom-built PC intended to host my Proxmox homelab environment. It includes part selection, hands-on assembly, BIOS configuration, and successful first boot. All components were sourced from Amazon.sa.

---

## Hardware List

| Component         | Model                                                    | Price (SAR) |
|------------------|-----------------------------------------------------------|-------------|
| CPU              | AMD Ryzen 5 8500G 6-Core 3.5GHz (AM5)                     | 590         |
| Motherboard      | MSI PRO A620M-B AM5 mATX                                  | 335         |
| RAM              | Kingston FURY Beast DDR5 64GB (2×32GB) 6000MHz CL30       | 824         |
| SSD              | Kingston NV3 NVMe PCIe 4.0 1TB                            | 225.30      |
| Case             | GAMEON Emperor Midnight II Series                         | 269         |
| PSU              | FSP HYPER 80+ PRO 650W 80PLUS Bronze ATX 3.0              | 245         |

**Total Cost:** ~SAR 2,488

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

### 5. Motherboard Shield and Case Setup
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
- Confirmed 1×32GB DDR5 recognized (second stick added after initial boot)  
- No BIOS update required  

---

## Result

The system booted successfully after an initial RAM debug LED issue. After reseating one RAM stick, the machine powered on and displayed the BIOS interface. This machine is now ready for Proxmox installation and lab virtualization work.

---

## Notes

All root credentials, BIOS notes, and system passwords were stored securely in Bitwarden.
