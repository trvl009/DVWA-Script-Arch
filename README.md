# DVWA Installer

![DVWA Logo](https://raw.githubusercontent.com/ethicalhack3r/DVWA/master/dvwa/images/logo.png)

## Table of Contents 📚
- [Description](#description)
- [Installation](#installation)
  - [Installation Steps](#installation-steps)
- [Usage](#usage)
- [Credentials](#credentials)
- [Contributing](#contributing)
- [License](#license)

---
## Description 📖

This script automates the installation process for [DVWA (Damn Vulnerable Web Application)](https://github.com/digininja/DVWA), a web application intentionally designed to be vulnerable to various attacks. DVWA is a tool for learning and practicing web application security.

**This is a fork of [IamCarron's](https://github.com/IamCarron) script for Arch-based systems.**

---

## Installation 🛠️
```bash
sudo bash -c "$(curl --fail --show-error --silent --location https://raw.githubusercontent.com/IamCarron/DVWA-Script/main/Install-DVWA.sh)"
```

**If you are willing to use root and empty password for the execution of MySQL commands the script must be run as root user.**

---

## Usage 🚀

Follow the on-screen instructions to install DVWA. The script will guide you through the process, including updating repositories, installing dependencies, and configuring the DVWA database.

---

## Credentials 🔐

After install, use the following credentials:
- **Username:** `admin`
- **Password:** `password`
  
---

## Contributing 🤝

Contributions are welcome! If you encounter any issues or have suggestions for improvement, please create a pull request or open an issue in the [original script's GitHub repository](https://github.com/IamCarron/DVWA-Script).

---

## License 📄

This project is licensed under the [MIT License](LICENSE).
