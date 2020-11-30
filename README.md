# T450s-Catalina-EFI-OC
My EFI folder for my hackintoshed Lenovo T450s using OC 0.6.3 and MacOS Big Sur

## WARNING: THIS EFI IS NOT BOOT READY, I HAVE REMOVED MY S/N AND SMBIOS SO PLEASE ADD YOUR OWN VALUES
## Specifications

```
- CPU: i7-5600U 2C/4T
- RAM: 8GB 1600MHz
- iGPU: HD 5500
- Display: 1920x1080 HD Touchscreen
- Wifi Card: Intel AC 7260
- Synaptics Trackpad/Trackpoint
- OpenCore 0.6.3
- Dual Booted with Manjaro
```
## Bios

- `Security -> Security Chip`: **Disabled**;
- `Memory Protection -> Execution Prevention`: **Enabled**;
- `Virtualization -> Intel Virtualization Technology`: **Enabled**;
- `Internal Device Access -> Bottom Cover Tamper Detection`: must be **Disabled**;
- `Anti-Theft -> Current Setting`: **Disabled**;
- `Anti-Theft -> Computrace -> Current Setting`: **Disabled**;
- `Secure Boot -> Secure Boot`: **Disabled**;
- `UEFI/Legacy Boot`: **UEFI Only**;
- `CSM Support`: **Yes**.

## Working

- Wifi and Bluetooth (Airportitlwm) (Hit Or Miss sometimes)
- Handoff, Continuity, AirDrop (Airportitlwm)
- iMessage, FaceTime and all other iCloud related things
- Ethernet
- Onboard audio (also Hit or Miss sometimes)
- USB 2.0 / USB 3.0
- Battery
- Touchpad
- Trackpoint
- miniDP
- Touchscreen
- Webcam


## Not Working
- VGA
- Sleep/Wake
