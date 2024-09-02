# WAFw00f

## Description
WAFw00f is a Web Application Firewall (WAF) fingerprinting tool. It sends a series of requests to a web server and analyzes the responses to determine if a WAF is in place and, if possible, which one.

## Author
Sandro Gauci and Wendel G. Henrique

## Source
- GitHub: https://github.com/EnableSecurity/wafw00f

## Usage by Security Engineers
Security engineers use WAFw00f to:
- Identify the presence of a WAF
- Determine the type of WAF in use
- Assess the effectiveness of WAF implementations
- Plan penetration testing strategies

## Useful Situations
WAFw00f is particularly useful for:
- Web application security assessments
- Penetration testing preparation
- Understanding a target's security infrastructure
- Evaluating WAF deployments

## Example Commands
1. Basic scan of a website:
   ```
   wafw00f http://example.com
   ```

2. Scan multiple sites:
   ```
   wafw00f http://site1.com http://site2.com
   ```

3. Read targets from a file:
   ```
   wafw00f -i targets.txt
   ```

4. Use a custom User-Agent:
   ```
   wafw00f -a "My Custom User-Agent" http://example.com
   ```

5. Output results to a file:
   ```
   wafw00f -o output.txt http://example.com
   ```

## Installation
To install WAFw00f using Homebrew on macOS:

```
brew install wafw00f
```

For other installation methods, you can use pip:

```
pip install wafw00f
```

Or refer to the official WAFw00f documentation on GitHub for alternative installation methods.
