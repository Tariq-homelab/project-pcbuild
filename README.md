# project-pcbuild

This project documents the full assembly of a second custom-built PC intended for lab virtualization, development, and general high-performance computing. It includes part selection, build process, and configuration notes. All parts were sourced from Amazon.sa or trusted local sellers.

---

## Hardware List

| Component         | Model & Specs                                                                                   | Price (SAR) | Quantity | Total     |
|------------------|--------------------------------------------------------------------------------------------------|-------------|----------|-----------|
| CPU              | AMD Ryzen 5 8500G / 6-Core / 3.5GHz / AM5                                                        | 590         | 1        | 590 SAR   |
| Motherboard      | MSI PRO A620M-B / AM5 / mATX                                                                     | 335         | 1        | 335 SAR   |
| RAM              | Kingston FURY Beast EXPO / DDR5 / 64GB (2×32GB) / 6000MHz / CL30 / White                         | 824         | 1        | 824 SAR   |
| SSD              | Kingston NV3 / NVMe PCIe 4.0 / 1TB / M.2 2280 / SNV3S/1000G                                      | 225.30      | 1        | 225.30 SAR|
| PSU              | FSP HYPER 80+ PRO / 650W / ATX 3.0 / 80PLUS Bronze 230V / Bulk                                   | 245         | 1        | 245 SAR   |
| Case             | GAMEON Emperor Midnight II                                                                       | 269         | 1        | 269 SAR   |

Total Cost: ~SAR 2,489.30

---

## Build Status

- Parts purchased  
- PC fully assembled  
- BIOS configured (SVM enabled, EXPO profile set)  
- System successfully boots and is stable under load  

---

## BIOS Configuration

- Enabled SVM Mode (AMD-V) for virtualization
- Enabled EXPO Profile for DDR5-6000 RAM performance
- Verified 64GB RAM (2×32GB) detected properly
- NVMe SSD recognized as bootable device
- No BIOS update required at time of build

---

## Notes

- All passwords, serial numbers, and BIOS screenshots are stored securely in Bitwarden.  
- This PC will serve as a Proxmox host and general virtualization lab system.
- SSD was sourced from local vendor Click Tera via Amazon.sa.

---

## Photos

Images to be added once documentation screenshots are complete.
