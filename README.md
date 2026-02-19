WiiU ViGEmBus Controller
🎮 Features
ViGEmBus Support: Emulates an Xbox 360 controller on Windows using the ViGEmBus driver.

Wireless Streaming: Streams Wii U GamePad inputs over the network to a PC.

Lower Latency: Optimized for better performance compared to older solutions.

Easy IP Setup: On-screen IP configuration for quick connection.

🆕 What's New?
Completely rewritten input handling.

Integration with ViGEmBus instead of SCPBus.

Improved UI for IP address entry.

🎯 Controls
During IP Configuration:
L/R: Switch selected octet

ZL/ZR: Adjust value ±10

D-Pad UP/DOWN: Adjust value ±1

A: Confirm and connect

HOME (hold): Exit

During Streaming:
HOME (hold): Disconnect and return to IP menu

📦 Building
Prerequisites:
WdevkitPPC (devkitPro)

Wii U libraries (WUT)

To compile:
make

📝 Configuration
The application allows you to configure the destination PC's IP address directly on the Wii U GamePad screen.

🙏 Credits
Crayon: For the original MiisendU source code.

ViGEm Team: For the ViGEmBus driver.

devkitPro/WUT contributors: For the Wii U development toolchain.

📄 License
This project is licensed under the MIT License.

🔧 Differences from MiisendU
Uses ViGEmBus for modern Windows compatibility.

Added an interactive IP picker (no more editing .ini files manually).

Refined network packet structure for stability.

🚀 Usage
Install ViGEmBus on your PC.

Run the server-side application on your PC.

Launch WiiU ViGEmBus Controller on your Wii U.

Enter your PC's IP address and press A.

📊 Speed Comparison
Example: Changing IP from 192.168.1.1 to 192.168.1.100

Original MiisendU: ~119 button presses

WiiUViGEmBus: ~21 button presses

Result: 5.6x faster! ⚡

📚 Documentation
English: README_WiiUViGEmBus.md

Español: LEEME.md

Quick Start: INICIO_RAPIDO.md

Build Instructions: BUILD_INSTRUCTIONS.md

Changes: CHANGES.md

Version: 1.0.0
Based on: MiisendU Wii U v1.4.0 by Crayon
