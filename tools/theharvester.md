# The Harvester

## Description
TheHarvester is a simple to use, yet powerful and effective tool designed to be used in the early stages of a penetration test or red team engagement. It gathers emails, names, subdomains, IPs and URLs using multiple public data sources.

## Author
Christian Martorella

## Source
- GitHub: https://github.com/laramies/theHarvester
- Official Website: N/A (GitHub is the main source)

## Usage by Security Engineers
Security engineers use TheHarvester to:
- Gather email addresses
- Find subdomains
- Discover virtual hosts
- Collect open ports and banners
- Retrieve employee names

## Useful Situations
TheHarvester is particularly useful for:
- Reconnaissance phase of penetration testing
- Information gathering for social engineering
- Identifying an organization's digital footprint
- OSINT (Open Source Intelligence) gathering

## Example Commands
1. Basic search using Google:
   ```
   theHarvester -d example.com -b google
   ```

2. Search using multiple sources:
   ```
   theHarvester -d example.com -b google,bing,linkedin
   ```

3. Limit the number of results:
   ```
   theHarvester -d example.com -b all -l 100
   ```

4. Save results to XML file:
   ```
   theHarvester -d example.com -b all -f results.xml
   ```

5. Search for subdomains:
   ```
   theHarvester -d example.com -c
   ```

## Installation
To install TheHarvester using Homebrew on macOS:

```
brew install theharvester
```

For other installation methods, please refer to the official TheHarvester documentation on GitHub.
