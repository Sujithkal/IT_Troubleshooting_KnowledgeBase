# 🌐 Common Network Issues and Fixes

A guide to identifying and resolving basic networking problems on a PC or small office network.

---

## 1. ❌ No Internet Access

**Symptoms:**
- "No Internet" in system tray
- Websites not loading

**Fixes:**
- Check physical connection (Ethernet/wireless)
- Restart router/modem
- Run `ipconfig /release` and `ipconfig /renew`
- Run Windows Network Troubleshooter
- Flush DNS cache:
  ```cmd
  ipconfig /flushdns
2. 🔄 IP Address Conflict
Symptoms:

Error: “Another computer on this network has the same IP address”

Fixes:

Reboot the device

Set to obtain IP automatically (DHCP)

Run ipconfig /release → ipconfig /renew

3. 📡 Weak or No Wi-Fi Signal
Symptoms:

Frequent disconnections or low bars

Fixes:

Move closer to the router

Forget and reconnect to the Wi-Fi

Update wireless drivers

Change router channel settings

4. 📛 DNS Server Not Responding
Symptoms:

Ping works but websites don't load

Fixes:

Change to Google DNS:

Preferred: 8.8.8.8
Alternate: 8.8.4.4

Clear DNS cache:

cmd
ipconfig /flushdns
