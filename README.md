# 🎵 Audio Signal Plotter

A comprehensive MATLAB-based audio analysis application built with App Designer for visualizing and analyzing audio signals in multiple domains.

---

## 📋 Overview

**Audio Signal Plotter** is an intuitive graphical application that enables users to load audio files and instantly visualize various signal characteristics. The app provides multi-channel analysis, frequency domain representation, and time-frequency analysis through an easy-to-use interface.

## ✨ Features

### Core Visualizations

- **🎧 Dual Channel Display** - Separate visualization of left and right audio channels
- **📊 Amplitude vs Frequency Analysis** - Frequency spectrum representation of the audio signal
- **🌈 Spectrogram Generation** - Time-frequency analysis showing how frequency content evolves over time
- **📁 Audio File Import** - Support for common audio formats (WAV, MP3, etc.)

### Key Capabilities

- Real-time signal processing and visualization
- Multi-panel layout for comprehensive analysis
- Clean, professional user interface
- Built entirely with MATLAB App Designer

---

## 🚀 Getting Started

### Prerequisites

- MATLAB R2020a or later (recommended)
- Signal Processing Toolbox
- Audio Toolbox
- Access to MATLAB Online or local MATLAB installation

### Installation

1. Clone or download this repository to your local machine
2. Open MATLAB or MATLAB Online
3. Navigate to the project directory
4. Open the `.mlapp` file in MATLAB App Designer

### Running the Application

```matlab
% Option 1: Run from App Designer
% Open the .mlapp file and click "Run"

% Option 2: Run from Command Window
% Navigate to the app directory and execute:
AudioSignalPlotter
```

---

## 💡 How to Use

1. **Launch the Application** - Open the app from MATLAB App Designer or command window
2. **Load Audio File** - Click the import/load button and select your audio file
3. **View Analysis** - The app automatically generates and displays:
   - Left channel waveform
   - Right channel waveform
   - Frequency spectrum (Amplitude vs Frequency)
   - Spectrogram (Time-Frequency representation)

---

## 📊 Visualization Details

### Left & Right Channel Plots
Displays the amplitude variation over time for each stereo channel, allowing you to identify channel-specific characteristics and stereo separation.

### Amplitude vs Frequency
Shows the frequency distribution of the audio signal using Fast Fourier Transform (FFT), revealing the dominant frequencies present in the audio.

### Spectrogram
Provides a three-dimensional view (time, frequency, and intensity) of the audio signal, ideal for analyzing how the frequency content changes throughout the recording.

---

## 🛠️ Technical Stack

- **Platform**: MATLAB Online App Designer
- **Language**: MATLAB
- **Required Toolboxes**: 
  - Signal Processing Toolbox
  - Audio Toolbox (optional, for extended format support)

---

## 📂 Project Structure

```
AudioSignalPlotter/
│
├── AudioSignalPlotter.mlapp    # Main application file
├── README.md                    # Project documentation
└── assets/                      # Screenshots and media (optional)
```

---

## 🎯 Use Cases

- **Audio Engineering** - Analyze recorded tracks and identify frequency content
- **Music Production** - Examine stereo separation and frequency balance
- **Educational Purposes** - Learn about signal processing and audio analysis
- **Research** - Conduct acoustic studies and audio signal research
- **Quality Control** - Verify audio file characteristics and identify anomalies

---

## 🔮 Future Enhancements

- [ ] Real-time audio input analysis
- [ ] Additional filters and effects
- [ ] Export visualization options
- [ ] Batch processing capabilities
- [ ] Customizable plot settings
- [ ] Audio playback controls

---

## 📝 License

This project is available for educational and personal use.

---

## 👤 Author

Created as a MATLAB audio analysis project using App Designer.

---

## 🤝 Contributing

Suggestions and improvements are welcome! Feel free to fork this project and submit pull requests.

---

## 📧 Contact

For questions or feedback regarding this project, please open an issue in the repository.

---

<div align="center">

**Built with ❤️ using MATLAB App Designer**

</div>
