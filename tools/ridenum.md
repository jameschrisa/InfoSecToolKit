# RidEnum

## Description
RidEnum is a Python script that implements a technique known as RID cycling to enumerate user accounts through Microsoft Windows Serial Number (SID) bruteforcing.

## Author
Tim Tomes (LaNMaSteR53)

## Source
- GitHub: https://github.com/trustedsec/ridenum

## Usage by Security Engineers
Security engineers use RidEnum to:
- Enumerate user accounts on Windows systems
- Perform user discovery during penetration tests
- Identify potential targets for further exploitation
- Test Windows domain security configurations

## Useful Situations
RidEnum is particularly useful for:
- Active Directory environment assessments
- Penetration testing of Windows networks
- User account auditing
- Demonstrating the importance of proper account management

## Example Commands
1. Basic enumeration:
   ```
   python ridenum.py 192.168.1.100 500 50000 /path/to/wordlist.txt
   ```

2. Specify a username and password:
   ```
   python ridenum.py 192.168.1.100 500 50000 /path/to/wordlist.txt username password
   ```

3. Use with domain:
   ```
   python ridenum.py 192.168.1.100 500 50000 /path/to/wordlist.txt username password domain
   ```

## Installation
RidEnum is typically not available through package managers like Homebrew. To use it:

1. Clone the repository:
   ```
   git clone https://github.com/trustedsec/ridenum.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the script as shown in the example commands.

Always ensure you have proper authorization before using this tool on any systems or networks.
