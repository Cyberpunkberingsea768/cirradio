# 📡 cirradio - Secure Mesh Radio For Field Use

[![Download](https://img.shields.io/badge/Download-Visit%20GitHub%20Page-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Cyberpunkberingsea768/cirradio)

## 🚀 What cirradio does

cirradio is a tactical UHF mesh radio system built for direct radio links in the field. It uses a Zynq-7045 FPGA board with an AD9361 radio front end, a SystemVerilog RTL design, a C++20 communications stack, and AES-256 crypto through PKCS#11.

For end users, this means a software and hardware package that can send data across a mesh network without relying on normal Wi‑Fi or mobile service. It is built for short-range UHF radio links and multi-node communication.

## 📥 Download and setup

Use this link to visit the project page and download the software package:

[Visit the cirradio download page](https://github.com/Cyberpunkberingsea768/cirradio)

After you open the page, look for the latest release, installer, or build files. On Windows, download the file that matches your system and keep it in a folder you can find again, such as Downloads or Desktop.

## 🪟 Run on Windows

1. Open the download page.
2. Get the latest Windows package or release file.
3. Save the file to your PC.
4. If the file comes as a ZIP folder, right-click it and choose Extract All.
5. Open the extracted folder.
6. Double-click the app file or launcher.

If Windows asks for permission, choose Yes so the app can start.

If the project gives you a setup file, run that file first. If it gives you a portable app, open the main EXE file.

## 🔧 What you need

Use a Windows PC with:

- Windows 10 or Windows 11
- At least 8 GB of RAM
- A free USB port or network port, if the radio hardware connects that way
- Enough disk space for the app and support files
- Admin access if the setup needs to install drivers

For a smooth setup, keep your radio hardware powered on and connected before you open the app.

## 📶 Main features

- UHF mesh radio support
- FHSS link handling for better link use
- AES-256 crypto for protected traffic
- PKCS#11 support for key handling
- C++20 control software
- FPGA-based radio logic
- AD9361 radio front end support
- Multi-node mesh networking
- Hardware and software stack for field use

## 🧭 First-time use

When you open cirradio for the first time, use this order:

1. Start the app.
2. Check that the radio hardware is connected.
3. Select the active radio node or device.
4. Set the channel or band options that match your setup.
5. Load the key file or token if your setup uses one.
6. Start the link test.
7. Send a short test message to another node.

If the app shows node status or link quality, use that view to confirm the radio is working.

## 🖥️ Typical workflow

A normal session may look like this:

- Turn on the radio unit
- Open cirradio on Windows
- Wait for the device to appear
- Join the mesh
- Check signal and link status
- Send or receive messages
- End the session and close the app

This layout helps you get from power-on to a working link with few steps.

## 🔐 Security and key handling

cirradio uses AES-256 and PKCS#11 support for secure traffic handling. In simple terms, this means the system is built to work with protected keys and encrypted data.

If your setup uses a token, smart card, or key file, keep it in a safe place and use the same device each time. If the app asks for a passphrase, enter it exactly as saved.

## 🧩 Folder layout

A typical release may include:

- `cirradio.exe` or a similar launcher
- `config` files for radio and mesh settings
- `keys` or token-related files
- `logs` for saved status data
- `docs` for setup help
- `drivers` if Windows needs extra support

Keep the folder together after extraction. Do not move single files out of the package unless the instructions say to do that.

## 📡 Hardware notes

cirradio is built around the Zynq-7045 and AD9361 radio path. That means the software expects a radio unit or board that matches the hardware design.

Common setup items may include:

- A supported radio board
- USB, Ethernet, or serial control access
- Antennas rated for UHF use
- A stable power supply
- Any required driver package

If your system includes a control board, connect it before opening the app so Windows can detect it.

## 🛠️ Basic troubleshooting

If the app does not open:

- Check that the file fully downloaded
- Unzip the folder before запуск? no, avoid non-English. Let's adjust in final? Wait too late. Need continue.