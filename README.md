# YellowSense Face Liveness Detection SDK For Android

<div align="center">
  <img src="https://www.yellowsense.in/assets/logo.jpeg" alt="YellowSense Technologies" width="200"/>
  <h2>Advanced AI-Powered Face Liveness Detection</h2>
  <p><strong>Enterprise-Grade Biometric Security Solution (Active Liveness + Device Tiering)</strong></p>
</div>

## Overview

YellowSense Face Liveness Detection System is an enterprise-grade biometric security solution designed to prevent spoofing attacks in digital identity verification. The updated V2 system combines **Active Liveness Challenges** (Head Turn, Smile, Blink) with **Dynamic Device Tiering** to ensure 98%+ accuracy across both flagship and budget Android devices.

## Download APK

📱 **Ready to Test?** Download the latest V2 APK:

[**Download app-debug.apk**](YellowSense_FaceLivenessV2.apk) (150MB)

### Installation Instructions
1. Download the APK file to your Android device
2. Enable "Install from Unknown Sources" in Settings
3. Install the APK
4. Grant camera permissions when prompted
5. Follow the on-screen active challenges (Turn Head, Smile, etc.)

## Key Features

- **Active Liveness Challenges**: Interactive flow requiring user actions (Blink, Turn Left/Right, Smile) to prove presence.
- **Dynamic Device Tiering**: 
    - **High Tier**: 720p analysis + GPU acceleration for flagship devices.
    - **Low Tier**: 480p analysis + Robust CPU processing for budget/MediaTek devices.
- **Universal Compatibility**: Fixed "Red Oval/No Detection" issues on Redmi/MediaTek chipsets via custom YUV stride handling.
- **Real-time Feedback**: Instant UI guidance for user actions (e.g., "Turn Head Left", "Smile").
- **Offline Processing**: 100% on-device ML execution (MediaPipe + ONNX) for privacy and speed.
- **Anti-Spoofing**: Protection against photo, video, and mask attacks via temporal logic and depth correlation.

## Technical Specifications

- **Minimum Android Version**: API 26 (Android 8.0)
- **Target Android Version**: API 34 (Android 14)
- **Application Size**: ~45MB (including ML models)
- **Supported Architectures**: ARMv7, ARM64
- **AI Engine**: MediaPipe Face Mesh + ONNX Runtime
- **Performance**: 
    - Flagship: 30 FPS analysis
    - Budget (Redmi 9): 10-15 FPS analysis (Optimized)

## How to Use

1. **Position your face** in the oval frame.
2. **Follow the instructions** displayed at the top:
    - *"Look at the camera"* (Blink detection)
    - *"Turn head left"*
    - *"Turn head right"*
    - *"Smile"*
3. **Wait for the green oval** which indicates success for each step.
4. **View results** on the success screen after completing all challenges.

## Security & Reliability

- **Active Challenge Logic**: Randomly verifies specific facial movements that are hard to spoof with static images.
- **Device-Specific Optimization**: Automatically detects hardware capabilities to prevent crashes or false negatives on low-end phones.
- **YUV Stride Compensation**: Advanced image processing ensures camera feed integrity on all manufacturers (Xiaomi, Samsung, Oppo, etc.).
- **Privacy Protection**: No facial data leaves the device; all processing is local.

## Troubleshooting

- **"Red Oval" but no detection?** Ensure you are in a well-lit area. The app now supports older MediaTek devices that previously failed.
- **"Turn other way"?** The app detects head direction precisely. Ensure you turn exactly as requested (Left vs Right).

## Company

**YellowSense Technologies**  
*Advanced AI-Powered Biometric Security*

**Contact**: hr@yellowsense.in  
**Repository**: `https://github.com/yellowsense2008/Face_liveness_UIDAI`

---

*© 2026 YellowSense Technologies. All rights reserved.*
