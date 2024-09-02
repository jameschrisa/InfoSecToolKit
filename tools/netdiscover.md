# Netdiscover

## Description
Netdiscover is an active/passive ARP reconnaissance tool, developed mainly for those wireless networks without dhcp server, when you are wardriving. It can also be used on switched networks.

## Author
Jaime Penalba

## Source
- GitHub: https://github.com/alexxy/netdiscover

## Usage by Security Engineers
Security engineers use Netdiscover to:
- Discover live hosts on a network
- Perform network reconnaissance
- Identify potential rogue devices
- Map out network topology

## Useful Situations
Netdiscover is particularly useful for:
- Initial network enumeration
- Wireless network auditing
- Identifying devices on networks without DHCP
- Quick host discovery in penetration testing

## Example Commands
1. Scan the default interface:
   ```
   sudo netdiscover
   ```

2. Scan a specific range:
   ```
   sudo netdiscover -r 192.168.1.0/24
   ```

3. Passive mode (just listen):
   ```
   sudo netdiscover -p
   ```

4. Specify interface:
   ```
   sudo netdiscover -i eth0
   ```

5. Fast mode (less accurate):
   ```
   sudo netdiscover -f
   ```

## Installation
To install Netdiscover using Homebrew on macOS:

```
brew install netdiscover
```

For other installation methods, please refer to your system's package manager or compile from source using the GitHub repository.
