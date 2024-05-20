# Say Intentions for Mac (X-Plane 12)

![Fullscreen_21_5_2024__9_42_am](https://github.com/paulfisher53/SayIntentionsForMac/assets/25142601/aa8cfcf3-e0af-4721-9ac3-084c07db5871)

### Installation

1. Install UTM (https://mac.getutm.app/)
2. Create a Windows 11 virtual machine (https://docs.getutm.app/guides/windows/). Make sure the `Network Mode` is set to `Emulated VLAN`, do not change any of the `Advanced Settings`
3. Install `Say Intentions` on the Windows 11 virtual machine (download from the Pilot Portal)
4. Download the latest `Release.zip` file (from https://github.com/paulfisher53/SayIntentionsForMac/releases) and copy it to the Windows 11 Virtual Machine and unzip

### Run

1. Execute `run.bat` (from the unzipped `Release.zip` file). This will forward UDP port 49000 (using `sudppipe.exe`) and run a dummy `X-Plane.exe` process to trick the `Say Intentions` client
2. Open `X-Plane 12` on your Mac
3. Open `Say Intentions` on the Windows 11 virtual machine. It should connect to X-Plane 12 on the Mac and work as normal
