# Introduction #

Potential wireless detection methods:
  1. NFC
  1. RFID
  1. WiFi
  1. Bluetooth

# Exploration #

## NFC ##
Due to the wireless band that NFC operates at, it's maximum range is approximately 10 centimeters. Using NFC to track personnel would require the deliberate scanning of NFC enabled devices. NFC is a specific type of RFID.

RFID/NFC reader/writer: https://www.adafruit.com/products/364

### NFC Tags ###
See: http://nfc-forum.org/our-work/specifications-and-application-documents/specifications/nfc-forum-technical-specifications/
#### Type 1 Specification ####
  * Standard: ISO/IEC 14443A
  * Permissions: Read and re-write capable (configurable to be read-only)
  * Storage: 96 bytes expandable to 2KB
#### Type 2 Specification ####
  * See Type 1
  * Storage: 48 bytes expandable to 2KB
#### Type 3 Specification ####
  * Standard: JIS X 6319-4 (FeliCa)
  * Permissions: Preconfigured as read/re-write or read-only
  * Storage: up to 1MB
#### Type 4 Specification ####
  * Standard: ISO/IEC 14443
  * Permissions: Preconfigured as read/re-write or read-only
  * Storage: up to 32KB

### Standards ###
  * ISO/IEC 14443: defines
  * ISO/IEC 18000-3

## RFID ##

Depending on the tag / receiver, the maximum distance is variable. You can have anywhere from 10 centimeters of detection range, to 12 meters and beyond.

See: http://skyrfid.com/RFID_Tag_Read_Ranges.php

More specifically: http://www.skyrfid.com/index.php?pr=RFID_HealthCare_Management

A good read on cost -> detection range: http://changelog.complete.org/archives/7589-a-linux-based-rfid-thing-finder

Open source initiatives:
http://www.openbeacon.org/
http://www.openpcd.org/

<To be expanded>

## WiFi ##


&lt;content&gt;



## Bluetooth ##
- This can interact with a device from over 30 ft away.
- It requires that the device sync with the bluetooth device... which is a disadvantage to NFC's ability to be instantaneous.
- It can also pick up signals of other devices in the area and produce false, untrustworthy results.
- It seems counter productive to have to sync with the bluetooth system in order to sanitize your hands.

See: http://www.ioncannon.net/programming/1603/turn-a-raspberry-pi-into-an-ibeacon/