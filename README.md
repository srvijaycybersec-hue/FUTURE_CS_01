DVWA Security Testing Project with Kali linux
Overview

This project demonstrates security testing using Kali Linux, Burp Suite, and the Damn Vulnerable Web Application (DVWA). It includes setup instructions for Kali Linux and DVWA, as well as practical exercises on common web vulnerabilities such as SQL Injection, Cross-Site Scripting (XSS), and others. The project is an aid for learning penetration testing and ethical hacking skills.
Features

    Kali Linux setup for penetration testing
    Installation and configuration of DVWA on a local server
    Use of Burp Suite Community Edition for web application testing
    Exploration of various web vulnerabilities including:
        SQL Injection (Blind/Classic)
        Cross-Site Scripting (Reflected/Stored/DOM)
        Brute Force attacks
        Command Injection
        File Inclusion
        Insecure CAPTCHA bypass
    Step-by-step demonstration of vulnerability exploitation
    Security level configuration in DVWA for practice from low to high security

Prerequisites

    Kali Linux installed on VMware or other virtualization platform
    Apache web server, MySQL/MariaDB installed and configured
    Burp Suite Community Edition installed on Kali Linux
    Basic knowledge of Linux command line and networking

Setup Instructions
Clone the Damn Vulnerable Web Application (DVWA) repository:

git clone https://github.com/digininja/DVWA.git

Move the cloned DVWA folder to your web server root, typically /var/www/html/.
Copy the configuration file template:

cp config/config.inc.php.dist config/config.inc.php

    Edit config/config.inc.php to set database credentials and other configuration options.
    Start MySQL/MariaDB service and create the DVWA database and user with appropriate privileges.
    Restart Apache server.
    Access DVWA via browser at http://localhost/DVWA/setup.php and complete the database setup.
    Launch Burp Suite and configure your browser to use Burp as a proxy for testing.
    Begin exploring DVWA vulnerabilities through the web interface and Burp Suite tools.

Usage

    Use DVWA to practice exploitation of different web vulnerabilities.
    Modify the security level as needed to practice different difficulty levels.
    Analyze HTTP requests and responses using Burp Suite to understand attack mechanics.
    Refer to included project documentation for detailed vulnerability descriptions and test cases.

References

    DVWA GitHub Repository
    Kali Linux Documentation
    Burp Suite Community Edition
    OWASP Web Security Testing Guide

License
This project is for educational purposes only. Use responsibly and ethically.
