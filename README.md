# Port_scanner
A simple Python-based port scanner to identify open ports on specified targets. This tool scans a range of ports on one or more target IP addresses and reports any open ports it finds.

Features
Scans a specified range of ports on target IP addresses
Supports scanning multiple targets by separating IP addresses with commas
Simple and easy-to-use command-line interface
Requirements
Python 3.x
Usage
Clone the Repository:

sh
Copy code
git clone https://github.com/yourusername/port-scanner.git
cd port-scanner
Run the Port Scanner:

sh
Copy code
python port_scanner.py
Input the Targets and Ports:

When prompted, enter the target IP addresses separated by commas.
Specify the number of ports you want to scan.
Example
sh
Copy code
[*] Enter Targets To Scan (split them by ,): 192.168.1.1, 192.168.1.2
[*] Enter How Many Ports You Want To Scan: 100
This will scan the first 100 ports of the IP addresses 192.168.1.1 and 192.168.1.2.

Code Overview
scan(target, ports): Starts scanning the specified number of ports on the target IP address.
scan_port(ipaddress, port): Attempts to connect to a specific port on the given IP address and reports if the port is open.
Disclaimer
This tool is intended for educational purposes only. Unauthorized port scanning is illegal and unethical. Always ensure you have permission to scan any target.
