# 🔍 Day 2 – Network Discovery with Nmap & Zenmap

## 🛠️ Tools Used  
- Windows 11 Pro  
- Nmap CLI & Zenmap GUI  
- Wireshark  
- TP-Link ER707-M2 Router  
- TP-Link TL-SG105 Switch  
- PowerShell  
- Web Browser  

---

## 🚀 What I Did  

### 1️⃣ Tool Verification  
Checked Nmap version via PowerShell and launched Zenmap GUI to confirm installation.

<img width="831" height="163" alt="3ZJJVbw" src="https://github.com/user-attachments/assets/b0fb1f9f-b656-48ce-84df-94058c2ccd7b" />

---

<img width="675" height="323" alt="nRMFgGb" src="https://github.com/user-attachments/assets/f2b8d013-5c33-4404-9a2e-e53adf39d14c" />

### 2️⃣ Network Info  
Ran `ipconfig /all` to find my IPv4 address and subnet mask for targeting scans.

<img width="738" height="239" alt="EnfgHTR" src="https://github.com/user-attachments/assets/3db3b4ae-f300-4c37-b596-ffad65e59d6b" />

### 3️⃣ Wireshark Capture  
Started Wireshark capture on my Ethernet adapter with a filter to focus on HTTP and UDP traffic during scans.

<img width="844" height="464" alt="6dxjHmE" src="https://github.com/user-attachments/assets/d32b122b-bcba-4b55-bd42-d3d8b9759302" />

### 4️⃣ Nmap CLI Scans  
Performed full subnet scan and ping sweep using Nmap CLI, and saved results to a text file.

<img width="792" height="340" alt="v3vuivd" src="https://github.com/user-attachments/assets/f3f6d0d2-826e-4e09-a893-267b1681a57e" />

### 5️⃣ Zenmap GUI Scan  
Used Zenmap’s Intense scan profile on the subnet, reviewed results, and saved output.

<img width="723" height="418" alt="pjm1CIH" src="https://github.com/user-attachments/assets/f6ed7c6c-1895-4867-adab-20888d393d93" />

### 6️⃣ Hardware Verification  
Made sure router and switch were powered and connected. Logged into router web admin at 192.168.0.1 to check connected devices.

<img width="523" height="255" alt="25FrjWx" src="https://github.com/user-attachments/assets/b62221f7-2daf-4ede-8ef1-82c9834a8b35" />

---

<img width="999" height="758" alt="FELxoYR" src="https://github.com/user-attachments/assets/dde65e85-a0bc-447d-b014-57f77ce7f720" />

---

## 📚 What I Learned  

- How to verify network tool installations and basic IP info on Windows.  
- Running Nmap scans via CLI and GUI for comprehensive network discovery.  
- Capturing and filtering network traffic with Wireshark during active scanning.  
- Accessing router admin interface to cross-check connected devices.  
- Noticing differences between scan results and actual network connections due to firewalls or device states.  


