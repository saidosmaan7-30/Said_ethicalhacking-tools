# Said Ethical Hacking Tools

Powerful Python tools for different stages of ethical hacking, including reconnaissance, scanning, exploitation, and reporting. Customizable, lightweight, and beginner-friendly.

---

## Tools Overview

| Tool Name    | Stage           | Description                                       |
|--------------|-----------------|-------------------------------------------------|
| SaidRecon    | Reconnaissance  | Gather IP and HTTP headers from a domain or IP. |
| SaidVulnScan | Scanning        | Scan open ports and services using Nmap.        |
| SaidBrute    | Gaining Access  | Brute-force login forms with a password list.   |
| SaidSQLx     | Exploitation    | Basic SQL Injection testing on URL parameters.  |

---

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/saidosmaan7-30/Said_ethicalhacking-tools.git
cd Said_ethicalhacking-tools

2. Install Python 3 and pip (if not installed)


3. Install required Python packages:



pip install requests

4. Install Nmap for SaidVulnScan:



On Debian/Ubuntu:


sudo apt-get install nmap

On Windows, download from https://nmap.org/download.html and install.



---

Usage

Run each tool using Python 3:

SaidRecon

python SaidRecon.py

Prompts for domain or IP.


---

SaidVulnScan

python SaidVulnScan.py

Prompts for target IP.


---

SaidBrute

python SaidBrute.py

Prompts for login URL, username, and path to password wordlist.


---

SaidSQLx

python SaidSQLx.py

Prompts for URL with 'id=' parameter to test for SQL Injection.


---

Notes

Use these tools only on systems you have permission to test.

Educational and ethical use only.

SaidVulnScan requires Nmap installed and available in your system PATH.



---

Contact

Created by Said Osman Awil.


---

---


