# FireStrike - Android Termux DDoS Testing Tool

**Author:** zaid.escamillaa (Instagram)

## ⚠️ LEGAL DISCLAIMER
This tool is for **authorized security testing only**. You must have explicit written permission
to test any target you use this against. Unauthorized use is illegal.

## 📱 Requirements (Install these in Termux)

```bash
# Update packages
pkg update && pkg upgrade -y

# Install Python
pkg install python -y

# Install required Python libraries
pip install requests
pip install colorama
pip install pyfiglet
pip install termcolor

# Optional: Increase file descriptor limit for more connections
pkg install ulimit
ulimit -n 65535

# Fix SSL for older Android versions if needed
pkg install openssl-tool
