# 🐧 Using Remote Desktop Protocol (RDP) on Linux

This guide shows how to connect to a Windows PC using RDP from Linux.

---

## 📌 Requirements

- Linux system (Ubuntu, Debian, Fedora, etc.)
- Internet connection
- Access to a Windows PC with RDP enabled

---

## 📥 Step 1: Install RDP Client

### Ubuntu / Debian:

- sudo apt update
- sudo apt install remmina remmina-plugin-rdp

### Fedora:

- sudo dnf install remmina remmina-plugins-rdp

---

## 🚀 Step 2: Open Remmina

- Launch **Remmina Remote Desktop Client**
- Click **+ (New Connection)**

---

## 🌐 Step 3: Configure Connection

- **Protocol:** RDP  
- **Server:** IP address of Windows PC  
- **Username:** Your Windows username  
- **Password:** Your password  

---

## 🖥️ Step 4: Connect

1. Click **Save & Connect**
2. Accept certificate (if prompted)
3. You are now connected 🎉

---

## ⚙️ Optional Tools

- **rdesktop** (lightweight CLI tool)
- **FreeRDP (xfreerdp)** (advanced users)

Example:

- xfreerdp /v:IP_ADDRESS /u:USERNAME /p:PASSWORD

---

## 🔒 Security Tips

- Use strong passwords 🔐  
- Avoid exposing port 3389 🌐  
- Use VPN for secure access 🔑  

---

## ❗ Troubleshooting

### Can't connect?
- Check IP address  
- Ensure Windows PC is ON  

### Connection refused?
- Verify RDP is enabled  
- Check firewall rules  

### Authentication failed?
- Check username/password  
- Try format: `PCNAME\\username`  

---

## ✅ Done!

You can now connect to a Windows PC from Linux using RDP 🚀
