# Nagios Remote Plugins Collection 🛠️

![Nagios](https://img.shields.io/badge/Nagios-FF0000?style=for-the-badge&logo=nagios&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

> As an **intense Nagios user**, I often need to develop or adapt plugins to work with **NRDP**, **NRDS**, or any other remote plugin executor.

---

## ✨ About This Project

This repository contains plugins, scripts, and tools I created or adapted for use in **Nagios / Icinga / Naemon** environments with remote execution (NRDP, NRDS, NSCA, etc.).

The main goal is to provide **lightweight**, **reliable**, and **easy-to-maintain** plugins for real-world production scenarios.

### Key Objectives:
* **Simplify** the creation and adaptation of remote plugins.
* **Standardize** output and performance data.
* **Support** multiple remote delivery methods (NRDP, NRDS, etc.).
* **Help** other Nagios administrators.

---

## 📂 Repository Structure

```text
/
├── plugins/      # Ready-to-use plugins
├── templates/    # Base templates for new plugins
├── utils/        # Helper scripts
├── docs/         # Detailed documentation
└── examples/     # Configuration examples
```

---

## 🚀 How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mpleite/nagios-plugins.git
   ```

2. **Make scripts executable:**
   ```bash
   chmod +x plugins/*.sh plugins/*.py
   ```

### Plugin Standards
Every plugin includes in its header:
* **Description:** What the plugin does.
* **Parameters:** Accepted arguments.
* **Usage examples:** How to run it.
* **Compatibility:** (NRDP / NRDS / NRPE).

---

## 🛠️ Technologies
* **Bash** & **Python 3**
* * **Powershell** & **cmd**
* **Perl** (legacy support when needed)
* **NRDP / NRDS** protocols
* **Nagios Core / Icinga 2 / Naemon**

---

## 🤝 Contributing

Feel free to:
* Suggest new plugins.
* Report bugs.
* Submit improvements via Pull Request.

Please read the `CONTRIBUTING.md` file for more details.

---

**Made with ❤️ by a Nagios addict.**
