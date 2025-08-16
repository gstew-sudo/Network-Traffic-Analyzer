# SOC Network Traffic Analyzer

## Overview
This Python script simulates a SOC-style network traffic analyzer for PCAP files. It parses network packets to summarize source and destination IPs, protocol distribution, and detect suspicious activity, such as potential scanning or high-volume connections. The script generates a CSV report for further analysis, making it a practical tool for threat detection and network monitoring.

## Features
- Parses PCAP files using `pyshark`.
- Summarizes top source and destination IPs.
- Displays protocol distribution.
- Flags suspicious IPs exceeding a configurable packet threshold.
- Generates a CSV report for documentation or further investigation.
- Easily extendable for port scanning detection, GeoIP analysis, or automated alerts.

## Requirements
- Python 3.8+
- [PyShark](https://pypi.org/project/pyshark/)

Install dependencies via pip:

```bash
pip install pyshark
