# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
<img width="1894" height="1025" alt="image" src="https://github.com/user-attachments/assets/a1c02f13-deaf-4cdb-956e-afaf4b6bb0bc" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output
<img width="925" height="1030" alt="6" src="https://github.com/user-attachments/assets/327727aa-f949-4ccd-a7e9-a9d9686c7d69" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="1042" height="936" alt="image" src="https://github.com/user-attachments/assets/ae0be5d7-2bcd-4c93-8f4d-4e2ec7537479" />
<img width="912" height="901" alt="image" src="https://github.com/user-attachments/assets/08a6a6bc-1707-482c-81f2-58bfcc3b9b13" />



## History of the website:
## output
https://web.archive.org/
<img width="1702" height="1013" alt="image" src="https://github.com/user-attachments/assets/979d089d-b158-4ab2-85e3-3500a5a28d75" />
<img width="1561" height="889" alt="image" src="https://github.com/user-attachments/assets/b12b29f2-ce24-4d92-a1cc-dd2ca3faee64" />


# Webserver Fingerprinting:

## nmap:
###output
<img width="925" height="1030" alt="1" src="https://github.com/user-attachments/assets/c11f391d-bf18-43ae-9c72-5832c7ebd991" />

Purpose: Scans a target system to find open ports, running services, and network details.

Example command

nmap www.google.com

Sample Output

Starting Nmap
Nmap scan report for www.google.com
PORT     STATE SERVICE
80/tcp   open  http
443/tcp  open  https


## Whatweb
### output
<img width="925" height="1030" alt="2" src="https://github.com/user-attachments/assets/cb20eea5-9255-414e-9351-6cf5af04f9d1" />

 Purpose: Identifies technologies used by a website (server type, CMS, frameworks, etc.).

Example command

whatweb www.google.com

Sample Output

http://www.google.com [200 OK]
Country[UNITED STATES]
IP[142.250.183.196]
HTML5
HTTPServer[gws]


# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="925" height="1030" alt="3" src="https://github.com/user-attachments/assets/f78d7e2a-15ad-43ee-9088-7a697a1b11f5" />

Command

sudo traceroute -T www.google.com

Purpose: Tracks route packets take using TCP protocol (useful when ICMP is blocked).

Sample Output

1  192.168.1.1
2  10.0.0.1
3  172.217.160.78

Result:
Shows path traveled by TCP packets from your system to destination server
## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="925" height="1030" alt="4" src="https://github.com/user-attachments/assets/f31bdf2b-5510-45be-ac44-7993b2df15db" />

Command

sudo traceroute -U www.google.com

Purpose: Tracks route using UDP packets.

Sample Output

1  192.168.1.1
2  10.0.0.1
3  142.250.183.196

## ICMP Traceroute:
sudo traceroute  www.google.com
## output

<img width="925" height="1030" alt="5" src="https://github.com/user-attachments/assets/719a3bd5-d0e4-4a04-bd04-1c091f90c138" />

sudo traceroute www.google.com

Purpose: Default traceroute method using ICMP echo packets.

Sample Output

1  192.168.1.1
2  10.0.0.1
3  142.250.183.196



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
