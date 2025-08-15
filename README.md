# Fake TWRP

A **fake TWRP recovery simulator** for Termux that flashes shell scripts with realistic logs, progress bars, and a TWRP-style interface.

## Features

- Blue TWRP-style interface with colored menus  
- Flash multiple `.sh` scripts safely  
- Fake system and data partitions (`$HOME/fake_twrp/fake_system` and `$HOME/fake_twrp/fake_data`)  
- Backup and wipe cache commands  
- Progress bars and timestamped logs  
- Fully safe, non-root, Termux-compatible  

---

## Installation

Follow these steps to install and run **Fake TWRP** in Termux:

### 1️⃣ Install Termux
- Download **Termux** from [F-Droid](https://f-droid.org/packages/com.termux/).  
  > ⚠️ Do not use the Play Store version; it’s outdated.  
- Open Termux after installation.

### 2️⃣ Update Termux packages
```bash
pkg update && pkg upgrade -y
###3️⃣ install required packages
pkg install git -y
pkg install bash -y
4️⃣ clone the fake twrp repository
git clone https://github.com/Rah-rgb/Fake-twrp.git
cd Fake-twrp
5️⃣ make the main script executable
chmod +x fake_twrp_color.sh
6️⃣ add or prepare example scripts
place .sh scripts inside the example_scripts folder
make them executable:
chmod +x /your/sh/file
7️⃣ run the fake twrp tool
./fake_twrp_color.sh


