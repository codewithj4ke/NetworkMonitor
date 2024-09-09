[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/code-written-by-chatgpt-ai-ftw.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

# System Monitor Tool

A simple system monitoring tool built using Python's Tkinter for the GUI, psutil for system metrics, and Matplotlib for real-time network traffic plotting.

## Overview

This project is a desktop application that provides real-time monitoring of system information, including:

- Network Information (hostname and IP addresses)
- Memory Usage (total, available, used, and percentage)
- Storage Usage (details about disk partitions)
- Network Traffic (live graph showing incoming and outgoing data rates)

The GUI is built with Tkinter and provides a text-based overview of system metrics along with a live-updating graph of network traffic.

## Features

- **Real-time Monitoring**: Continuously updates and displays network traffic rates.
- **Detailed System Info**: Provides comprehensive details about memory and storage usage.
- **Interactive Graph**: Visualizes network traffic data with Matplotlib.

### Prerequisites

Ensure you have Python 3.x installed. You will also need to install the following Python packages:

- `tkinter` (usually included with Python)
- `psutil`
- `matplotlib`
