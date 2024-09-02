# Nmap

## Description
Nmap (Network Mapper) is a powerful and versatile open-source tool used for network discovery and security auditing. It is designed to rapidly scan large networks, although it works equally well for single hosts.

## Author
Gordon Lyon (also known as Fyodor)

## Source
- GitHub: https://github.com/nmap/nmap
- Official Website: https://nmap.org/

## Usage by Security Engineers
Security engineers use Nmap for various purposes, including:
- Network inventory and mapping
- Port scanning to identify open services
- OS fingerprinting
- Vulnerability detection
- Security auditing

## Useful Situations
Nmap is particularly useful in scenarios such as:
- Initial reconnaissance of a network
- Identifying live hosts on a network
- Detecting unauthorized access points
- Auditing firewall configurations
- Penetration testing

## Example Commands
1. Basic scan of a single host:
   ```
   nmap 192.168.1.1
   ```

2. Scan a range of IP addresses:
   ```
   nmap 192.168.1.1-254
   ```

3. Perform an OS detection scan:
   ```
   nmap -O 192.168.1.1
   ```

4. Perform a stealthy SYN scan:
   ```
   nmap -sS 192.168.1.1
   ```

5. Scan all ports:
   ```
   nmap -p- 192.168.1.1
   ```

## Installation
To install Nmap using Homebrew on macOS:

```
brew install nmap
```

For other package managers or operating systems, please refer to the official Nmap installation guide: https://nmap.org/book/install.html
