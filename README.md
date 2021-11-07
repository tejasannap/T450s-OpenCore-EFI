# T450s-OpenCore-EFI
My EFI folder for my hackintoshed Lenovo T450s using OC 0.6.4 and MacOS Big Sur

## I longer am in possesion of this laptop so this repository will no longer be updated :(

## WARNING: THIS EFI IS NOT BOOT READY, I HAVE REMOVED MY S/N AND SMBIOS SO PLEASE ADD YOUR OWN VALUES
## Specifications

```
- CPU: i7-5600U 2C/4T
- RAM: 8GB 1600MHz
- iGPU: HD 5500 (2040MB Patched)
- Display: 1920x1080 HD Touchscreen
- Wifi Card: Intel AC 7260
- Synaptics Trackpad/Trackpoint
- OpenCore 0.6.4
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

- Wifi (Airportitlwm) (Hit Or Miss sometimes)
- Handoff, Continuity, AirDrop (Airportitlwm)
- iMessage, FaceTime and all other iCloud related things
- Ethernet
- Onboard audio
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
