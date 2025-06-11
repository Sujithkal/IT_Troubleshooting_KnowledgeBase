# 💻 BSOD (Blue Screen of Death) Common Errors and Fixes

This guide helps troubleshoot some of the most frequent Blue Screen of Death (BSOD) issues seen in Windows environments.

---

## 1. ❌ IRQL_NOT_LESS_OR_EQUAL (0x0000000A)

Cause:
- Faulty drivers or RAM issues

Fixes:
- Update all drivers (especially network and graphics)
- Run Windows Memory Diagnostic Tool
- Check for hardware compatibility
- Scan system files:
  sfc /scannow

---

## 2. 🧠 PAGE_FAULT_IN_NONPAGED_AREA (0x00000050)

Cause:
- Faulty RAM, antivirus conflict, or disk errors

Fixes:
- Run chkdsk /f /r
- Test memory using MemTest86 or Windows Memory Diagnostic
- Disable or uninstall third-party antivirus temporarily

---

## 3. 🧱 SYSTEM_SERVICE_EXCEPTION (0x0000003B)

Cause:
- Incompatible or buggy driver, usually graphics-related

Fixes:
- Update graphics drivers
- Run:
  sfc /scannow
  DISM /Online /Cleanup-Image /RestoreHealth
- Uninstall recently installed software

---

## 4. 🧩 DRIVER_IRQL_NOT_LESS_OR_EQUAL (0xD1)

Cause:
- Corrupt or outdated drivers

Fixes:
- Boot into Safe Mode
- Update/reinstall device drivers
- Use BlueScreenView tool to identify the exact driver causing the issue

---

## 5. 🔧 CRITICAL_PROCESS_DIED

Cause:
- A crucial Windows process failed

Fixes:
- Boot into Safe Mode and run startup repair
- Run System File Checker:
  sfc /scannow
- Reinstall or reset Windows if repair fails

---

✅ General BSOD Troubleshooting Steps:
- Keep Windows updated
- Check device drivers regularly
- Test RAM and hard disk
- Use tools like:
  - WhoCrashed
  - BlueScreenView
  - Windows Reliability Monitor

---

