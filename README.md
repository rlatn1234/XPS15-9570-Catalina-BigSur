# DELL XPS15 9570 MacOS Catalina/Big Sur

MacOS Catalina EFI with **CLOVER / Opencore Bootloader**

Clover Bootloader supports MacOS Catalina 10.15.6(19G2021)

OpenCore Bootloader supports MacOS Big Sur 11.2.3(20D91)


# HARDWARE Spec.

* i7-8750H
* UHD630
* GTX1050Ti Max-Q
* 16GB RAM
* 4K INFINITYEDGE Display
* WD SN550 NVME 1TB
* ALC298
* DW1560

## Testing

* Thunderbolt 3 Localnode (firmware flash)


## Working

| Feature | Status | Notes |
| ------------- | ------------- | ------------- |
| **UHD630** |  Working | Fully supported|
| **ALC298** |  Working  | To fix headphones install [ALCPlugFix-Swift](https://github.com/black-dragon74/ALCPlugFix-Swift/releases/tag/1.4) |
| **Wifi/BT** |  Working | Replace with working card will work ex) DW1560 DW1820a|
| **Thunderbolt** | Testing | Need more peripheral devices to test |
| **GTX1050Ti** |  X | NEVER GONNA WORK |
| **UnderVolting** | Working |Use [SmartCPUKor](https://github.com/rlatn1234/smart-cpu)  [SmartCPUENG](https://github.com/tctien342/smart-cpu)


## BIOS Settings

* BIOS: 1.18.1
* (Using OC) MacOS Big Sur 11.2.3(20D91)
