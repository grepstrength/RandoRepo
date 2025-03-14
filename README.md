# RandoNotes
Random series of my own personal notes for pentesting.

### Hack the Box VPN
When you connect to HTB VPN, but are unable to connect to the internet as well, run the below command as `root` or `sudo`.

```
route del -net default gw <HTB_VPN_IP_ADDRESS> netmask 0.0.0.0 dev tun0
```
Reference: [Bob McKay's Blog](https://bobmckay.com/i-t-support-networking/ethical-hacking/hackthebox-vpn-internet-not-working-aka-enable-split-tunneling-on-htb-vpn/)
