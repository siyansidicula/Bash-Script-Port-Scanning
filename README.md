# Bash Port Scanner

This is a simple Bash script that scans common ports on a target host and displays whether the ports are open or closed.

## Features

* Scans common TCP ports
* Displays open and closed ports
* Easy to use
* Written in Bash

## Usage

Make the script executable:

```bash
chmod +x port_scanner.sh
```

Run the script:

```bash
./port_scanner.sh localhost
```

or

```bash
./port_scanner.sh google.com
```

## Example Output

```text
Scanning common ports on localhost...

Port 22 is OPEN
Port 80 is OPEN
Port 443 is OPEN
```

