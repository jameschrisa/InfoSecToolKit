# SimplyEmail

## Description
SimplyEmail is a Python-based OSINT tool that gathers email addresses from various public sources. It's designed to be a fast and simple way to perform email reconnaissance.

## Author
Alexander Rymdeko-Harvey

## Source
- GitHub: https://github.com/SimplySecurity/SimplyEmail

## Usage by Security Engineers
Security engineers use SimplyEmail to:
- Gather email addresses associated with a domain
- Perform reconnaissance for social engineering campaigns
- Identify potential targets within an organization
- Assess an organization's exposure of email addresses

## Useful Situations
SimplyEmail is particularly useful for:
- Initial phases of penetration testing
- Social engineering assessments
- Open-source intelligence (OSINT) gathering
- Demonstrating the importance of email security and privacy

## Example Commands
1. Basic scan of a domain:
   ```
   ./SimplyEmail.py -all -e example.com
   ```

2. Use specific modules:
   ```
   ./SimplyEmail.py -m google -m bing -e example.com
   ```

3. Output results to a file:
   ```
   ./SimplyEmail.py -all -e example.com -o /path/to/output
   ```

4. Verify gathered emails:
   ```
   ./SimplyEmail.py -all -e example.com --verify
   ```

## Installation
SimplyEmail is not typically available through package managers like Homebrew. To install it:

1. Clone the repository:
   ```
   git clone https://github.com/SimplySecurity/SimplyEmail.git
   ```

2. Navigate to the SimplyEmail directory:
   ```
   cd SimplyEmail
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the setup script:
   ```
   ./setup/setup.sh
   ```

Always ensure you have proper authorization before using this tool to gather information about individuals or organizations.
