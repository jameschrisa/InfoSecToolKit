# WhatWeb

## Description
WhatWeb identifies websites. It recognizes web technologies including content management systems (CMS), blogging platforms, statistic/analytics packages, JavaScript libraries, web servers, and embedded devices.

## Author
Andrew Horton (urbanadventurer) and Brendan Coles

## Source
- GitHub: https://github.com/urbanadventurer/WhatWeb

## Usage by Security Engineers
Security engineers use WhatWeb to:
- Identify web technologies and software used by websites
- Perform initial reconnaissance on targets
- Gather information for vulnerability assessments
- Create profiles of large numbers of websites

## Useful Situations
WhatWeb is particularly useful for:
- Web application security assessments
- Penetration testing reconnaissance
- Large-scale web technology surveys
- Identifying potentially vulnerable software versions

## Example Commands
1. Basic scan of a website:
   ```
   whatweb http://example.com
   ```

2. Aggressive scan (more intrusive):
   ```
   whatweb -a 3 http://example.com
   ```

3. Scan multiple websites:
   ```
   whatweb http://site1.com http://site2.com
   ```

4. Output results to a file (XML format):
   ```
   whatweb --log-xml=output.xml http://example.com
   ```

5. Scan websites from a text file:
   ```
   whatweb -i targets.txt
   ```

## Installation
To install WhatWeb using Homebrew on macOS:

```
brew install whatweb
```

For other installation methods, you can clone the GitHub repository and follow the installation instructions provided in the README file.
