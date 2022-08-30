# EFI-Hackintosh- B560M Aorus Elite - i5 11400 OEM

Sucessful Big Sur installation with 11th Generation CPU and B560M Aorus Elite motherboard

## Current System Info

- Mac Pro (2019)
- MacOS Big Sur 11.6.8

## Hardware

|      Type       | Item                             |
| :-------------: | -------------------------------- |
|     **CPU**     | [ Intel Core i5 11400 OEM ]      |
| **Motherboard** | [ B560M Aorus Elite ]            |
|     **GPU**     | [ AMD Radeon R7 250 2 GB GDDR3 ] |
|     **SSD**     | [ KingSpec NVME 512GB ]          |

## Working hardware

- Audio: ALC897 - `AppleALC.kext` with boot-args `alcid=12`
- GPU: native working
- USB: `USBMap.kext` with my needs

## Important thing if you use this EFI:

Update **config.plist** in PlatformInfo > Generic with YOUR informations.
<br><br>
_1. MLB (Board Serial)
<br> 2. ROM (Mac Address)
<br> 3. SystemSerialNumber (Serial)
<br> 4. SystemUUID (SmUUID)_

Please use [_genSMBIOS_](https://github.com/corpnewt/GenSMBIOS/archive/refs/heads/master.zip) for generate values for above itens.
<br>
Please use [_ProperTree_](https://github.com/corpnewt/ProperTree/archive/refs/heads/master.zip) for configure/edit your config.plist.
