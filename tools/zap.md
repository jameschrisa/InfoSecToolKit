# Zed Attack Proxy (ZAP)

## Description
OWASP Zed Attack Proxy (ZAP) is a free, open-source penetration testing tool being maintained under the umbrella of the Open Web Application Security Project (OWASP). ZAP is designed specifically for testing web applications and is both flexible and extensible.

## Author
OWASP Community

## Source
- GitHub: https://github.com/zaproxy/zaproxy
- Official Website: https://www.zaproxy.org/

## Usage by Security Engineers
Security engineers use ZAP to:
- Perform automated scans
- Serve as a man-in-the-middle proxy
- Spider websites
- Fuzz test applications
- Passive scan traffic

## Useful Situations
ZAP is particularly useful for:
- Web application security assessments
- Penetration testing
- Continuous integration/continuous deployment (CI/CD) pipeline security testing
- API security testing

## Example Commands
1. Start ZAP GUI:
   ```
   zap.sh
   ```

2. Run a quick scan from the command line:
   ```
   zap-cli quick-scan -s xss,sqli http://example.com
   ```

3. Generate an HTML report:
   ```
   zap-cli report -o report.html -f html
   ```

4. Spider a site:
   ```
   zap-cli spider http://example.com
   ```

5. Active scan:
   ```
   zap-cli active-scan http://example.com
   ```

## Installation
To install ZAP using Homebrew on macOS:

```
brew install --cask owasp-zap
```

For other installation methods, please refer to the official ZAP documentation.
