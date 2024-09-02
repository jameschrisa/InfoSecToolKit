# Gobuster

## Description
Gobuster is a tool used to brute-force URIs (directories and files) in web sites, DNS subdomains, and virtual host names. It's written in Go and designed to be fast and reliable.

## Author
OJ Reeves

## Source
- GitHub: https://github.com/OJ/gobuster

## Usage by Security Engineers
Security engineers use Gobuster to:
- Discover hidden directories and files on web servers
- Enumerate subdomains
- Perform virtual host discovery
- Conduct web application reconnaissance

## Useful Situations
Gobuster is particularly useful for:
- Web application security assessments
- Penetration testing
- Bug bounty hunting
- Rapid enumeration of large websites

## Example Commands
1. Directory bruteforcing:
   ```
   gobuster dir -u http://example.com -w /path/to/wordlist.txt
   ```

2. DNS subdomain enumeration:
   ```
   gobuster dns -d example.com -w /path/to/subdomains.txt
   ```

3. Virtual host discovery:
   ```
   gobuster vhost -u http://example.com -w /path/to/vhosts.txt
   ```

4. Specify file extensions:
   ```
   gobuster dir -u http://example.com -w /path/to/wordlist.txt -x php,txt,html
   ```

5. Use custom User-Agent:
   ```
   gobuster dir -u http://example.com -w /path/to/wordlist.txt -a "My Custom User-Agent"
   ```

## Installation
To install Gobuster using Homebrew on macOS:

```
brew install gobuster
```

For other installation methods, please refer to the official Gobuster documentation on GitHub.
