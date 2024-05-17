# Python Port Scanner
This script is a simple and efficient port scanner written in Python. It allows users to scan specified IP addresses for open ports, with options to customize the range of ports to scan and the speed of the scan.
# Requirements
* `socket` module (standard library)
* `concurrent.futures` module (standard library)
* `tqdm module` (can be installed via pip)
# Example
You can run the script with `python3 port_scanner.py` and this is the example output:
```
Enter the IP address: 192.168.1.1
Do you want to scan all ports? Y/n: Y
It will be scanned from 0 to 65535.
Write the speed of your test (1-5): 3
```

