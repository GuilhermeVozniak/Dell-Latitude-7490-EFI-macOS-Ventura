# Dell Latitude 7490 Hackintosh EFI
# macOS 11.x BigSur with Intel Wireless via AirportItlwm

Note: My laptop was sold in April 2024 and no more updates will be available.

## Tested macOS version:
macOS 13.3.1 Ventura using OpenCore 0.9.2

## System configuration
- Intel Core i5-8350U 1.7GHz
- 16GB DDR4-2400MHz RAM (8GB+8GB)
- Intel UHD Graphics 617 or 620 *not sure*
- Samsung SSD 970 EVO 500GB
- Intel Dual-Band Wireless-AC 8265

## Confirmed working
1) Loudspeaker
2) 3.5mm headphone jack^
4) Battery Management
5) Backlight Control (Fn+B & Fn+S)
6) Ethernet
7) Touchpad with Gestures
8) WiFi (2.4/5GHz) via AppleItlwm) _(Update: Updated kexts to v2.1.0)_
9) Bluetooth Audio*
10) USB-C Power Delivery for Charging (Apple 61W, Ugreen 65W)
11) Barrel Plug for Charging (Dell 90W)
12) FileVault
13) CPU SpeedStep
14) iGPU Acceleration
15) Native hotkey support with Fn keys
16) Dual-booting with Windows (Native dual-boot, not through BootCamp / Parallels)
17) HDMI output
18) SideCar using USB-A to lightning _(tested on iPad 7th/9th generation, WiFi+Cellular)_
19) Display Port & HDMI over USB-C
20) USB-C Data Transfer (slow speed)

^_3.5mm headphone jack might not work properly after system wakes from sleep, reboot will resolve the issue._


## Not working
1) TrackPoint

## Potential issues
1) Sleep mode not activating - Causing kernel panics very rare but it happends some times

## Unknown (not tested)
1) Intel TurboBoost (Unable to monitor)
2) Handoff and Airdrop (Likely not working due to AppleItlwm Limitations)
3) WWAN
4) SD Card Reader
5) ThunderBolt and Touchscreen (SKU did not include)
6) SideCar over WiFi
