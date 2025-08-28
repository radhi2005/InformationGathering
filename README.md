# Ex-02 InformationGathering
Information Gathering Techiques
# NAME:RADHIMEENA M
# REG NO:212223040159

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

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="766" height="415" alt="image" src="https://github.com/user-attachments/assets/b1866e8c-3ccd-4ba4-8d38-7dcc8ac67463" />

### Finding Hosting Company :

get further detail by using ip2location.com website.

## output
<img width="786" height="417" alt="image" src="https://github.com/user-attachments/assets/da12434f-2683-4670-8dc2-2af0cf822b9a" />

### History of the website :

## output

https://web.archive.org/

<img width="782" height="424" alt="image" src="https://github.com/user-attachments/assets/16a28dad-c656-4079-9e41-382e4e32b141" />

### ping command :
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/918e8f23-0a65-490a-9aeb-f08625cc3629" />

### netcat :

sudo nc example.com 80

GET / HTTP/1.1

Host: example.com

### output

<img width="751" height="591" alt="image" src="https://github.com/user-attachments/assets/6085307c-046c-4533-90d3-02d8ed2c50cd" />

### nmap :

### output

<img width="762" height="293" alt="image" src="https://github.com/user-attachments/assets/4e49e6d2-d8b7-4f59-b7b5-330cdbef667d" />

### whatweb :

## output:

<img width="772" height="214" alt="image" src="https://github.com/user-attachments/assets/68a573be-e20e-4c46-9169-c0bfc41bdfc9" />

<img width="775" height="497" alt="image" src="https://github.com/user-attachments/assets/338b690c-4838-43f4-8ced-e7185ce7b8df" />

### httprint :

### output

<img width="782" height="630" alt="image" src="https://github.com/user-attachments/assets/2b2a9009-a8e0-4193-ac11-dbcc186b6538" />

### TCP traceroute :

sudo traceroute -T icc-cricket.com

## output

<img width="1028" height="773" alt="image" src="https://github.com/user-attachments/assets/8f0da9cb-6908-409f-b1a7-98990d618765" />

### UDP traceroute :

sudo traceroute -U icc-circket.com

## output

<img width="1028" height="773" alt="image" src="https://github.com/user-attachments/assets/89f3a872-2119-4c4d-a139-b94178547738" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
