# RandoRepofRepos
Random series of my own personal notes and favorite repos for pentesting. Updated regularly as I remember to add things.

### Hack the Box VPN
When you connect to HTB VPN, but are unable to connect to the internet as well, run the below command as `root` or `sudo`.

```
route del -net default gw <HTB_VPN_IP_ADDRESS> netmask 0.0.0.0 dev tun0
```
Reference: [Bob McKay's Blog](https://bobmckay.com/i-t-support-networking/ethical-hacking/hackthebox-vpn-internet-not-working-aka-enable-split-tunneling-on-htb-vpn/)

### Network

 - [ligolo-ng](https://github.com/nicocha30/ligolo-ng) - A powerful network tunneling tool using TUN interfaces.
 - [NetExec](https://github.com/Pennyw0rth/NetExec) - Network execution tool. Successor to CrackMapExec.
 - [Impacket](https://github.com/fortra/impacket) - Suite of Python tools for various Windowws network protocols. 
 - [Evil-WinRM](https://github.com/Hackplayers/evil-winrm) - CLI for WinRM.
 - [Rubeus](https://github.com/GhostPack/Rubeus) - Tool to conduct numerous Windows AD attacks.
 - [Responder](https://github.com/SpiderLabs/Responder) - Tool to poison the LLMNR and NBT-NS protocols on a network.
 - [MimiKatz](https://github.com/gentilkiwi/mimikatz) - Tried and true cred dumper.
 - [hashcat](https://github.com/hashcat/hashcat) - Tried and true password cracker.
 - [BloodHound](https://github.com/SpecterOps/BloodHound) - Noisy Active Directory enumeration tool.
 - [Certify](https://github.com/GhostPack/Certify) - Tool to enumerate and abuse AD misconfigurations.
 - [PEASS-ng](https://github.com/peass-ng/PEASS-ng/tree/master) - Windows and Linux priv esc enumeration tools.
 - [enum4linux](https://github.com/CiscoCXSecurity/enum4linux) - Windows and Samba enumeration tool. 


### Web/Cloud

 - [gobuster](https://www.kali.org/tools/gobuster/) - Web site directory and file brute force tool. 
 - [SQLMap](https://github.com/sqlmapproject/sqlmap) - Automatic web app SQLi enumeration tool.
 - [GitHarvester](https://github.com/metac0rtex/GitHarvester) - Uses regex to search for GitHub users and projects to harvest credentials.
 - [AWSBucketDump](https://github.com/jordanpotti/AWSBucketDump) - Enumerates AWS S3 buckets for interesting files. 
