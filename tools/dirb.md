# Dirb

## Description
Dirb is a web content scanner. It looks for existing (and/or hidden) web objects. It basically works by launching a dictionary-based attack against a web server and analyzing the response.

## Author
The Dark Raver

## Source
- Official Website: http://dirb.sourceforge.net/
- Source: https://sourceforge.net/projects/dirb/

## Usage by Security Engineers
Security engineers use Dirb to:
- Discover hidden directories and files on web servers
- Perform web application reconnaissance
- Identify potential entry points for further testing
- Automate the process of finding resources not linked from the main site

## Useful Situations
Dirb is particularly useful for:
- Web application security assessments
- Penetration testing
- Bug bounty hunting
- Website mapping

## Example Commands
1. Basic scan of a website:
   ```
   dirb http://example.com
   ```

2. Use a custom wordlist:
   ```
   dirb http://example.com /path/to/custom/wordlist.txt
   ```

3. Scan with a specific file extension:
   ```
   dirb http://example.com -X .php
   ```

4. Save output to a file:
   ```
   dirb http://example.com -o output.txt
   ```

5. Set a custom user agent:
   ```
   dirb http://example.com -a "Mozilla/5.0"
   ```

## Installation
To install Dirb using Homebrew on macOS:

```
brew install dirb
```

For other installation methods, please refer to the official Dirb documentation or your system's package manager.
