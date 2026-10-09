# Home Lab: Attack, Clean Up, Rescan

A VirtualBox home lab where I attack deliberately vulnerable machines from Kali, then clean up what I broke and rescan to check the fix worked. Each write-up covers what I did, what it means on a real network, and how to fix it.

## Write-ups

| Write-up | Target | What it covers |
|---|---|---|
| [recon-and-vsftpd-backdoor.md](./recon-and-vsftpd-backdoor.md) | Metasploitable 2 | Nmap recon, exploiting CVE-2011-2523, cleanup and rescan |
| [samba-exploit.md](./samba-exploit.md) | Metasploitable 2 | Exploiting CVE-2007-2447 |
| [dvwa-sql-injection.md](./dvwa-sql-injection.md) | DVWA | SQL injection and cracking the hashes it exposed |
| [dvwa-xss.md](./dvwa-xss.md) | DVWA | Reflected and stored XSS |

Metasploitable 2 and DVWA are deliberately vulnerable practice targets, run in my own VirtualBox lab.
