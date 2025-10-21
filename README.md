
# Kali Linux and DVWA Security Testing Project

## Overview
This project demonstrates security testing using Kali Linux, Burp Suite, and the Damn Vulnerable Web Application (DVWA). It includes setup instructions for Kali Linux and DVWA, as well as practical exercises on common web vulnerabilities such as SQL Injection, Cross-Site Scripting (XSS), and others. The project is an aid for learning penetration testing and ethical hacking skills.

## Features
- Kali Linux setup for penetration testing
- Installation of Metasploitable 2 machine(vulnerable web application) 
- Use of Burp Suite Community Edition for web application testing
- Exploration of various web vulnerabilities including:
  - SQL Injection (Blind/Classic)
  - Cross-Site Scripting (Reflected/Stored/DOM)
  - Command Injection
- Step-by-step demonstration of vulnerability exploitation
- Security level configuration in DVWA for practice from low to high security

## Prerequisites
- Kali Linux installed on VMware or other virtualization platform
- Download and installed Metasploitable 2 vuln machine from web resource
- Burp Suite Community Edition installed on Kali Linux
- Basic knowledge of Linux command line and networking

## Setup Instructions
1.Run the kali linux and Metasploitable 2 machine 
2.metasploitable machine username password is msfadmin:msfadmin
3. Access DVWA via browser at `http://localhost` and complete the database setup.
4. Launch Burp Suite and configure your browser to use Burp as a proxy for testing.
5. Begin exploring DVWA vulnerabilities through the web interface and Burp Suite tools.

## Usage
- Use DVWA to practice exploitation of different web vulnerabilities.
- Modify the security level as needed to practice different difficulty levels.
- Analyze HTTP requests and responses using Burp Suite to understand attack mechanics.
- Refer to included project documentation for detailed vulnerability descriptions and test cases.

## References
- [Kali Linux Documentation](https://www.kali.org/docs/)
- [Burp Suite Community Edition](https://portswigger.net/burp/communitydownload)
- OWASP Web Security Testing Guide

## License
This project is for educational purposes only. Use responsibly and ethically.
