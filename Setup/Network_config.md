
- **Gateway** -> `10.0.2.1`
- **Attacker:** Kali Linux -> `10.0.2.30` 
* **XDR:** Ubuntu -> `10.0.2.40`
* **Victim:** Windows 10 -> `10.0.2.50`

---

>[!Tip]
>Windows doesn't allow ti receive pings, blocking by default ICMP Echo Request, so to be sure that all the machines are well configured and reachable from the other, I had to activate a
>this rule of the firewall that disabled by default, so on PowerShell with administrative privileges:
>`Enable-NetFirewallRule -Name FPS-ICMP4-ERQ-In`


