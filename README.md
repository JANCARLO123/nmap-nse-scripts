Repository for NSE (Nmap Scripting Engine) development. You will find my scripts (including non-official ones), libraries, resources and other related material from my workshops. 

TODO
================
-Finishing SMB2 NSE library
-Currently working on password mangling functionality

Paulino Calderon
calderon()websec.mx
http://calderonpale.com

Save the script above in the “scripts” folders of the Nmap installation.

For Windows: C:\Program Files (x86)\Nmap\scripts
For Linux: /usr/share/nmap/scripts/ or /usr/local/share/nmap/scripts/


map -Pn -p445 --script smb-vuln-ms17-010 192.168.200.0/24 -oN output.tx

