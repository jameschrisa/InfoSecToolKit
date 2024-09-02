# Nikto

## Description
Nikto is an open-source web server scanner that performs comprehensive tests against web servers for multiple items, including over 6700 potentially dangerous files/programs, checks for outdated versions of over 1250 servers, and version specific problems on over 270 servers.

## Author
Chris Sullo

## Source
- GitHub: https://github.com/sullo/nikto
- Official Website: https://cirt.net/Nikto2

## Usage by Security Engineers
Security engineers use Nikto to:
- Identify potential vulnerabilities in web servers
- Detect misconfigurations
- Find outdated software versions
- Discover default files and programs

## Useful Situations
Nikto is particularly useful for:
- Web application security assessments
- Penetration testing
- Compliance auditing
- Routine security checks

## Example Commands
1. Basic scan of a website:
   ```
   nikto -h http://example.com
   ```

2. Scan with SSL:
   ```
   nikto -h https://example.com -ssl
   ```

3. Scan and output to a file:
   ```
   nikto -h http://example.com -o report.txt
   ```

4. Scan multiple ports:
   ```
   nikto -h http://example.com -p 80,443,8080
   ```

5. Scan and update plugins:
   ```
   nikto -h http://example.com -update
   ```

## Installation
To install Nikto using Homebrew on macOS:

```
brew install nikto
```

For other installation methods, please refer to the official Nikto documentation.
