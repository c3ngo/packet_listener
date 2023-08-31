# Packet Listener

This project provides a simple packet listener implemented in Python using the Scapy library. The packet listener is designed to capture HTTP packets and display their contents. **Please note that this code is intended for educational purposes and should be used responsibly and legally.**

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Requirements](#requirements)
- [Disclaimer](#disclaimer)

## Introduction

This packet listener demonstrates how to use the Scapy library to capture network packets and specifically focuses on HTTP packets. The listener captures packets on the specified interface and displays the payload content of HTTP packets.

## Features

- Captures network packets, specifically targeting HTTP packets.
- Displays the payload content of captured HTTP packets.

## Usage

1. Make sure you have Python installed.
2. Install the Scapy library using the following command:

```sh
pip install scapy
```

3. Open the `packet_listener.py` file in a text editor.
4. Modify the `listen_packets` function parameter to specify the interface you want to capture packets on. Replace `"eth0"` with the desired interface name.

```python
listen_packets("eth0")
```

Run the script by executing the following command:

```sh
python3 listener.py
```

The packet listener will start capturing network packets on the specified interface. If an HTTP packet with payload content is captured, it will be displayed in the console.

Note: Be cautious when capturing network packets, and ensure that you have the necessary permissions. Unauthorized capturing of network data is against the law and unethical.

## Requirements

- Python 3.x
- Scapy library
- 
Install the required library using the following command:

```sh
pip install scapy
```
## Disclaimer
This packet listener example is intended for educational and learning purposes only. It should not be used for any malicious or unauthorized activities. The developer and the provider of this code are not responsible for any misuse or legal consequences caused by the use of this code.
