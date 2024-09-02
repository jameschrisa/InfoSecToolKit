# Bettercap

## Description
Bettercap is a powerful, easily extensible and portable framework written in Go which aims to offer to security researchers, red teamers and reverse engineers an easy to use, all-in-one solution with all the features they might possibly need for performing reconnaissance and attacking WiFi networks, Bluetooth Low Energy devices, wireless HID devices and Ethernet networks.

## Author
Simone Margaritelli (evilsocket)

## Source
- GitHub: https://github.com/bettercap/bettercap
- Official Website: https://www.bettercap.org/

## Usage by Security Engineers
Security engineers use Bettercap to:
- Perform network reconnaissance
- Execute man-in-the-middle attacks
- Sniff network traffic
- Perform WiFi and Bluetooth Low Energy attacks
- Create custom modules for specific tasks

## Useful Situations
Bettercap is particularly useful for:
- Wireless network security assessments
- Network traffic analysis
- IoT device security testing
- Red team operations
- Educational purposes in controlled environments

## Example Commands
1. Start Bettercap:
   ```
   sudo bettercap
   ```

2. Scan the network:
   ```
   net.probe on
   ```

3. Start a man-in-the-middle attack:
   ```
   set arp.spoof.targets 192.168.1.10
   arp.spoof on
   ```

4. Sniff HTTP traffic:
   ```
   set net.sniff.regexp .*password=.*
   net.sniff on
   ```

5. WiFi scanning:
   ```
   wifi.recon on
   ```

## Installation
To install Bettercap using Homebrew on macOS:

```
brew install bettercap
```

For other installation methods, please refer to the official Bettercap documentation.
