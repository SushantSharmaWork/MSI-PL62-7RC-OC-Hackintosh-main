# MSI-PL62-7RC-OC-Hackintosh

EFI folder for booting macOS Catalina 10.15.7 on a MSI PL62 7RC Laptop.

## Hardware Info & Specs (WIP)

| Part      | Model                                    |
| --------- | ---------------------------------------- |
| Processor | Intel i5-7300HQ (4C4T Kaby Lake)         |
| Memory    | DDR4 SODIMM, Supports Up to 64GB (2x 8G) |
| Storage   | 1x SATA @ SATA 3.0                       |

Hackintosh for my laptop- MSI pl62-7rc :

MSI pl62-7rc : (Also called MSI Prestige)

| Part      | Model                                                                                              |
| --------- | -------------------------------------------------------------------------------------------------- |
|CPU         | Intel Core i7 7700HQ @ 2.80GHz	Kaby Lake 14nm Technology                                        |
|GPU         |  GeForce MX150 - 2GB DDR4                                                                         |
|RAM         | 12.0GB Dual-Channel Unknown @ 1200MHz (2 ram used: 4gb, 8gb crucial)                              |
|MB          | Micro-Star International Co. Ltd. MS-16JD (U3E1) :HM175                                           |
|Audio Codec | 1. Intel Kaby Lake HDMI @ Intel Sunrise Point PCH - High Definition Audio Controller [D1]	PCI  |
|            | 2. Realtek ALC892 @ Intel Sunrise Point PCH - High Definition Audio Controller [D1]	PCI          |
|    		 |	                                                                                                 |
|Ethernet    | Qualcomm Atheros AR8171/8175 PCI-E Gigabit Ethernet Controller (NDIS 6.30)                        |
|Wifi/BT     | Intel Dual Band Wireless-AC 3168, Intel(R) Wireless Bluetooth(R).                                 |
|Touchpad    | Synaptics SMBus TouchPad- \_SB.PCI0.SBUS , Standard PS/2 Keyboard.                                |
|BIOS        | E16JDIMS.10F                                                                                      |
|Video card  |Intel: Intel HD Graphics 630 (MSI), Nvidia: MX 150                                                 |
|Storage     | 298GB TOSHIBA MQ01ABF032 (SATA ), 465GB KINGSTON SA2000M8500G (SATA-2 (SSD))                      |
|Speaker     | VEN_10EC&DEV_0892                                                                                 |
																												 
## Kexts, Drivers and (WIP)

## Versions (WIP)

# Bugs

- Trackpad PC/2 Synaptic click (physical button and tapping) doesn't work (need more time to fix it).
- No battery management (again, not enough time to do it).

# AfterMath:

# Setting up display text size:
bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"

# Setting up keyboard:

n your Mac open Settings Preferences.
Now go to Keyboard > Modifier Keys and select your keyboard from the keyboard drop down list.
Now for the Option key select ‘⌘ Command’ and for Command (⌘) key choose ‘⌥ Option’.
Click on the OK button and exit.

#Turn on three finger drag for your Mac trackpad
The ability to drag items using a three-finger gesture is an option for trackpads that support Force Touch.

	1	Choose Apple menu  > System Preferences, then click Accessibility. 
	2	Select Pointer Control in the sidebar. (In earlier versions of macOS, select Mouse & Trackpad.)
	3	Click the Trackpad Options button.
	4	Select ”Enable dragging,” then choose ”three finger drag” from the menu.
	5	Click OK.

Energy Saver Settings
	1	Open the Settings App
	2	Click Energy Saver
	3	Uncheck
	4	Uncheck Wake for Ethernet Network access
	5	Uncheck Enable Power Nap

sudo pmset autopoweroff 0
sudo pmset powernap 0
sudo pmset standby 0
sudo pmset proximitywake 0
sudo pmset tcpkeepalive 0


Read/write windows drive(NTFS):

Download:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

macFuse
