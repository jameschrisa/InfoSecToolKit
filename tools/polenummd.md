# PolEnum

## Description
PolEnum (Policy Enumerator) is a Python script designed to extract password policy information from Windows systems using null sessions.

## Author
Joshua "JDuck" Drake

## Source
- The original source is no longer available, but the tool is often included in security-focused Linux distributions.

## Usage by Security Engineers
Security engineers use PolEnum to:
- Enumerate password policies on Windows systems
- Assess the strength of password requirements
- Identify potential weaknesses in password configurations
- Gather information for password cracking attempts

## Useful Situations
PolEnum is particularly useful for:
- Windows domain security assessments
- Penetration testing of Windows environments
- Password policy audits
- Demonstrating the importance of strong password policies

## Example Commands
1. Basic enumeration:
   ```
   polenum [username]:[password]@[target]
   ```

2. Use with IP address:
   ```
   polenum [username]:[password]@192.168.1.100
   ```

3. Use with domain:
   ```
   polenum [username]:[password]@[domain]/[target]
   ```

## Installation
PolEnum is typically not available through package managers like Homebrew. It's often included in security-focused Linux distributions like Kali Linux. If you need to install it manually:

1. Ensure you have Python and the necessary dependencies (like Impacket) installed.
2. Obtain the PolEnum script from a trusted source.
3. Make the script executable:
   ```
   chmod +x polenum.py
   ```
4. Run the script as shown in the example commands.

Always ensure you have proper authorization before using this tool on any systems or networks.
