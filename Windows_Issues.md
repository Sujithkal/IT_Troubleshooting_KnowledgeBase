# 🪟 Common Windows Issues and Fixes

This file lists frequent problems encountered on Windows desktops/laptops and how to troubleshoot them like an IT support technician.

---

## 1. 🔄 Slow Boot or Login Time

**Symptoms:**
- Takes a long time to boot or login
- High disk usage in Task Manager

**Fixes:**
- Disable startup apps: `Task Manager > Startup > Disable unnecessary apps`
- Run `sfc /scannow` to repair system files
- Check disk health: `chkdsk /f /r`
- Upgrade HDD to SSD if applicable

---

## 2. ❌ Application Not Responding

**Symptoms:**
- Apps freeze or become unresponsive

**Fixes:**
- End task via Task Manager
- Run in compatibility mode
- Reinstall the app
- Check Event Viewer for logs

---

## 3. 📥 Windows Update Fails

**Symptoms:**
- Error code during update (e.g., 0x80070005)

**Fixes:**
- Run Windows Update Troubleshooter  
- Restart Windows Update service:
  ```powershell
  net stop wuauserv
  net start wuauserv
Clear SoftwareDistribution folder

Use sfc /scannow to repair corrupted files

4. 🔇 No Sound
Symptoms:

No audio output even when volume is up

Fixes:

Check output device

Restart Windows Audio Service

Reinstall audio drivers from Device Manager

5. 🧼 Low Disk Space
Symptoms:

"Low Disk Space" warning

Fixes:

Run Disk Cleanup

Remove temp files: Win + R → %temp%

Uninstall unused apps

Move files to external drive


