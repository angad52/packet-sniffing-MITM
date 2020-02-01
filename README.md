# packet-sniffing
 A simple script to perform MITM (Man In The Middle) Attack by arp-spoofing and packet-sniffing.
 
 ***IT WILL ONLY WORK ON HTTP WEBSITES***

# First Run these command in your terminal:-

***1. sudo apt-get install python***

***2. sudo apt-get install python3***

***3. sudo apt-get install scapy***

***4. sudo apt-get install python-pip***

***5. pip install scapy-python3***

***6. pip install scapy_http***

***7. echo 1 > /proc/sys/net/ipv4/ip_forward***

# After installing the above packeges, you are ready for MITM.Just follow these commands.

Don't close the terminal during the below processes

***sudo python arp_spoofing.py***

Enter "Target IP" and "Gateway IP".

To check the gateway ip enter ***route -n*** in terminal.

***sudo python packet_sniffer.py***

Enter the "Interface" on which you want to perform the MITM.
