# Hackintosh-Opencore-6-HP-Z2-G4-MT
Opencore source for HP Z2 G4 workstation (Tower Case)


Work well with opencore 6.0 Catalina 10.15.6

iMac (Retina 5K, 27-inch, 2019)

i5-9400 with UHD 630

4K monitor

Ethernet I219LM7 - work

Wifi BCM94360CS2 realmac 

iMess/Facetime work

Sleep/Wake work

USB work

front headphone jack work  

--

Fixed RTC0 BIOS error 005 when restart 

BIOS config:
Disable legacy boot & sercue boot
Disable RAID
-----
I have disable external GPU because nVIDIA 1060 3GB was plug into this machine. YOu need to change config.plist if you want to use AMD graphic card.

---
Please follow this guide for optimize power consumtion depend on your CPU (not include in this package)
https://dortania.github.io/OpenCore-Post-Install/universal/pm.html#lfm-low-frequency-mode
