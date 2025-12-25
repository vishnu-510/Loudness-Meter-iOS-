# 🎚️ Loudness Meter – iOS (SwiftUI)

An iOS audio analysis app built using **SwiftUI** and **AVFoundation** that analyzes imported audio files and displays loudness-related metrics.

## 🚀 Features
- 📈 Peak Level Detection (dBFS)
- 🔊 RMS Loudness Measurement (dBFS)
- 🎛️ Stereo Left / Right Loudness Meters
- ⚠️ Clipping Detection
- ⏱️ Audio Duration
- 🔄 Mono / Stereo Channel Detection
- 📊 Animated Loudness Bar Meter

## 🧠 Audio Processing
- Reads audio using `AVAudioPCMBuffer`
- Converts multi-channel audio to mono
- Calculates:
  - Peak amplitude
  - RMS amplitude
  - dBFS conversion
- Normalizes loudness for UI meters
- Detects clipping when samples exceed digital limits

## 🛠️ Tech Stack
- Swift
- SwiftUI
- AVFoundation / AVFAudio
- Xcode

## 📌 Why this project?
This project demonstrates real-time audio signal analysis concepts and serves as a foundation for DSP-based applications and audio plugins.

## 👨‍💻 Author
**Vishnu Kumar**  
Aspiring Audio & iOS Developer
