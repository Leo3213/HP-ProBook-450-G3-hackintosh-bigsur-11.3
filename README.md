# HP-ProBook-450-G3-Hackintosh
My HP ProBook 450 G3 Hackintosh laptop configuration.


This Config uses Clover as the bootloader (but its the version 5133 which uses open core runtime) and I am currently running macOS BigSur 11.3 as OS

everything works that I'm aware of except:
  sleep when plugged in.
  sd card reader.

Laptop Specifications:

    Intel Core i7 6200U CPU (Skylake)
    Intel HD 520 Graphics
    8GB DDR4-2133MHz RAM
    15.6 Full HD Display
    Synaptics PS2 TouchPad
(THIS CARD WAS REPLACED WITH THE FOLLOWING!)


    2 USB 3.0 Ports, 2 USB 2.0 Ports
    HDMI Port
    SD Card Reader
    Kingston SSD disk A400 120GB (upgraded)
    sata m2 500 gb ssd.
    
    soon i will be repacing dvd drive with 1tb hdd
    for windows backups and mac timemachine backups 
    (it will be partioned in 2)

BIOS Setup:

    Disable Fast Boot
    Disable Power On when AC Detected
    Disable Power On when Lid is Opened
    Disable Secure Boot
    Disable Legacy Boot
    Enable Turbo Boost
    Enable Hyperthreading
    Enable Multi-Processor
    Enable VT-x
    Disable Wake on LAN
    Video Memory Size: 64MB
    Enable Runtime Power Management
    Disable Extended Idle Power States
    Enable Deep Sleep
    Disable Wake when Lid is Opened
    Disable Wake on USB
    Enable Power Control

What works:

    macOS BigSur 11.3
    UEFI booting via OpenCore
    Built-in keyboard (with special function keys)
    Built-in trackpad
    Brightness Control Hotkeys
    Audio Control Hotkeys
    HDMI Video and Audio
    Integrated Camera
    Native Wifi and Ethernet
    Bluetooth and AirDrop
    Native audio with AppleALC, including headphone
    Built-in mic
    Native power management
    Battery status
    USB 3.0 Ports
    Ethernet
    Audio on internal speaker and headphone
    Sleep and Wake (still need to fix sleep when plugged in. Otherwise perfect)

What doesn't work:

    Fingerprint Reader
    SD Card Reader

Thanks to:
The entire internet.

only 1% is my actual doing. this config is the result of many other config fixes and tips. I just combined them into a working config.

Most other guides were designed for the i5 version of this laptop, not the i7.

this is designed for the i7 variant.

(I rebuilt the config manually with the same settings so it wouldn't be corrupt)

Below is a link to my configuation

if anyone wants to make this config better for everyone let me know your fixes and ill include them and give you credit :)
