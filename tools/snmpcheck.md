# SNMPCheck

## Description
SNMPCheck is a free open source tool distributed under GPL that allows you to enumerate information via SNMP protocol.

## Author
Matteo Cantoni

## Source
- Original Source: http://www.nothink.org/codes/snmpcheck/ (may no longer be available)
- Alternative Source: https://github.com/pwnieexpress/pwn_plug_sources/tree/master/src/snmpcheck

## Usage by Security Engineers
Security engineers use SNMPCheck to:
- Enumerate information from SNMP-enabled devices
- Gather system information, running processes, and open ports
- Identify potential misconfigurations in SNMP
- Perform network reconnaissance

## Useful Situations
SNMPCheck is particularly useful for:
- Network device auditing
- Penetration testing of SNMP-enabled systems
- Asset discovery and inventory
- Identifying information leakage through SNMP

## Example Commands
1. Basic SNMP check:
   ```
   snmpcheck -t 192.168.1.100
   ```

2. Specify SNMP community string:
   ```
   snmpcheck -t 192.168.1.100 -c public
   ```

3. Use SNMPv3:
   ```
   snmpcheck -t 192.168.1.100 -v 3 -u username -a SHA -A password -x AES -X password
   ```

4. Output results to a file:
   ```
   snmpcheck -t 192.168.1.100 -w output.txt
   ```

## Installation
SNMPCheck is not typically available through package managers like Homebrew. To use it:

1. Obtain the SNMPCheck script from a trusted source.
2. Ensure you have Perl and the necessary SNMP libraries installed.
3. Make the script executable:
   ```
   chmod +x snmpcheck-1.9.rb
   ```
4. Run the script as shown in the example commands.

Alternatively, on some systems, you might be able to install it using:

```
apt-get install snmpcheck
```

Always ensure you have proper authorization before using this tool on any systems or networks.
