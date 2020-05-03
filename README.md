# network_scanner
it is use to scan the network connecting on the same network
import scapy.all as scapy

def scan(ip):
    scapy.arping(ip)


scan("10.0.2.1")


NOTE in function scan i use my ip of router  so you can finnd the router ip by 
just arp -a
