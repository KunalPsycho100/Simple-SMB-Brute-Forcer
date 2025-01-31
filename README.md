**#SMB Brute Forcer (Batch Script)**
Description
This highly efficient SMB brute-force tool is built using Batch scripting to automate authentication attempts against a Windows SMB service. It iterates through a provided wordlist, systematically attempting to establish a connection using the net use command. The script is designed for fast execution, handling failed attempts smoothly while maintaining stealth and reliability. With minimal dependencies, it offers a lightweight yet powerful solution for penetration testing and security assessments.

**Usage**
Enter the target IP address of the SMB service.
Specify the username for authentication.
Provide a password wordlist (e.g., wordlist.txt).

Example Command:

batch

smb_bruteforce.bat 192.168.1.10 Administrator wordlist.txt

⚠️ Disclaimer: This tool is intended for ethical security testing only and should not be used without proper authorization. 🚀
