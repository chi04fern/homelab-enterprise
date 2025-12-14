# 🏢 Enterprise Homelab - Windows AD & Linux Integration

## 📖 Overview
Un ambiente homelab enterprise che replica infrastrutture aziendali, dimostrando l'integrazione tra Windows Active Directory e Linux Fedora.

## 🏗️ Architecture
- **Domain Controller**: Windows Server 2022 (192.168.122.10)
- **Linux Client**: Fedora Workstation (192.168.122.50)
- **Domain**: homelab.local
- **Services**: Active Directory, DNS, SMB File Sharing

## 🎯 Key Achievements
✅ Integrazione completa Windows AD + Linux Fedora  
✅ Configurazione DNS enterprise con forward/reverse zones  
✅ Autenticazione cross-platform funzionante  
✅ File sharing SMB operativo  
✅ Troubleshooting di problemi complessi risolti

## 📸 Evidence Gallery
### Active Directory & Domain Controller
![Windows Server AD DS Installation](installazione%20ad%20su%20homelab%20winserver2022.png)
![Active Directory Users and Computers](active%20directory%20users%20and%20computers.png)
![Domain Controller Dashboard](domain_controller_funzionante.png)

### DNS Configuration
![DNS Manager with Zones](DNS%20manager.png)
![DNS Resolution Working](dns%20resolving%20fedora.homelab.local.png)
![nslookup Success](nslookup%20homelab.local(dns%20resolve).png)

### Linux Integration
![Fedora Host Information](hostnamectl%20fedora.png)
![AD Integration Status](realm%20list.png)
![User Authentication](getent%20passwd%20administrator@homelab.local.png)
![SSSD Service Status](systemctl%20status%20ssd.png)

### Network & File Sharing
![SMB Shares List](lista%20condivisioni.png)
![Shared Folder Properties](proprietà%20condivisione%20shared.png)
![SMB Access Test](accesso%20ad%20una%20condivisone%20specifica%20e%20ls%20.png)

### Virtualization & Remote Access
![Virtual Machines Running](vms%20running.png)
![Tailscale VPN Status](tailscale%20status.png)
![Windows VM with Internet](vm%20win%20internet%20funziona.png)

### Server Management
![Server Manager Dashboard](server%20manager.png)
![Windows Server AD](winserver%20AD.png)
![Shared Resources](shares%20on%20windows%20server.png)

## 🛠️ Technical Skills Demonstrated
- Active Directory Domain Services
- DNS Management (Forward/Reverse Zones)
- Linux-Windows Integration (SSSD, realm)
- Network Troubleshooting
- Virtualization (KVM/libvirt)
- SMB/CIFS File Sharing Configuration
- Remote Access & VPN Setup
- System Administration & Service Management

---

## Quick Start
```bash
# Clone this repository
git clone https://github.com/chi04fern/homelab-enterprise
