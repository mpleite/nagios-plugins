# Contributing to Nagios Remote Plugins 🤝

First off, thank you for considering contributing to this project! It's people like you who make this a great tool for the Nagios community.

## 🟢 How Can I Help?

### Reporting Bugs
* Check the [Issues](https://github.com/mpleite/nagios-plugins/issues) tab to see if the bug has already been reported.
* If not, open a new issue. Include:
    * The plugin name.
    * The OS/environment where it failed.
    * The error message or unexpected behavior.
    * Steps to reproduce.

### Suggesting Enhancements
* Open an issue to discuss the improvement.
* Explain why this change would be useful for other Nagios users.

### Submitting a Pull Request (PR)
1. **Fork** the repository.
2. **Create a branch** for your feature or fix (`git checkout -b feature/awesome-new-plugin`).
3. **Commit** your changes with clear descriptions.
4. **Push** to your fork and **open a Pull Request**.

---

## 🛠️ Development Standards

To keep the repository organized and the plugins reliable, please follow these guidelines:

### 1. Plugin Output
All plugins must follow the standard Nagios output format:
`STATUS: Short description | performance_data=value;warn;crit;min;max`

### 2. Exit Codes
Ensure your plugin returns the correct exit codes:
* **0**: OK
* **1**: WARNING
* **2**: CRITICAL
* **3**: UNKNOWN

### 3. Header Template
Every new plugin should include a header with:
```text
# Description: [What it does]
# Usage: ./plugin_name.sh -w 80 -c 90
# Parameters: -w (warning), -c (critical), etc.
# Requirements: [e.g., python3, jq, bc]
# Compatibility: [NRDP, NRDS, NRPE]
```

### 4. Language Choice
* Use **Bash** for simple system checks (minimal dependencies).
* Use **Python 3** for complex logic, API interactions, or JSON parsing.
* * Use **Powershell** for scripts on windows (minimal dependencies).
* Keep scripts as lightweight as possible.

---

## 📜 Code of Conduct
By participating in this project, you agree to maintain a respectful and collaborative environment.

**Happy monitoring!** 🚀
