# DNSRecon

## Description
DNSRecon is a Python script that provides the ability to perform various DNS-related tasks, including zone transfers, DNS cache snooping, and various DNS-related enumeration techniques.

## Author
Carlos Perez

## Source
- GitHub: https://github.com/darkoperator/dnsrecon

## Usage by Security Engineers
Security engineers use DNSRecon to:
- Enumerate DNS records
- Perform zone transfers
- Discover subdomains
- Identify misconfigurations in DNS
- Gather intelligence about a target domain

## Useful Situations
DNSRecon is particularly useful for:
- Reconnaissance phase of penetration testing
- DNS security audits
- Domain mapping
- Identifying potential attack vectors related to DNS

## Example Commands
1. Basic DNS enumeration:
   ```
   dnsrecon -d example.com
   ```

2. Perform a zone transfer:
   ```
   dnsrecon -d example.com -t axfr
   ```

3. Brute force subdomains:
   ```
   dnsrecon -d example.com -t brt -D /path/to/subdomains.txt
   ```

4. Reverse lookup of IP range:
   ```
   dnsrecon -r 192.168.1.0/24
   ```

5. Cache snooping:
   ```
   dnsrecon -t snoop -n 8.8.8.8 -D /path/to/domains.txt
   ```

## Installation
To install DNSRecon using Homebrew on macOS:

```
brew install dnsrecon
```

For other installation methods, please refer to the official DNSRecon documentation on GitHub.
