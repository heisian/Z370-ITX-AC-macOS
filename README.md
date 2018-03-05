# Z370-ITX-AC-macOS
This is a working EFI/Clover configuration complete with config.plist and applicable kexts for macOS 10.12.6.

PC Part Picker build: https://pcpartpicker.com/b/8zFtt6

## macOS version
~~`10.13.3`~~ `10.12.6`

**NOTE:** I previously published config for 10.13.3, however due to the current
NVIDIA drivers causing massive lag, and the inability to get older versions
of the drivers to boot, I have downgraded to 10.12.6. This is the current
config that gives the best performance for _this hardware config_.
If the NVIDIA drivers for 10.13.3 ever get fixed, I will publish an update here.

## System Specs
* ASRock Z370M-ITX/ac
* Intel i7-8700K 3.7GHz
* G.Skill Ripjaws V Series 16GB (2 x 8GB) DDR4-2400 Memory
* Crucial MX300 275GB M.2-2280 Solid State Drive
* Gigabyte GeForce GTX 1050Ti
* Corsair SF 450W 80+ Gold Certified Fully-Modular SFX Power Supply
* IOGEAR Bluetooth 4.0 USB Micro Adapter, GBU521

## Post-install
* Audio install script: https://github.com/toleda/audio_CloverALC/blob/master/audio_cloverALC-130_v0.4.command
* NVIDIA web drivers: https://images.nvidia.com/mac/pkg/378/WebDriver-378.05.05.25f06.pkg
* SmUUID and Serial Number generation for iMessage. Search the forums!

## Working
* Displayport Dual 4k monitors
* ~~APFS~~ (Worked in 10.13.3 config)
* Sleep
* Audio
* ~~FileVault~~ (Worked in 10.13.3 config)

The motherboard's built-in Bluetooth and WiFi module does NOT work with macOS.
You will need to get a compatible module for the M.2 slot, or use a USB
Bluetooth dongle (listed above).
