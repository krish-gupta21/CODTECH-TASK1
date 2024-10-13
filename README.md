lo**Name:** Krish Gupta
**Company:** CODTECH IT SOLUTIONS
**ID:** CT08DS7959
**DOMAIN:** CYBER ECURITY AND ETHICAL HACKING
**DURATION:** September to October 2024

# Overview of the Project

### Project: Vulnerabilty Scanning Tool

The **Vulnerability Scanner** is a lightweight command-line tool that helps identify potential security weaknesses in target systems. It performs two key functions: scanning for open TCP ports and checking the software version of a specified URL.

### Features

- **Open Ports Detection**: Scans a specified IP address or hostname for open ports (0 to 5000), reporting accessible ports that may expose the system to vulnerabilities.
  
- **Software Version Checking**: Retrieves and displays the software version from the server response header of a given URL, helping users assess if the software is outdated or potentially vulnerable.

### Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/krish-gupta21/CODTECH-TASK1.git
   cd CODTECH-TASK1
   chmod +x vulnscan.sh
   ```

2. Run the scanner:
   ```bash
   bash vulnscan.sh
   ```

### Requirements

- Unix-like OS with Bash support
- `curl` installed

### Contribution

Contributions are welcome! Open an issue or submit a pull request to enhance the script.
