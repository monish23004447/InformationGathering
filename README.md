# Ex-02 InformationGathering
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
<img width="1789" height="1083" alt="481462318-0a80035e-4828-4fdd-9ded-bc18e830f666" src="https://github.com/user-attachments/assets/d047e5f1-b21a-449f-90b2-eaed8c9b7727" />



### Finding Hosting Company :
<img width="1906" height="1075" alt="image" src="https://github.com/user-attachments/assets/80428ad8-00d4-464a-9492-10ae47d04951" />

<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/e628b7d9-ad28-4209-b7f7-470c30b8f08e" />


### History of the website :
<img width="1919" height="992" alt="image" src="https://github.com/user-attachments/assets/3a15893c-6f98-45d8-8b47-1fbc6438bd77" />

<img width="1893" height="1007" alt="image" src="https://github.com/user-attachments/assets/c993c51c-3bc9-4e35-b137-f2bff5717d91" />

### ping command :
<img width="721" height="865" alt="image" src="https://github.com/user-attachments/assets/1e4ccf96-7edd-446d-9d94-413858f4718f" />


### whois :
<img width="1202" height="965" alt="image" src="https://github.com/user-attachments/assets/6feb01f5-0625-4094-b985-93be41b17dd8" />

### netcat :
<img width="874" height="93" alt="image" src="https://github.com/user-attachments/assets/99d1aff0-f354-408a-a26b-6caac6435f9e" />


### nmap :
<img width="992" height="231" alt="image" src="https://github.com/user-attachments/assets/1d0e256a-6860-4425-9d3a-00f316f99b72" />


### whatweb :
<img width="1903" height="135" alt="image" src="https://github.com/user-attachments/assets/cd4e8cf8-0e98-40a9-9577-b3d0b4bf25d0" />


### httprint :
<img width="862" height="809" alt="image" src="https://github.com/user-attachments/assets/1a77b09b-db24-4d81-90e3-098ec62822d2" />


### TCP traceroute :
<img width="766" height="106" alt="image" src="https://github.com/user-attachments/assets/afba32bd-0b71-42e4-b92f-747eae0615e9" />


### UDP traceroute :
<img width="714" height="88" alt="image" src="https://github.com/user-attachments/assets/aad586a8-bb05-4394-95c4-ed1e35c65f1b" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
