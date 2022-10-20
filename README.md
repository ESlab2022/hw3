# HW3 BLE Notification

## Installation

### Clone the repository

```bash
git clone https://github.com/ESlab2022/hw3.git
cd hw3
```

### Install Python3 requirements

Install packages

```bash
sudo apt install python3-pip
sudo apt install libglib2.0-dev
sudo pip install bluepy
```

## Usage

### Android Phone

1. Install `BLE Tool`
2. Start advertising

Default setting:
Service: 0xfff0
Characteristic: 0xfff4

### RPi

```bash
sudo python ble_scan_connect.py
```

### Demo

https://user-images.githubusercontent.com/8317457/196878935-eba03fdb-065c-4781-8d05-502f919eab5a.mp4

