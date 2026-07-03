<p align="center">
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  </a>
  <a href="https://www.kali.org/">
    <img src="https://img.shields.io/badge/Kali_Linux-268BEE?style=for-the-badge&logo=kali-linux&logoColor=white" alt="Kali Linux">
  </a>
</p>

# RECON1.2 // Tactical Network Reconnaissance Suite

RECON1.2 is a specialized, lightweight network auditing utility engineered for rapid reconnaissance and target surface mapping. Developed with a "zero-dependency" philosophy, this tool is designed to provide security operators and researchers with an efficient way to perform target vector analysis, port enumeration, and service banner identification within complex network environments.

Built natively in Python, RECON1.2 prioritizes speed and tactical precision, making it a reliable asset during both early-stage footprinting and active engagement phases. Whether you are conducting internal infrastructure hardening or authorized security assessments, RECON1.2 delivers immediate, actionable intelligence on your target's listening services.

---

### 🖥️ Usage Example

Saat kamu menjalankan *tool* ini, ini adalah tampilan *banner* dan cara menggunakannya di terminal:

```text
============================================================
   ██████╗ ███████╗ ██████╗  ██████╗ ███╗   ██╗ ██╗ ██████╗ 
   ██╔══██╗██╔════╝██╔════╝ ██╔═══██╗████╗  ██║███║╚════██╗
   ██████╔╝█████╗  ██║      ██║   ██║██╔██╗ ██║╚██║ █████╔╝
   ██╔══██╗██╔══╝  ██║      ██║   ██║██║╚██╗██║ ██║██╔═══╝ 
   ██║  ██║███████╗╚██████╗ ╚██████╔╝██║ ╚████║ ██║███████╗
   ╚═╝  ╚═╝╚══════╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═══╝ ╚═╝╚══════╝
                  RECON TOOL v1.2 // BY NEUROPRASSSSS
============================================================

                 RECON TOOL v1.2 // BY NEUROPRASSSSS

[*] Starting high-speed scan on 192.168.1.1...

[+] Port 22    : OPEN
[+] Port 80    : OPEN
[+] Port 443   : OPEN

[*] Scan complete.
[+] Results saved to scan_results.txt

```
🚀 How to Run
If this is your first time accessing this repository, please clone it to your local machine first:
```
git clone https://github.com/panjipras36-star/RECON1.2.git
```
Navigate to the project director
```
cd RECON1.2
```

Run the scanner:
```
python3 recon.py -t <TARGET_IP>
```

🚀 Usage

Basic Scan (Default Ports):
```
python3 recon.py -t <TARGET_IP>
```
Custom Port Scan & Save Results:
```
python3 recon.py -t <TARGET_IP> -p 22,80,443,8080 -o results.txt

```

⚖️ Disclaimer

RECON1.2 is intended for educational purposes and authorized security testing only. The developer assumes no liability for any misuse, damage, or legal consequences arising from the use of this tool. Use this tool responsibly and strictly within controlled environments.
