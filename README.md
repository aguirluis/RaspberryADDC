# DietPi Samba Active Directory Domain Controller (ADDC) on Raspberry Pi

This project demonstrates how to set up a Raspberry Pi running **DietPi** as a lightweight **Active Directory Domain Controller (ADDC)** using **Samba 4**.  
It’s ideal for labs, homelabs, and small environments where you want to experiment with domain services without heavy hardware.

---

## 🚀 Features
- Minimal OS footprint with **DietPi**
- Samba 4 configured as an **Active Directory Domain Controller**
- Integrated **Kerberos** and **DNS**
- Easy provisioning of domains, users, and groups
- Lightweight enough to run on Raspberry Pi hardware

---

## 📦 Requirements
- Raspberry Pi 4 (recommended) or newer
- MicroSD card (≥16GB, Class 10 or better) or SSD
- Stable network connection
- DietPi image (download from [dietpi.com](https://dietpi.com/))
- Basic Linux knowledge

---

## 🛠 Installation Steps


### 2. Install Samba and Dependencies
```bash
Update package:
sudo apt-get update
Install Samba 4 and required tools:
sudo apt-get install samba samba-dsdb-modules samba-vfs-modules winbind libpam-winbind libnss-winbind krb5-user
During Kerberos setup, accept defaults (this will be configure later).

---

🌐 Step 3: Provision the Domain Controller


