# Port Scanner

A simple Python-based port scanner to identify open ports on specified targets. This tool scans a range of ports on one or more target IP addresses and reports any open ports it finds.

## Features

- Scans a specified range of ports on target IP addresses
- Supports scanning multiple targets by separating IP addresses with commas
- Simple and easy-to-use command-line interface

## Requirements

- Python 3.x

## Usage

1. **Clone the Repository:**

    ```sh
    git clone https://github.com/yourusername/port-scanner.git
    cd port-scanner
    ```

2. **Run the Port Scanner:**

    ```sh
    python port_scanner.py
    ```

3. **Input the Targets and Ports:**

    - When prompted, enter the target IP addresses separated by commas.
    - Specify the number of ports you want to scan.

## Example

```sh
[*] Enter Targets To Scan (split them by ,): 192.168.1.1, 192.168.1.2
[*] Enter How Many Ports You Want To Scan: 100
