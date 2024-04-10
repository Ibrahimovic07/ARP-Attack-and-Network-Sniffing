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

![arp-a](https://github.com/prithviraj5703/ARP-Attack-and-Network-Sniffing/assets/121418418/9b9f52db-8ec5-4222-9286-e6f81faf5685)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![arpspoof](https://github.com/prithviraj5703/ARP-Attack-and-Network-Sniffing/assets/121418418/16855139-7ac5-4346-a8bb-353bcb924250)

 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![ftp](https://github.com/prithviraj5703/ARP-Attack-and-Network-Sniffing/assets/121418418/1e345053-dc1a-488f-94ad-001d1fbbb0c8)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![dsniff](https://github.com/prithviraj5703/ARP-Attack-and-Network-Sniffing/assets/121418418/8c918348-a2c5-4e6e-944e-b7f49c5d3960)


Invoke the wireshark and examine the various menus  and controls of the tool:

![wireshark](https://github.com/prithviraj5703/ARP-Attack-and-Network-Sniffing/assets/121418418/ab6973c3-143e-47f6-8710-df78184d0e2d)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
