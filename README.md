# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
<img width="1037" height="725" alt="image" src="https://github.com/user-attachments/assets/21ee59d7-98dc-4c31-b557-c57b9b514d33" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/2d870a17-4559-4e30-a8d8-e1a7632a97b4" />



Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/402d0e77-63da-4963-a624-4b14077fc0ff" />



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
