# Audio Encryption Using Classical Ciphers

A Java Swing desktop application designed for audio file encryption, decryption, waveform visualization, and playback using classical cryptographic algorithms.

## 📌 Overview
This project applies classical cryptographic ciphers to audio data (such as WAV files). Audio bytes are processed and transformed using classic cipher techniques, allowing encryption and decryption while preserving file structures.

## 🔐 Implemented Ciphers
- **ADFGX Cipher**: Combines Polybius square substitution with columnar transposition.
- **Bifid Cipher**: Uses Polybius fractionation and coordinate recombination.
- **Nihilist Cipher**: Applies key addition onto Polybius coordinates.
- **Polybius Square**: Maps byte values to 2D matrix coordinates.
- **Tap Code**: Encodes values into sequences of coordinate taps.
- **Trifid Cipher**: Extends fractionation into a 3D coordinate space (layer, row, column).

For formal algorithmic specifications, see [`Algorithms.tex`](Algorithms.tex).

## 🖥 Features
- **GUI Application**: Intuitive Java Swing graphical interface (`MainUI` / `MainWindow`).
- **Waveform Visualization**: Visual representation of audio waveforms via `WaveformPanel`.
- **Audio Services**:
  - `AudioCryptoService`: Handles cipher encryption and decryption logic.
  - `AudioFileService`: File I/O for audio formats.
  - `AudioPlayerService`: Integrated playback for encrypted and decrypted audio.

## 🚀 How to Run

Ensure Java Runtime Environment (JRE) or Java Development Kit (JDK) 11+ is installed.

Run the application using:
```bash
java -cp . com.cns.project.Main
```
