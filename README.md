# Crash Browser
## Overview
This is a simple JavaScript-based script designed to crash a web browser by overwhelming its resources. 

It utilizes Web Workers and infinite memory allocation to exhaust the browser's memory and processing capabilities, causing it to become unresponsive or crash entirely.

## How It Works
The script defines a function `workerCrash()` that creates an infinite loop.

Inside the loop, it generates a Web Worker running a Blob containing JavaScript code.

The Web Worker itself contains an infinite loop that repeatedly allocates large `ArrayBuffer` objects (2^30 bytes each), rapidly consuming memory.

By spawning an unbounded number of workers, the script pushes the browser beyond its limits.

## Usage
1. Clone or download this repository from GitHub.

2. Open the index.html file in a web browser.

3. The script will execute automatically and attempt to crash the browser.

**Warning:** This script is intended for educational or testing purposes only. Running it may cause your browser to freeze, crash, or potentially affect system stability depending on resource availability. Use at your own risk.

## License
This project is open-source and licensed under the MIT License. Feel free to use, modify, or distribute it as you see fit.

## Disclaimer
The author is not responsible for any damage caused by running this script. Use it responsibly and avoid running it on production systems or devices you cannot afford to disrupt.
