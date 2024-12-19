# HG14: Subdomain Enumeration Tool
## Subd.py
![Subdomain-Enumeration](picture.png)
## Subdomain.py
![Subdomain-Enumeration](picture2.png)

## Table of Contents
- [Introduction](#introduction)
- [Fetures](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage/Subd.py](#usage/subd.py)
## Introduction 
HG14 is a Python-based subdomain enumeration tool that helps identify subdomains and domains linked to a given website. It uses HTML parsing techniques to extract URLs and identify subdomains for security assessments and reconnaissance.

---

## Features

- **Subdomain Identification**: Extracts subdomains and domains from a given website URL.
- **HTML Parsing**: Uses BeautifulSoup for efficient extraction of anchor tags and URLs.
- **User-Agent Customization** (in `subdomain.py`): Bypasses basic detection mechanisms by web servers.
- **SSL Verification Disablement** (in `subdomain.py`): Ignores SSL certificate errors during requests.

---

## Prerequisites

- Python 3.x
- Required libraries: `requests`, `bs4`, `pyfiglet`, `urllib3`

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/himanshigupta14/Subdomain-Enumeration.git
cd Subdomain-Enumeration
```
## Usage/Subd.py
- run the script:
  ```bash
  python subd.py
- Enter the target /website url when promted.
  ```bash
  [+]Enter a website URL: example.com
  ```
- The script will output:
    - Subdomain: Extracted domain 
    - Domains: Extracted domains
## Usage/Subdomain.py
-run the script:
  ```bash
  python subdomain.py
  ```
- Enter the target /website url when promted.
  ```bash
  [+]Enter a website URL: example.com
  ```
-Key difference in the upgraded script
  -Bypasses SSL verification for the sites with invalid SSL certificates.
  -Adds a user-agent header to request for better compatibility.
-The script will output:
  - Subdomain: Extracted domain 
  - Domains: Extracted domains
## Notes
-The tool automatically normalizes the URL (e.g., adds http:// if missing).
-Ensure you have proper authorization before scanning domains. Unauthorized scanning is illegal and unethical.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the functionality.
