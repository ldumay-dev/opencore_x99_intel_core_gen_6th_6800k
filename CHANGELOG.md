# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added & Updated - Kext files

#### Added

- BlueToolFixup.kext : v2.6.9
- IntelBluetoothFirmware.kext : v2.4.0

#### Updated

- Lilu.kext : v1.6.7 to v1.7.0
- The config.plist

Result :
    - Main Config : **OK**
    - SSD M.2 NVME : **OK**
    - Ethernet : **OK**
    - Bluetooth : **NO**
    - WIFI : **NO**
    - GPU : **BETTER** 
        - ever no 60Hz for my 4K screen
        - small perfmance test : **Tour Flyover** with plan good, but slowed down by my CPU.
    - RAM : **CAUTION**
        - more memory cache used. No apps opened, just a vue on macOS.
	- 32Go : 7Go in cache / 13Go used => 30-40% used