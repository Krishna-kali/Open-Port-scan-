# Open-Port-scan-
To perform open port first we need to find the IP address, to find the IP address after that install nmap
1. Install Nmap
.Linux: sudo apt install nmap (Debian/Ubuntu) or sudo yum install nmap (CentOS/RHEL).
.macOS: brew install nmap.
.Windows: Download from nmap.org.
2. Identify Your Local Network Range
.Find your device’s IP and subnet mask:
.Linux/macOS: Run ifconfig or ip a.
.Windows: Run ipconfig.

Example Output:![image alt](https://github.com/Krishna-kali/Open-Port-scan-/blob/287888f19fa77d2445a6eea038c063e7246edb50/IMG_20250807_142237_971%20(2).png)
3. Scanning for open Ports
open nmap and type the command 
Basic scan : Discover live host and open ports
the for it is : nmap -T4 --open 192.168.1.0/24
![image alt](https://github.com/Krishna-kali/Open-Port-scan-/blob/c12bb70cf3dc5422bac1b911f03a4d27399e465d/Screenshot_2025-08-07-15-10-04-368.png)
we can aggressive scan also in nmap by using the -A with sudo and there lot of options in nmap for port scanning, we can use different types of flag in nmap, to know more about nmap flag use --help or --man to know about the flags
