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
- Windows Server AD DS Installation
![Windows Server AD DS Installation](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/installazione%20ad%20su%20homelab%20winserver2022.png)

- Active Directory Users and Computers
![Active Directory Users and Computers](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/active%20directory%20users%20and%20computers.png "active directory users and computers" )
- Domain Controller Dashboard
![Domain Controller Dashboard](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/domain_controller_funzionante.png)

### DNS Configuration
- DNS Manager with Zones
  
![DNS Manager with Zones](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/DNS%20manager.png)
- DNS Resolution Working
  
![DNS Resolution Working](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/dns%20resolving%20fedora.homelab.local.png)
- nslookup success
  
![nslookup Success](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/nslookup%20homelab.local(dns%20resolve).png)

### Linux Integration
![Fedora Host Information](hostnamectl%20fedora.png)
- AD Integration Status
  
![AD Integration Status](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/realm%20list.png)
- User Authentication 
![User Authentication](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/getent%20passwd%20administrator%40homelab.local.png)
- SSSD Service Status
![SSSD Service Status](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/systemctl%20status%20ssd.png)

### Network & File Sharing
- SMB Shares List
  
![SMB Shares List](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/lista%20condivisioni.png)
- Shared Folder Properties

![Shared Folder Properties](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/propriet%C3%A0%20condivisione%20shared.png)

- SMB Access Test
  
![SMB Access Test](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/accesso%20ad%20una%20condivisone%20specifica%20e%20ls%20.png)

### Virtualization & Remote Access
- Virtual Machines Running
![Virtual Machines Running](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/vms%20running.png)

- Tailscale VPN Status
![Tailscale VPN Status](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/tailscale%20status.png)

- Windows VM with Internet
  
![Windows VM with Internet](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/vm%20win%20internet%20funziona.png)

### Server Management
- Server Manager Dashboard
![Server Manager Dashboard](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/server%20manager.png)
- Windows Server AD
![Windows Server AD](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/winserver%20AD.png)
- Shared Resources
![Shared Resources](https://github.com/chi04fern/homelab-enterprise/blob/main/screenshots/shares%20on%20windows%20server.png)

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
