# Browser Crash Test

## Overview
This is a JavaScript-based demonstration designed to crash a web browser by overwhelming its resources. It utilizes Web Workers and infinite memory allocation to exhaust the browser's memory and processing capabilities, causing it to become unresponsive or crash entirely.

## Features
- Educational demonstration of browser resource limitations
- Interactive interface with warning messages
- Requires explicit user confirmation before execution
- Detailed explanation of purpose and risks

## How It Works
The script creates Web Workers that continuously allocate large memory buffers. By spawning an unbounded number of workers, the script pushes the browser beyond its resource limits, eventually causing it to crash.

## Usage
1. Clone or download this repository from GitHub.
2. Open the index.html file in a web browser.
3. Read the warnings carefully.
4. Click the "Run Crash Test" button if you wish to proceed.
5. Confirm your intention when prompted with the warning dialog.

## Safety Features
Unlike the previous version, this updated script:
- Does not execute automatically upon page load
- Requires explicit user confirmation via button click
- Displays clear warnings about potential consequences
- Includes a secondary confirmation dialog with detailed risks

## Warning
**SEVERE WARNING:** This will cause your browser to crash, your computer to lag, and may potentially cause irreversible performance impacts.

This demonstration is intended for educational or testing purposes only. Running it may cause your browser to freeze, crash, or potentially affect system stability depending on resource availability. Use at your own risk.

## License
This project is open-source and licensed under the MIT License. Feel free to use, modify, or distribute it as you see fit.

## Disclaimer
The author is not responsible for any damage caused by running this script. Use it responsibly and avoid running it on production systems or devices you cannot afford to disrupt. Using this code to intentionally crash others' browsers without consent may be illegal.
