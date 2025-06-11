# 🧰 Essential Tools for IT Troubleshooting

This file lists the most commonly used tools by IT support technicians, both command-line and graphical, for diagnosing and resolving issues.

---

## 🖥️ Windows Command-Line Tools

### 1. ipconfig
- Shows IP address, subnet mask, and default gateway
- Common usage:
  ipconfig /all  
  ipconfig /release  
  ipconfig /renew  
  ipconfig /flushdns  

### 2. ping
- Tests network connectivity to another device or site  
  Example:  
  ping 8.8.8.8  

### 3. tracert
- Traces the route taken to reach a destination  
  Example:  
  tracert google.com  

### 4. nslookup
- DNS query tool to resolve domain names  
  Example:  
  nslookup facebook.com  

### 5. netstat
- Displays network connections and listening ports  
  Example:  
  netstat -an  

---

## 🛠️ Windows GUI Tools

### 6. Task Manager
- Monitor system performance, end unresponsive programs

### 7. Event Viewer
- View detailed logs of system, application, and security events

### 8. Device Manager
- View and manage hardware and drivers

### 9. Disk Management
- Create, resize, or format disk partitions

### 10. Windows Memory Diagnostic
- Tests for RAM issues  
  Access: `mdsched.exe`

---

## 🐧 Linux Tools (Command Line)

### 11. ifconfig / ip
- View and configure network interfaces  
  Example:  
  ip addr show  

### 12. top / htop
- Display running processes and CPU/memory usage

### 13. df / du
- Check disk usage  
  df -h → human-readable format  
  du -sh * → summarize folder sizes  

### 14. journalctl / dmesg
- View system logs and kernel messages  

### 15. systemctl
- Control systemd services  
  Example:  
  sudo systemctl restart NetworkManager  

---

## 🧪 Third-Party & Bonus Tools

- **BlueScreenView** – Analyze crash dumps for BSODs  
- **WhoCrashed** – Automatic crash analysis  
- **Putty** – SSH into remote systems  
- **Nmap** – Network scanner  
- **Wireshark** – Packet analyzer  
- **CrystalDiskInfo** – Check HDD/SSD health  

---

