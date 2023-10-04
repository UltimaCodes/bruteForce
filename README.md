# Brute Force Code Generator

This Python script generates combinations of characters in a brute-force manner for various purposes such as password cracking, testing security, or other use cases. It can generate combinations of different lengths and provide performance benchmarks.

## Features

- Generate combinations of characters of specified lengths.
- Provides performance benchmarking for different modes.
- Supports multiprocessing to speed up combination generation.
- Adjustable batch size to manage memory usage.

## Prerequisites

Before running the script, ensure you have the following:

- Python 3.x installed on your system.
- Required Python packages installed (`itertools`, `time`, `datetime`, `multiprocessing`, `functools`, `psutil`).

## Usage

1. Clone the repository or download the script.

2. Open a terminal and navigate to the directory containing the script.

3. Run the script using the following command:

   ```bash
   python forcerofthebrute.py

Follow the on-screen prompts to specify the minimum and maximum length of combinations you want to generate.

Choose whether to enable live progress display. This is recommended for high-end systems.

The script will provide you with an estimated time for combination generation. Confirm to proceed.

The script will generate combinations and display the total number of combinations and the time elapsed.

Benchmarks
The script provides two benchmark modes:

Performance mode: Generates combinations quickly but without live progress display.
Live display mode: Generates combinations with a live progress display.
Notes
Be cautious when enabling live progress display for long combinations, as it can be resource-intensive.

Adjust the CHARACTER_SET variable to customize the character set for combination generation.

License
This project is licensed under the MIT License - see the LICENSE file for details.
