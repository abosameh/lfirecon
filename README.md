# lfirecon
# Current Features:

- **High-Speed Scanning:** Lightning-fast scanning of web applications for Local File Inclusion (LFI) vulnerabilities.

- **Multi-URL Support:** Simultaneously scan multiple URLs for LFI issues.

- **Comprehensive Payload Scanning:** Extensive payload library for thorough testing.
- **Rapid Vulnerability Detection:** Quickly identifies LFI vulnerabilities with minimal false positives.

- **Multi-Threaded:** Utilizes multi-threading for efficient scanning.

- **Vulnerability URL Output:** Provides a list of vulnerable URLs for further analysis or action.
  

# Installation Instructions
requires **go1.19** to install successfully. Run the following command to install the latest version: 

```sh
**Old_Go**
go get -u github.com/abosameh/lfirecon
**Update_Go**
go install github.com/abosameh/lfirecon@latest

path setup

cp -r /root/go/bin/lfirecon /usr/local/bin
```
# Usage:
```
lfirecon -f urls.txt -p payloads.txt -o output.txt -v
```
