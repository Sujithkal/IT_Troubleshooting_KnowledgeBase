# 🖨️ Common Printer Issues and Fixes

This guide covers typical printer problems faced in IT support roles and how to troubleshoot them.

---

## 1. ❌ Printer Not Showing on PC

Symptoms:
- Printer is connected but not detected by the system

Fixes:
- Check cable or wireless connection
- Power cycle the printer
- Reinstall printer drivers
- Run Windows "Add a Printer" wizard

---

## 2. 📡 Printer Offline

Symptoms:
- Status shows "Offline" in Devices and Printers

Fixes:
- Right-click printer → “Use Printer Online”
- Restart Print Spooler service:
  net stop spooler
  net start spooler
- Ensure the printer is connected to the network

---

## 3. 🖨️ Print Jobs Stuck in Queue

Symptoms:
- Print job won't cancel or stays in "printing" state

Fixes:
- Open Print Queue → Cancel all jobs
- Restart Print Spooler service
- Delete files from:
  C:\Windows\System32\spool\PRINTERS

---

## 4. ⚠️ Driver Issues

Symptoms:
- Printer installs but doesn’t work
- Error messages when printing

Fixes:
- Download and install the latest drivers from the manufacturer’s website
- Use Windows Update to auto-install drivers
- Remove and re-add the printer

---

## 5. 🔍 Troubleshoot Wireless Printers

Steps:
- Confirm the printer is connected to the correct Wi-Fi
- Ping printer IP from PC:
  ping 192.168.X.X
- Access printer web interface via IP
- Restart router and printer

---

Bonus Tip:
For frequent problems, install a universal print driver like HP Universal Print Driver (UPD) to reduce compatibility issues.

---

