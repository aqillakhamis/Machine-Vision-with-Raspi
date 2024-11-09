# Headless Raspberry Pi Configuration

## :memo: Overview

This configuration is for a headless Raspberry Pi setup. You will need your laptop, Raspberry Pi, Raspberry Pi power adapter and SD card. Please follow the steps below. 

## Step 1: Download the Raspberry Pi OS Image

1. Go to the Raspberry Pi website and download **Raspberry Pi Imager**. [Raspberry Pi Imager](https://www.raspberrypi.com/software/) is the quick and easy way to install an Operating System to a microSD card ready to use with your Raspberry Pi. 

2. Download and install the Raspberry Pi Imager for your computer (Windows 🪟, macOS :apple:, Linux 🐧).

* If you're using a Mac, it will download a `.dmg` file
* For Windows, it will download an `.exe` file

## Step 2: Prepare Your SD Card

1. **Insert your SD Card**: Insert your microSD card (atleast 8GB, but preferably 16GB or more) into your computer using an SD card reader. 

2. **Format the SD card (optional)**: if your SD card has been used before and you want to start fresh, you can format it using an SD card formatter tool. 

## Step 3: Install Raspberry Pi OS using the Raspberry Pi Imager

<p align="center">
    <img src = "https://github.com/aqillakhamis/Machine-Vision-with-Raspi/blob/main/assets/raspi%20imager.png" alt="Raspberry Pi Imager" />
</p>

1. **Open Raspberry Pi Imager**: Launch the Raspberry Pi Imager you installed earlier.

2. **Raspberry Pi Device**: Choose model Raspberry Pi you use.

3. **Operating System**: Choose OS. Select Raspberry Pi OS (64-bit), which is the most commonly used version for latest Raspberry Pi. 

4. **Storage**: Choose storage according to your SD card. 

5. Click **Next** button.

## Step 4 : OS Customisation

<p align="center">
    <img src = "" alt="OS Customisation" />
</p>

1. **Edit Settings**: Click edit settings to configure general setup your Raspberry Pi

<p align="center">
    <img src = "" alt="OS Customisation General" />
</p>

In `GENERAL` tab: 

1. **Hostname**: Set your hostname. `raspberrypi` will be the default setting. You can change this to your preferred hostname. 

2. **Set Username and Password**: Set your username and password to login your Raspberry Pi. 

3. **Configure Wireless LAN**: Set which network will be used for your headless setting. Make sure this network setting is the same with the one connected with your laptop. 

4. **Wireless LAN Country**: Select MY (Malaysia)

<p align="center">
    <img src = "" alt="OS Customisation Services" />
</p>

In `SERVICES` tab: 

1. Tick `Enable SSH` and use password authentication. 

Click **SAVE** to save all settings and proceed with clicking `YES`. This will download the Raspberry Pi OS with configured settings and write it to the SD card. It may take several minutes. 

## Step 5: Eject the SD Card

1. Safely eject the SD card from your computer. 

## Step 6: Boot the Raspberry Pi

1. **Insert the SD card**: Insert the SD card into your Raspberry Pi. 

2. **Connect Raspberry Pi Power Adapter**: Plug in the power adapter to your Raspberry Pi and turn it on. The Pi will automatically boot up and connect to Wi-Fi (this may take a minute or two). 
