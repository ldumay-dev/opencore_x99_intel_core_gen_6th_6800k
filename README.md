# OpenCore - X99 - i7 Gen 6th - i7-6800k

## Description

FR : Ce projet à pour but simple de testé macOS sur une configuration fixe avant la migration futur vers un véritable MacPro, ainsi que de pouvoir explorer les nombres possibles de développement sur, dans et pour macOS (=> apprendre l'ingénierie système bas niveau).

EN: The simple aim of this project is to test macOS on a fixed configuration before the future migration to a real MacPro, as well as to explore the possible numbers of developments on, in and for macOS (=> learn low-level systems engineering).

## Configuration obtenue

### Dates de test

- Premiers essais : 2024-06-11
- Derniers essais : 2024-06-14
- Durée de test de cette version : actuel (last: 2024-09-10)

### Verions testé de MacOS :

- MacOS Ventura (13.6.7) : ✅
- MacOS Sonoma (14.5) : ❌ (ne passe pas)

### Configuration

<img src="SCREENSHOTS/test_0.1_img_001.png" max-width="300px" />

- Target OS:
    - Mac computer: **Mac Pro - MacPro7,1** 
    - Mac OS version: **macOS Ventura (13.6.7)**
- Computer:
    - Power supply: **Corsair RM 1000W**
    - Motherboard: **GA-X99-UD4**
    - CPU: **Intel Core i7 6800K @ 3,40Ghz 6 Cores**
        - Architecture: **Broadwell E**
    - RAM: **32 Go - 8x 8Go 3200Mhz DDR4**
    - GPU: **AMD Readeon RX 6600 XT 8Go**
    - Screen:
        - Screen 1: **DELL P2310H 28"**
            - Size: **28"**
            - Resolution: **3840x2160**
            - Refresh rate: **60Hz**
            - Interface: **DisplayPort**
            - Disposition: **Payage**
        - Screen 2: **DELL P2310H 23"**
            - Size: **23"**
            - Resolution: **1920x1080**
            - Refresh rate: **30Hz**
            - Interface: **HDMI**
            - Disposition: **Portrait**
        - Screen 3: **DELL P2311H 23"
            - Size: **23"**
            - Resolution: **1920x1080**
            - Refresh rate: **30Hz**
            - Interface: **HDMI**
            - Disposition: **Portrait**
    - Network:
        - Ethernet: ***[...]***
        - Wifi & BT: Intel ***[...]***
    - Storage disk: SSD Crucial BX500 SATA 6 Gb/s 2.5"
        - Read: **540** Mo/s
        - Write: **500** Mo/s
    
> **NB:**
>   - FR: Avec macOS Ventura, j'ai ressenti des ralentissements lors de grosse charge d'écriture sur le disque dur. Il est possible que cela soit fortement dû au SSD, mais aussi au processeur qui commence à vieillir pour de nouveaux OS.
>    - EN: With macOS Ventura, I experienced slowdowns during heavy write loads on the hard disk. This may be largely due to the SSD, but also to the processor, which is starting to age for new OS.

For more information : [All screenshots](DOCS/0_All_Screenshots.md)

### Functional features

- Bootloader:
    - OpenCore: ✅
- USB installation key:
    - Starting the installer: ✅
    - Start installation: ✅
    - Finalize installation: ✅
- In OS:
    - PC components
        - Interface elements: ✅
        - Screens: ✅
            - Screen 1: 🔄 (but not in 60Hz)
            - Screen 2: ✅
            - Screen 3: ✅
        - USB ports: ✅
        - Sound: ✅
        - Microphone: ✅
        - Webcam: ✅
        - Ethernet: ✅
        - WIFI: ❌
        - Bluetooth: ❌
    - OS components
        - All native apps: ✅
        - iCloud: ✅
        - Collaborate: ✅
        - App Store: ✅
        - System Preferences: ✅
            - Stability :🔄
        - System updates: 🤷‍♂️