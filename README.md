# firewall-auth

This repository contains a python script for the firewall authentication on the IITK network from the command line. It also takes care of 

Note: `firewall3.py` is the currently working file and uses python3. `firewall2.py` has not been tested yet.

## Usage
- Providing credentials at runtime
  ```bash
  $ python3 firewall3.py
  Username: your_username
  Password: your password
  ```

- Passing as arguments (sequence matters)
  ```bash
  $ python3 firewall3.py your_username your_password
  ```

- Using .netrc file (pass the netrc option) and modify the ~/.netrc file accordingly.