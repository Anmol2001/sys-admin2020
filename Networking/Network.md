Q1 


Q2 This question can be done by installing and using the "whois" command followed by the domain name i.e. iitmandi.ac.in as students.iitmandi.ac.in is a subdomain of it.
So it is bought from ERNET.

Q3 It uses simple Nmap command :
anmol@anmol:~$ nmap -p 0-2000 iitmandi.co.in

Starting Nmap 7.60 ( https://nmap.org ) at 2020-09-10 00:17 IST
Nmap scan report for iitmandi.co.in (14.139.34.11)
Host is up (0.093s latency).
Not shown: 1990 closed ports
PORT     STATE    SERVICE
0/tcp    filtered unknown
22/tcp   open     ssh
25/tcp   filtered smtp
53/tcp   open     domain
80/tcp   open     http
137/tcp  filtered netbios-ns
138/tcp  filtered netbios-dgm
139/tcp  filtered netbios-ssn
443/tcp  open     https
445/tcp  filtered microsoft-ds
1434/tcp filtered ms-sql-m

Nmap done: 1 IP address (1 host up) scanned in 28.21 seconds


So it is clearly visible that it has 4 open ports.
