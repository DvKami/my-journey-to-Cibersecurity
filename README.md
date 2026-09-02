# My Journey to Become a DevOps Engineer 

Documenting my path from zero to DevOps Engineer — daily notes, hands-on projects, and real code, built one step at a time over 1 year.

**Following:** [roadmap.sh/devops](https://roadmap.sh/devops) as the conceptual guide, paired with a hands-on project track ("Bases de Hierro") to actually apply each concept in Python.

---

##  My Practical Roadmap: "Bases de Hierro"

| Project | Focus | Status |
|---|---|---|
| 1. CLI Diagnostic Tool | Python basics, argparse, env variables |  In progress |
| 2. Log Analyzer & API Notifier | File handling, exceptions, REST APIs |  Not started |
| 3. Infrastructure Auditor | JSON/YAML, functions, cloud SDKs (boto3) |  Not started |
| 4. Deployment Automation Engine | SSH automation, cron jobs, CI/CD basics |  Not started |

---

##  My Environment

- **OS:** Ubuntu 26.04 LTS (VirtualBox VM)
- **Editor:** VS Code + Remote-SSH extension
- **Language:** Python 3
- **Workflow:** Windows (PowerShell) → SSH → Ubuntu VM → VS Code remote editing

---

##  Daily Log

### Day 1 — Sept 1, 2026
**What I did:**
- Set up a Linux environment from scratch: created a VirtualBox VM, installed Ubuntu Desktop 26.04 LTS
- Learned my first Linux commands: `whoami`, `pwd`, `sudo apt update`
- Installed VS Code inside the VM using `snap install code --classic`
- Installed and configured OpenSSH Server on the VM
- Connected to my VM remotely from Windows PowerShell via SSH
- Installed VS Code on Windows + Remote-SSH extension, connected directly to the VM
- Wrote my first Python exercise: extracting values from a dictionary (`hostname`, `puerto`) and printing them

**Key concepts learned:**
- `sudo` = run as administrator
- `snap` = Linux's package manager (like an app store, but via terminal)
- `--classic` = permission flag that removes sandboxing restrictions
- SSH = secure remote connection protocol to control another machine via terminal
- Bridged Adapter (VirtualBox) = gives the VM its own IP on the local network, required for SSH access from the host machine

**Reflection:**
Started the day thinking DevOps setup would be overwhelming — ended it having built a full remote dev environment (VM + SSH + remote editing) from absolute zero. Confirms that breaking things into small steps beats trying to consume everything at once.

---

##  Notes
This repo will be updated as I progress through both roadmap.sh/devops topics and the 4 hands-on projects above.
