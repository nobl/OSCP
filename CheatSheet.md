# 1. LDAP

**1. LDAPSEARCH**

ldaspsearch -x -h 10.10.10.107

**2. NMAP**

┌──(kali㉿kali)-[~/HackTheBox]
└─$ locate -r nse$ | grep -i ldap
/usr/share/nmap/scripts/ldap-brute.nse
/usr/share/nmap/scripts/ldap-novell-getpass.nse
/usr/share/nmap/scripts/ldap-rootdse.nse
/usr/share/nmap/scripts/ldap-search.nse

┌──(kali㉿kali)-[~/HackTheBox]
└─$ nmap --script ldap-search 10.10.010.107
