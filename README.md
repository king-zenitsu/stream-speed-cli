# Video Speed Controller CLI 🎬⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-brightgreen.svg)](https://www.python.org/)

A streamlined CLI utility for video editors and developers to compute media playback scalers, time savings, and generate pitch-corrected FFmpeg commands.

## Features
- ⚡ **Precision Scaling**: Accurately computes duration and time savings for fractional speeds.
- 🎵 **Pitch Preservation**: Automatically chains multi-stage `atempo` filters for high-speed scalers (>2.0x).
- 🛠️ **One-Line Copyable FFmpeg Output**: Ready to run directly in your terminal.

## Installation
```bash
git clone https://github.com/king-zenitsu/stream-speed-cli.git
cd stream-speed-cli
python speed_ctrl.py --help
```

## Usage Example
```bash
# Calculate 1.75x speedup for a 45-minute video and get command
python speed_ctrl.py -i raw_lecture.mp4 -o fast_lecture.mp4 -s 1.75 -d 45
```

## License
MIT License. Free for open-source and commercial use.
