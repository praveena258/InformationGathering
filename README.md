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

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com



## nmap:
###output


## Whatweb
### output


## httprint
### output




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output


## UDP Traceroute:
sudo traceroute -U www.google.com
## output



## ICMP Traceroute:
sudo traceroute  www.google.com
## output






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
