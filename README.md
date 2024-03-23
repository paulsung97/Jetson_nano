# Setting Up Your Jetson Nano

This guide provides step-by-step instructions on how to prepare your Jetson Nano for use, including initial setup and troubleshooting common issues.

## Initial Setup

### What You'll Need:
- **Jetson Nano**
- **SD Card** (16GB or larger recommended)
- **5V 2A Micro-USB Power Supply**
- **HDMI Cable**

### Preparing the SD Card:

1. **Download the Jetson Nano Developer Kit SD Card Image (version 4.6.1)**  
   Visit the [NVIDIA Developer Downloads](https://developer.nvidia.com/embedded/downloads) page to download the image.

2. **Unzip the Downloaded File**  
   Extract the contents of the zip file after downloading.

3. **Download an Image Writing Tool**  
   Obtain the [Win32DiskImager tool](https://sourceforge.net/projects/win32diskimager/) from SourceForge.

4. **Write the Image to the SD Card**  
   - Launch the Win32DiskImager tool.
   - Select the unzipped image file and the SD card drive.
   - Click on the **Write** button to begin the process.

## Troubleshooting: SD Card Errors

If you encounter issues with the SD card being recognized or appearing as unusable, follow these steps:

1. **Access Disk Management**
   - Right-click on the Start menu.
   - Select **Disk Management**.

2. **Prepare the SD Card**
   - In Disk Management, locate your SD card (it should appear as unallocated space).
   - Right-click the unallocated space and select **Create New Simple Volume**.

3. **Format the SD Card**
   - Download the [SD Memory Card Formatter](https://www.sdcard.org/downloads/formatter/sd-memory-card-formatter-for-windows-download/) for Windows.
   - Install and run the tool to format your SD card, which should resolve any errors.

## Setting Up DeepStream

To leverage the capabilities of your Jetson Nano for AI-driven video analytics, setting up DeepStream is essential.

1. **Download DeepStream SDK 6.0**  
   Follow the [DeepStream 6.0 Quickstart Guide](https://docs.nvidia.com/metropolis/deepstream/6.0/dev-guide/text/DS_Quickstart.html) for detailed installation instructions.

By following these instructions, your Jetson Nano will be ready for developing cutting-edge AI applications.

---
