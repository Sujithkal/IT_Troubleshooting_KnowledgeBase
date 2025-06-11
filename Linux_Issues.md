# 🐧 Common Linux Issues and Fixes

Basic Linux troubleshooting tips for beginners using Ubuntu or similar distributions in an IT support role.

---

## 1. 🚫 “Permission Denied” Error

Symptoms:
- Terminal shows: "Permission denied"

Fixes:
- Add `sudo` before the command
- Change file permissions using:
  chmod +x filename.sh  # to make script executable
- Check file ownership:
  chown username filename

---

## 2. 🔐 “Sudo: Command Not Found” or “User Not in Sudoers”

Symptoms:
- Cannot run sudo commands

Fixes:
- Switch to root user:
  su -
- Add user to sudo group:
  usermod -aG sudo your_username

---

## 3. 📁 Can't Access Mounted USB Drive

Symptoms:
- USB not showing up in /media or /mnt

Fixes:
- Check devices using:
  lsblk
- Mount manually:
  sudo mount /dev/sdb1 /mnt

---

## 4. 🧼 Disk Full – Can’t Create Files

Symptoms:
- Error: “No space left on device”

Fixes:
- Check disk usage:
  df -h
- Find large files:
  sudo du -sh /*
- Clean up package cache:
  sudo apt-get clean

---

## 5. ❌ Network Issues in Linux

Fixes:
- Restart networking service:
  sudo systemctl restart NetworkManager
- Check IP address:
  ip addr show
- Test connection:
  ping -c 4 google.com

---

