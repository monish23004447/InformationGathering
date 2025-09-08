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
![Uploading 482944052-58803e41-5191-4be3-b5f6-314679e06f7b.png…]()
<img width="1918" height="1018" alt="482944222-565e7608-2cab-4d1a-a530-9d5b20da0580" src="https://github.com/user-attachments/assets/58af7301-c4f8-4c01-9209-6e50d2185989" />
<img width="1918" height="1015" alt="482944439-094d949b-8a0f-4eb1-8224-2ffe2216a478" src="https://github.com/user-attachments/assets/18fee1a6-4bc9-4297-8511-83bfd8a85cf7" />
<img width="1917" height="1016" alt="482944560-baa798f8-8687-486b-a839-92d0e30cad74" src="https://github.com/user-attachments/assets/2b2dcd89-97e6-45ef-ada0-38bb119146f5" />

### Finding Hosting Company :
<img width="1919" height="972" alt="482945031-d4f87da2-4a71-47f1-8ab5-f3cd795c02f0" src="https://github.com/user-attachments/assets/e667fe6c-380f-46ad-b555-a5214432b1c3" />
<img width="1918" height="1017" alt="482945148-aec6b44d-5411-47d9-8c9a-6ee23a8c7850" src="https://github.com/user-attachments/assets/fdf206d6-1ea1-473b-b1bd-e9b97d1dba4a" />
<img width="1919" height="1020" alt="482945315-f8d5bf8c-d643-48d5-87ed-d933fa54077d" src="https://github.com/user-attachments/assets/39c2c80c-d8a6-4468-98d7-4046c605b4fe" />


### ping command :
### Kali Linux:
<img width="1918" height="1017" alt="482946972-0ecfdacd-2c69-4afb-8c1b-07806d1aadd8" src="https://github.com/user-attachments/assets/e35a52ad-1cc3-4e41-8438-4693e6e9fcfa" />

### Windows:
<img width="1470" height="482" alt="482947230-b36cfbb1-16d2-4c55-9023-a56ab0b1280e" src="https://github.com/user-attachments/assets/512be07e-d40b-48a1-9a68-c23faf052449" />


### whois :
<img width="1918" height="1022" alt="482949794-e28806bb-f24d-44e9-834e-eadead5649f3" src="https://github.com/user-attachments/assets/dca22e9f-27c2-406e-aa0e-26d2f7faa8d0" />

### netcat :
<img width="1917" height="391" alt="482950429-0c598f28-83f9-459d-b231-33efc43d9fbb" src="https://github.com/user-attachments/assets/fe9269b4-b1b2-4963-a2cc-0cc587837713" />

### nmap :
<img width="1918" height="302" alt="482951000-87919d8f-ab32-40d7-acd3-4dd25951c0f4" src="https://github.com/user-attachments/assets/447bf5c4-da8d-46b9-b6b9-fc7b688c0465" />

### whatweb :
<img width="1918" height="192" alt="482951144-238e0829-14b1-485d-bb3c-88c59f9276de" src="https://github.com/user-attachments/assets/8eafb00c-9dbb-470e-96da-0d53d3e24aca" />

### httprint :
<img width="1918" height="907" alt="482951612-1c8ee702-7702-4345-9c1c-31a1f7d06b69" src="https://github.com/user-attachments/assets/fc29ad9c-ae5e-4070-b956-f48ebbfeb172" />

### TCP traceroute :
<img width="1918" height="342" alt="482951804-0b82904e-26ea-4f76-b870-9963698d14e0" src="https://github.com/user-attachments/assets/d89aa035-c98d-4300-bebf-565965eeb7bc" />

### UDP traceroute :
<img width="1918" height="507" alt="482952073-4f8103d9-fc73-4eeb-8bb2-96b4c6075273" src="https://github.com/user-attachments/assets/ab8cdd86-f735-4533-ae8b-8e6971799571" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
