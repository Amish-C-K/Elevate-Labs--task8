# 🛡️ Task 8: VPN Setup & Privacy Protection Report

## 🎯 Objective:
Understand the role of VPNs in protecting online privacy and ensuring secure communication by using a free VPN client.

---

## 🧰 Tools Used:
- **VPN Client**: ProtonVPN (Free Tier)
- **Website**: [whatismyipaddress.com](https://whatismyipaddress.com) – for IP checking
- **Test Site**: `https://example.com` – for encrypted traffic confirmation

---

## ⚙️ Step-by-Step VPN Setup

### 1. 🔍 Choose VPN:
- Selected **ProtonVPN** due to its strong privacy reputation and free plan availability.

### 2. 📝 Account Creation:
- Visited [https://protonvpn.com](https://protonvpn.com)
- Signed up using email verification for a **Free Tier** account.

### 3. 💻 Download and Installation:
- Downloaded ProtonVPN client for Windows.
- Installed the VPN software and logged into the application.

### 4. 🌐 Connection:
- Connected to the **"India - Free #1"** server.
- VPN status: **Connected**

  ![connect](https://github.com/Amish-C-K/Elevate-Labs--task8/blob/main/images/t8-3.png)

### 5. ✅ IP Address Check:
- Before VPN: My real IP showed my actual location.
- After VPN: New IP location changed to Switzerland (Proton's Free IP).
- Tool used: [https://whatismyipaddress.com](https://whatismyipaddress.com)

  ![check ip](https://github.com/Amish-C-K/Elevate-Labs--task8/blob/main/images/t8-4.png)

### 6. 🔐 Encrypted Traffic Test:
- Browsed `https://example.com` and verified it loaded securely via HTTPS.
- All traffic routed through VPN tunnel (AES-256 encrypted).

### 7. IP/DNS Leak Tests
whatismyipaddress.com:

Post-VPN IP: 103.125.235.22 (Tokyo, Japan).

DNSLeakTest:

All DNS servers belong to ProtonVPN (Tokyo).

✅ No leaks detected.

  ![check](https://github.com/Amish-C-K/Elevate-Labs--task8/blob/main/images/t8-6.png)

### 8. WebRTC Leak Test
WebRTC IP: Matches VPN IP (103.125.235.22).

Result: No Leak.

✅ Success: WebRTC doesn’t expose your real IP.

  ![check](https://github.com/Amish-C-K/Elevate-Labs--task8/blob/main/images/t8-7.png)

### 9. HTTPS Encryption & Browser Privacy
Browser Check:

IP: 103.125.x.x (Tokyo, Japan) → VPN is masking IP.

Tor: Not in use (expected with VPN).

Do Not Track: Disabled (consider enabling for extra privacy).

  ![check](https://github.com/Amish-C-K/Elevate-Labs--task8/blob/main/images/t8-5.png)

### 10. 🔄 Disconnection & Speed Comparison:
- Disconnected VPN and tested browsing:
  - VPN ON: Slightly slower due to encryption overhead.
  - VPN OFF: Regular speed resumed.
- IP address returned to original.

  ![check](https://github.com/Amish-C-K/Elevate-Labs--task8/blob/main/images/t8-8B.png)
  ![check](https://github.com/Amish-C-K/Elevate-Labs--task8/blob/main/images/t8-8A.png)

## 🔐 VPN Encryption & Privacy Features

### 🔒 Encryption:
- ProtonVPN uses **AES-256 encryption**
- Key exchange via **4096-bit RSA**
- Protocol: OpenVPN/IKEv2 (Free version uses OpenVPN)

### 🛡️ Privacy Features:
- No-logs policy
- Based in privacy-friendly Switzerland
- DNS leak protection
- Kill switch available (paid version)

---

## ✅ VPN Benefits:
- Masks IP address and hides location.
- Encrypts data on public Wi-Fi (prevents packet sniffing).
- Bypasses censorship and geo-blocking.
- Protects against ISP monitoring.

### ⚠️ VPN Limitations:
- Free plans may have speed caps or fewer servers.
- Doesn’t protect against malware/phishing websites.
- Some websites block VPN traffic (e.g., banks).
- Logging policies differ between providers — trust is critical.

---

## 📘 Interview Questions to Expect:

1. What is a VPN and how does it work?
2. How does a VPN protect your online data?
3. What are the differences between paid and free VPNs?
4. Can a VPN guarantee complete anonymity?
5. Why is DNS leak protection important?
6. What encryption standards are used in VPNs?

---

## 🏁 Final Outcome:
- ✅ Successfully set up and tested ProtonVPN
- ✅ Verified IP masking and encrypted traffic
- ✅ Understood VPN privacy strengths and limitations

