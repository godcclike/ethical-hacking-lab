## NMAP
| Syntax | Description |
| ----------- | ----------- |
| `sudo nmap -sP <network subnet>` (192.168.0.0/24) | to ping every host in that entire subnet |
| `sudo nmap -sT -p <port> <network subnet>` (80,443 192.168.0.0/24) | to see the specific ports that are running on that entire subnet |
| `sudo nmap -sS -p <port> <network subnet>` (80,443 192.168.0.0/24) | to see the specific ports that are running on that entire subnet (Stealthy) |
| `sudo nmap -sS -D <decoy ip add> <ip add of target>` (80,443 192.168.0.0/24) | to see the specific ports that are running on that entire subnet (Stealthy with decoy ip) |
| `sudo nmap -O <ip add>` | to see what OS is the host using |
| `sudo nmap -A <ip add>` | to see the OS, what ports are open, ssh key, traceroute |
| `sudo nmap --script vuln <ip add>` | to find all vulnerabilities for that machine using all scripts |



[nmap categories](https://nmap.org/nsedoc/categories/)


[nmap vulnerability testing](https://nmap.org/nsedoc/categories/vuln.html)
