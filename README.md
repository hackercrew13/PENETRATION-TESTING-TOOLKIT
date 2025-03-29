# PENETRATION-TESTING-TOOLKIT

## COMPANY: CODTECH IT SOLUTIONS

**NAME:** HARIVIKAS M  
**INTERN ID:** CTO4WP220  
**DOMAIN:** FRONT-END DEVELOPMENT  
**DURATION:** 4 WEEKS  
**MENTOR:** NEELA SANTOSH  

## Description
This is a simple Python-based penetration testing toolkit that includes a port scanner and a brute-force login attack tool. It helps security professionals identify open ports on a target system and test login credentials against a web-based authentication system.

## Features
- Scans open ports on a target system
- Performs brute-force login attacks on web authentication pages
- Simple command-line interface

## Prerequisites
Ensure you have Python 3 and the required libraries installed:
```sh
pip install requests
```

## Installation
Clone this repository and navigate into the project directory:
```sh
git clone https://github.com/your-username/pentest-toolkit.git
cd pentest-toolkit
```

## Usage
Run the script with Python:
```sh
python3 pentest_toolkit.py
```
Follow the on-screen prompts:
1. Enter the target IP to scan for open ports.
2. The scanner will check ports 21, 22, 80, 443, and 8080.
3. Enter the login page URL and username for brute-force testing.
4. The toolkit will attempt a brute-force login with a predefined password list.

### Example
```sh
Enter target IP: 192.168.1.1
Scanning 192.168.1.1 for open ports...
[+] Port 22 is open
[+] Port 80 is open

Enter login page URL: http://example.com/login
Enter username: admin
Starting brute force attack on http://example.com/login...
[-] Failed: admin - 123456
[-] Failed: admin - password
[+] Success: admin - welcome
```

## File Structure
```
pentest_toolkit.py  # Main script
README.md            # Documentation
```

## License
This project is licensed under the MIT License.

## Author
**HARIVIKAS M**

## OUTPUT


<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/6195be17-2991-479e-a24c-563fc995ae88" />

